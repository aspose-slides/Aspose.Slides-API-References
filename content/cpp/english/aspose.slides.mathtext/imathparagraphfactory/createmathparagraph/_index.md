---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API Reference
description: Create empty math paragraph
type: docs
weight: 1
url: /aspose.slides.mathtext/imathparagraphfactory/createmathparagraph/
---
## IMathParagraphFactory::CreateMathParagraph() method


Create empty math paragraph

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph()=0
```


### Return Value

new math paragraph

## IMathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) method


Creates a math paragraph and places the specified math block in it

```cpp
virtual System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::IMathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | math block to place in the paragraph |

### Return Value

new math paragraph

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathParagraph](../../imathparagraph/)
* Class [IMathParagraphFactory](../)
* Class [IMathBlock](../../imathblock/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)