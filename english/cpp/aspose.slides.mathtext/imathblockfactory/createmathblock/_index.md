---
title: CreateMathBlock()
second_title: Aspose.Slides for C++ API Reference
description: Create a math block
type: docs
weight: 1
url: /cpp/aspose.slides.mathtext/imathblockfactory/createmathblock/
---
## IMathBlockFactory::CreateMathBlock() method


Create a math block

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock()=0
```


### Return Value

new math block

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElement\>) method


Create a math block and place the element in it

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElement> mathElement)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | A math element |

### Return Value

new math block

## IMathBlockFactory::CreateMathBlock(System::SharedPtr\<IMathElementCollection\>) method


Create a math block and place elements in it

```cpp
virtual System::SharedPtr<IMathBlock> Aspose::Slides::MathText::IMathBlockFactory::CreateMathBlock(System::SharedPtr<IMathElementCollection> mathElements)=0
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
* Class [IMathBlockFactory](../)
* Class [IMathElement](../../imathelement/)
* Class [IMathElementCollection](../../imathelementcollection/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)