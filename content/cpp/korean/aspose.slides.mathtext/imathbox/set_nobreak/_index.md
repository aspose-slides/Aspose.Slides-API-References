---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API 참조
description: "줄 바꿈 없음. 이 속성은 객체 상자에 대한 \"unbreakable\" 속성을 지정합니다. true인 경우 상자 내에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이진 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면 상자 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true"
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) 메서드


줄 바꿈 없음. 이 속성은 객체 상자에 대한 "unbreakable" 속성을 지정합니다. true인 경우 상자 내에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이항 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면 상자 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## 비고


예:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## 참고

* 클래스 [IMathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)