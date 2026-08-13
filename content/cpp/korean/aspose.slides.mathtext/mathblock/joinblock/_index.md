---
title: JoinBlock()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 다른 수학 블록을 이 블록과 결합합니다
type: docs
weight: 196
url: /ko/aspose.slides.mathtext/mathblock/joinblock/
---
## MathBlock::JoinBlock(System::SharedPtr\<IMathBlock\>) 메서드


다른 수학 블록을 이 블록과 결합합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlock::JoinBlock(System::SharedPtr<IMathBlock> other) override
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| other | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 결합 블록 |

### 반환값

결합 후 이 수학 블록

## 비고



예: 
```cpp
auto block1 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"c"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"="));
auto block2 = System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"a"), System::MakeObject<MathematicalText>(u"2"))->Join(System::MakeObject<MathematicalText>(u"+"))->Join(System::MakeObject<MathSuperscriptElement>(System::MakeObject<MathematicalText>(u"b"), System::MakeObject<MathematicalText>(u"2")));
auto block3 = block1->JoinBlock(block2);
```

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [MathBlock](../)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)