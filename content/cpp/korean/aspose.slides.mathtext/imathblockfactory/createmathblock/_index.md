---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 수학 블록을 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() 메서드

수학 블록을 생성합니다

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```

### 반환 값

새 수학 블록

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) 메서드

수학 블록을 생성하고 그 안에 요소를 배치합니다

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | 수학 요소 |

### 반환 값

새 수학 블록

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) 메서드

수학 블록을 생성하고 요소들을 그 안에 배치합니다

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | 수학 요소 |

### 반환 값

새 수학 블록

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathBlock](../../imathblock/)
* 클래스 [IMathBlockFactory](../)
* 클래스 [IMathElement](../../imathelement/)
* 클래스 [IMathElementCollection](../../imathelementcollection/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)