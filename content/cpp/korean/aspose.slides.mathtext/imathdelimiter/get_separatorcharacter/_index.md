---
title: get_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 참조
description: "Delimiter Separator Character는 delimiter 객체에서 인수를 구분하는 문자를 지정합니다. 기본값: '|'."
type: docs
weight: 40
url: /ko/aspose.slides.mathtext/imathdelimiter/get_separatorcharacter/
---
## IMathDelimiter::get_SeparatorCharacter() 메서드


Delimiter Separator Character는 delimiter 객체에서 인수를 구분하는 문자를 지정합니다. 기본값: '|'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_SeparatorCharacter()=0
```

## 비고


예시: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 참조

* 클래스 [IMathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)