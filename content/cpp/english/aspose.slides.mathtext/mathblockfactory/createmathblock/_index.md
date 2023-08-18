---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API Reference
description: Create a math block
type: docs
weight: 1
url: /aspose.slides.mathtext/mathblockfactory/createmathblock/
---
## MathBlockFactory::CreateMathBlock() method


Create a math block

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock() override
```


### Return Value

new math block

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) method


Create a math block and place the element in it

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A math element |

### Return Value

new math block

## MathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) method


Create a math block and place elements in it

```cpp
System::SharedPtr<IMathBlock> Aspose::Slides::MathText::MathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElementCollection](../../imathelementcollection/)\> | math elements |

### Return Value

new math block

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [MathBlockFactory](../)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)