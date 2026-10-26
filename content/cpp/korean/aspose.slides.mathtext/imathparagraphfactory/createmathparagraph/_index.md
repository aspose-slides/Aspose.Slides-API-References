---
title: CreateMathParagraph()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 빈 수학 단락을 생성합니다
type: docs
weight: 1
url: /ko/aspose.slides.mathtext/imathparagraphfactory/createmathparagraph/
---
## IMathParagraphFactory::CreateMathParagraph() 메서드

빈 수학 단락을 생성합니다

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph()=0
```


### 반환 값

새로운 수학 단락

## IMathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) 메서드

수학 단락을 만들고 지정된 수학 블록을 그 안에 배치합니다

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock)=0
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 단락에 넣을 수학 블록 |

### 반환 값

새로운 수학 단락

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IMathParagraph](../../imathparagraph/)
* 클래스 [IMathParagraphFactory](../)
* 클래스 [IMathBlock](../../imathblock/)
* 네임스페이스 [Aspose::Slides::MathText](../../)
* 라이브러리 [Aspose.Slides](../../../)