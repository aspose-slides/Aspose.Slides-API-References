---
title: CreateMathParagraph()
second_title: C++용 Aspose.Slides API 참조
description: 빈 수학 단락을 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/mathparagraphfactory/createmathparagraph/
---
## MathParagraphFactory::CreateMathParagraph() 메서드

빈 수학 단락을 생성합니다

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph() override
```

### 반환 값

새 수학 단락

## MathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) 메서드

수학 단락을 만들고 지정된 수학 블록을 그 안에 배치합니다

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 단락에 배치할 수학 블록 |

### 반환 값

새 수학 단락

## 또 보기

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathParagraph](../../imathparagraph/)
* 클래스 [MathParagraphFactory](../)
* 클래스 [IMathBlock](../../imathblock/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)