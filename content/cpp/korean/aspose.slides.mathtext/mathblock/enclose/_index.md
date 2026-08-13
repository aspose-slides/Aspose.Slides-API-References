---
title: Enclose()
second_title: Aspose.Slides for C++ API 참조
description: 이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 프레임을 형성하도록 둘러씁니다
type: docs
weight: 222
url: /ko/aspose.slides.mathtext/mathblock/enclose/
---
## MathBlock::Enclose(char16_t, char16_t) 메서드

이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸서 프레임을 만듭니다

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char16_t | 시작 문자(보통 왼쪽 대괄호) |
| endingCharacter | char16_t | 끝 문자(보통 오른쪽 대괄호) |

### 반환값

프레임으로 지정된 문자를 포함하는 형식 [IMathDelimiter](../../imathdelimiter/)의 수학 요소
## 비고

예제:
```cpp
auto block = System::MakeObject<MathematicalText>(u"x")->Join(u"+y");
auto delimiter = System::ExplicitCast<IMathElement>(block)->Enclose(u'[', u']');
```

## MathBlock::Enclose(char16_t, char16_t, char16_t) 메서드

이 블록의 자식 요소를 괄호와 같은 지정된 문자 또는 다른 문자로 둘러싸고 구분 문자로 구분합니다

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Enclose(char16_t beginningCharacter, char16_t endingCharacter, char16_t separatorCharacter) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| beginningCharacter | char16_t | 시작 문자(보통 왼쪽 대괄호) |
| endingCharacter | char16_t | 끝 문자(보통 오른쪽 대괄호) |
| separatorCharacter | char16_t | 구분 문자 |

### 반환값

프레임과 구분 문자로 지정된 문자를 포함하는 형식 [IMathDelimiter](../../imathdelimiter/)의 수학 요소
## 비고

예제:
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Enclose(u'{', u'}', u'%');
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathDelimiter](../../imathdelimiter/)
* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)