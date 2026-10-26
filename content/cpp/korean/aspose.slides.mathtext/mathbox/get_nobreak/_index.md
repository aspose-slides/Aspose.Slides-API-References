---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API 참조
description: "No break 이 속성은 객체 박스의 \"unbreakable\" 속성을 지정합니다. true인 경우 박스 내부에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이진 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면 박스 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true"
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() 메서드


No break 이 속성은 객체 박스의 \"unbreakable\" 속성을 지정합니다. true인 경우 박스 내에서 줄 바꿈이 발생하지 않습니다. 이는 둘 이상의 이진 연산자로 구성된 연산자 에뮬레이터에 중요할 수 있습니다. 이 요소가 지정되지 않으면 박스 내부에서 줄 바꿈이 발생할 수 있습니다. 기본값: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## 비고


예시: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## 참조

* 클래스 [MathBox](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)