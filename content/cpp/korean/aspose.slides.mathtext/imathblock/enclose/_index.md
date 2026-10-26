---
title: Enclose()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 이 블록의 하위 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸고 구분 문자로 구분합니다.
type: docs
weight: 14
url: /ko/aspose.slides.mathtext/imathblock/enclose/
---
## IMathBlock::Enclose(char16_t, char16_t, char16_t) 메서드


이 블록의 하위 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸고 구분 문자로 구분합니다.

```cpp
virtual System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::IMathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter)=0
```


### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| beginningCharacter | char16_t | Beginning character (usually left bracket) |
| endingCharacter | char16_t | Ending character (usually right bracket) |
| separatorCharacter | char16_t | Separator character |

### 반환값

[IMathDelimiter](../../imathdelimiter/) 유형의 수학 요소로, 지정된 문자를 프레임 및 구분 기호로 포함합니다.

## 비고



예제: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathDelimiter](../../imathdelimiter/)
* Class [IMathBlock](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)