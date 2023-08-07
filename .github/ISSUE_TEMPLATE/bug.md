name: 🐞 버그 리포트
description: 버그 리포트
title: "[버그 리포트]: "
body:
  - type: input
    id: bug
    attributes:
      label: 버그 사항
      description: 버그에 대한 내용을 자세하게 적어주세요. 😊
      placeholder: ex) 이것이 이것이 안됩니다.
    validations:
      required: true
  - type: input
    id: simulation
    attributes:
      label: 버그 시뮬레이션
      description: 버그를 발견하게 된 상황을 단계별로 적어주세요.
      placeholder: ex) 이것을 누르고 저것을 누르니 버그 발생
    validations:
      required: true
  - type: input
    id: want
    attributes:
      label: 원하던 상황
      description: 원하던 상황을 적어주세요.
      placeholder: ex) 이것을 누르고 저것을 누르니 화면 등장
    validations:
      required: true
