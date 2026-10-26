---
title: get_OperatorEmulator()
second_title: Aspose.Slides for C++ API 참조
description: "연산자 에뮬레이터. true인 경우, 상자와 그 내용은 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 해당 문자가 줄 바꿈 지점으로 사용될 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. 연산자 에뮬레이터는 '=='와 같이 하나 이상의 글리프가 결합하여 연산자를 형성할 때 자주 사용됩니다. 기본값: false"
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathbox/get_operatoremulator/
---
## MathBox::get_OperatorEmulator() 메서드

연산자 에뮬레이터. true인 경우, 상자와 그 내용은 단일 연산자로 동작하며 연산자의 속성을 상속합니다. 이는 예를 들어, 해당 문자가 줄 바꿈 지점으로 사용될 수 있고 다른 연산자와 정렬될 수 있음을 의미합니다. 연산자 에뮬레이터는 '=='와 같이 하나 이상의 글리프가 결합되어 연산자를 형성할 때 자주 사용됩니다. 기본값: false

```cpp
bool Aspose::Slides::MathText::MathBox::get_OperatorEmulator() override
```

## 비고

예시:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## 관련 항목

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)