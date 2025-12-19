---
title: MathBlock()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathBlock class.
type: docs
weight: 66
url: /aspose.slides.mathtext/mathblock/mathblock/
---
## MathBlock::MathBlock() constructor


Initializes a new instance of the [MathBlock](../) class.

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock()
```

## Remarks


Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>();
```

## MathBlock::MathBlock(System::SharedPtr\<IMathElement\>) constructor


Creates a new mathematical block and puts specified element in it

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<IMathElement> mathElement)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The mathematical element to put in the block |
## Remarks



Example: 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBlock::MathBlock(System::SharedPtr\<System::Collections::Generic::IEnumerable\<System::SharedPtr\<IMathElement\>\>\>) constructor


Creates a new mathematical block and puts specified elements in it

```cpp
Aspose::Slides::MathText::MathBlock::MathBlock(System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<IMathElement>>> mathElements)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [System::SharedPtr](../../../system/sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>\>\> | Mathematical elements to put in the block |
## Remarks



Example: 
```cpp
auto elems = System::MakeArray<System::SharedPtr<IMathElement>>({System::MakeObject<MathematicalText>(u"item1"), System::MakeObject<MathematicalText>(u"item2")});
auto mathBlock = System::MakeObject<MathBlock>(elems);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MathBlock](../)
* Class [IMathElement](../../imathelement/)
* Class [IEnumerable](../../../system.collections.generic/ienumerable/)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)