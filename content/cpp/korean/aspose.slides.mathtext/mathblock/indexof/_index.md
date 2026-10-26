---
title: IndexOf()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 특정 수학 요소의 인덱스를 결정합니다.
type: docs
weight: 144
url: /ko/aspose.slides.mathtext/mathblock/indexof/
---
## MathBlock::IndexOf(System::SharedPtr\<IMathElement\>) method

특정 수학 요소의 인덱스를 컬렉션에서 결정합니다.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::IndexOf(System::SharedPtr<IMathElement> item) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 컬렉션에서 찾을 요소입니다. |

### 반환값

컬렉션에서 *item*이(가) 발견되면 해당 인덱스를 반환하고, 그렇지 않으면 -1을 반환합니다.
## 비고



예시: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto plusElement = System::MakeObject<MathematicalText>(u"+");
mathBlock->Add(plusElement);
mathBlock->Add(System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3")));
int32_t index = mathBlock->IndexOf(plusElement);
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)