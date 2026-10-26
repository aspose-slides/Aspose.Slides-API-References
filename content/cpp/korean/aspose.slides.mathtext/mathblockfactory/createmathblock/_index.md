---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 블록을 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() 메서드


수학 블록을 생성합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```


### 반환값

새 수학 블록

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) 메서드


수학 블록을 생성하고 요소를 그 안에 배치합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 수학 요소 |

### 반환값

새 수학 블록

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) 메서드


수학 블록을 생성하고 요소들을 그 안에 배치합니다

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 수학 요소들 |

### 반환값

새 수학 블록

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [MathBlockFactory](../)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathElementCollection](../../imathelementcollection/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)