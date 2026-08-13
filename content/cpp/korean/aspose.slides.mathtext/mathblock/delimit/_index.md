---
title: Delimit()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 구분자 문자로 자식 요소를 구분합니다 (대괄호 제외)
type: docs
weight: 209
url: /ko/aspose.slides.mathtext/mathblock/delimit/
---
## MathBlock::Delimit(char16_t) 메서드


구분자 문자로 자식 요소를 구분합니다 (대괄호 제외)

```cpp
System::SharedPtr<IMathDelimiter> Aspose::Slides::MathText::MathBlock::Delimit(char16_t separatorCharacter) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| separatorCharacter | char16_t | 구분자 문자 |

### 반환값

형식 [IMathDelimiter](../../imathdelimiter/)의 수학 요소

## 비고



예: 
```cpp
auto mathBlock = System::MakeObject<MathematicalText>(u"x")->Join(u"y");
auto delimiterElement = mathBlock->Delimit(u'|');
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathDelimiter](../../imathdelimiter/)
* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)