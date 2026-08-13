---
title: Accent()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 요소의 상단에 표시되는 악센트 기호(문자)를 설정합니다
type: docs
weight: 209
url: /ko/aspose.slides.mathtext/imathelement/accent/
---
## IMathElement::Accent(char16_t) 메서드

이 요소의 상단에 표시되는 악센트 기호(문자)를 설정합니다.

```cpp
virtual System::SharedPtr<IMathAccent> Aspose::Slides::MathText::IMathElement::Accent(char16_t accentCharacter)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| accentCharacter | char16_t | 악센트 문자. 값은 (U+0300\\u2013U+036F) 또는 (U+20D0\\u2013U+20EF) 범위 내에 있어야 합니다. |

### 반환 값

새 인스턴스 유형 [IMathAccent](../../imathaccent/)
## 비고



예시: 
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
```

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathAccent](../../imathaccent/)
* 클래스 [IMathElement](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)