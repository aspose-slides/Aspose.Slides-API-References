---
title: get_Format()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트 서식 속성
type: docs
weight: 27
url: /ko/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() 메서드


텍스트 서식 속성

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
```

## 비고


예: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IPortionFormat](../../../aspose.slides/iportionformat/)
* 클래스 [MathematicalText](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)