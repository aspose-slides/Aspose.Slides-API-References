---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Delimiter Separator Character는 구분자 객체에서 인수를 구분하는 문자를 지정합니다. 기본값은 '|'."
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/mathdelimiter/set_separatorcharacter/
---
## MathDelimiter::set_SeparatorCharacter(char16_t) 메서드

Delimiter Separator Character은(는) 구분자 객체에서 인수를 구분하는 문자를 지정합니다. 기본값은 '|'입니다.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_SeparatorCharacter(char16_t value) override
```

## 비고

예:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 참조

* 클래스 [MathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)