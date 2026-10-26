---
title: set_SeparatorCharacter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "Delimiter Separator Character는 delimiter 객체에서 인수를 구분하는 문자를 지정합니다. 기본값: '|'."
type: docs
weight: 53
url: /ko/aspose.slides.mathtext/imathdelimiter/set_separatorcharacter/
---
## IMathDelimiter::set_SeparatorCharacter(char16_t) 메서드

Delimiter Separator Character는 delimiter 객체에서 인수를 구분하는 문자를 지정합니다. 기본값: '|'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_SeparatorCharacter(char16_t value)=0
```

## 비고


예제:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_SeparatorCharacter(u'$');
```

## 참고

* 클래스 [IMathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)