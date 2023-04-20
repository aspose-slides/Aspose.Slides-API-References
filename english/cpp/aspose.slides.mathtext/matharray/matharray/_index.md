---
title: MathArray()
second_title: Aspose.Slides for C++ API Reference
description: Creates a mathematical array and places the specified element in it
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/matharray/matharray/
---
## MathArray::MathArray(System::SharedPtr\<IMathElement\>) constructor


Creates a mathematical array and places the specified element in it

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The element to place in the array |
## Remarks



Example: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
```

## MathArray::MathArray(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) constructor


Creates a mathematical array and places specified elements in it

```cpp
Aspose::Slides::MathText::MathArray::MathArray(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> elements)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| elements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Elements to place in the array |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathArray](../)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)