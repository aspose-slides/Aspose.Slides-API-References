---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API 참조
description: "연산자 에뮬레이터. true인 경우, 상자와 그 내용물은 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 해당 문자가 줄 바꿈 지점으로 사용될 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. 연산자 에뮬레이터는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다. 기본값: false"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathbox/get_operatoremulator/
---
## IMathBox::get_OperatorEmulator() 메서드


연산자 에뮬레이터. true인 경우, 상자와 그 내용물이 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 해당 문자가 줄 바꿈 지점으로 사용할 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. 연산자 에뮬레이터는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다. 기본값: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_OperatorEmulator()=0
```

## 비고


예시: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_OperatorEmulator(true);
```

## 참고

* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)