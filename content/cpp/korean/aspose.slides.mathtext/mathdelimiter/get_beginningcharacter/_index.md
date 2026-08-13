---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "구분자 시작 문자는 시작 또는 열리는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: '('."
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() 메서드


Delimiter Beginning Character는 시작, 즉 열리는 구분자 문자를 지정합니다. 수학 구분자는 괄호, 대괄호 및 중괄호와 같은 둘러싸는 문자입니다. 기본값: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## 비고


예제: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## 참조

* 클래스 [MathDelimiter](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)