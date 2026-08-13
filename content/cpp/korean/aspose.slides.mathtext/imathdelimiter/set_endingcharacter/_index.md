---
title: set_EndingCharacter()
second_title: Aspose.Slides for C++ API 참조
description: "구분자 종료 문자는 종료 또는 닫는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: ')'."
type: docs
weight: 79
url: /ko/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) 메서드


Delimiter Ending Character는 종료 또는 닫는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호, 중괄호와 같은 둘러싸는 문자입니다. 기본값: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
```

## 비고


예:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## 참고

* 클래스 [IMathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)