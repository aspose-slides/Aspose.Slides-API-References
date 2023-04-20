---
title: CreateMathParagraph()
second_title: Aspose.Slides for C++ API Reference
description: Create empty math paragraph
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/mathparagraphfactory/createmathparagraph/
---
## MathParagraphFactory::CreateMathParagraph() method


Create empty math paragraph

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph() override
```


### Return Value

new math paragraph

## MathParagraphFactory::CreateMathParagraph(System::SharedPtr\<IMathBlock\>) method


Creates a math paragraph and places the specified math block in it

```cpp
System::SharedPtr<IMathParagraph> Aspose::Slides::MathText::MathParagraphFactory::CreateMathParagraph(System::SharedPtr<IMathBlock> mathBlock) override
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
* Class [MathParagraphFactory](../)
* Class [IMathBlock](../../imathblock/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)