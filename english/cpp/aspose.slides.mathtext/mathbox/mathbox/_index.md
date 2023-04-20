---
title: MathBox()
second_title: Aspose.Slides for C++ API Reference
description: Initializes MathBox with the specified element as an argument
type: docs
weight: 144
url: /cpp/aspose.slides.mathtext/mathbox/mathbox/
---
## MathBox::MathBox(System::SharedPtr\<IMathElement\>) constructor


Initializes [MathBox](../) with the specified element as an argument

```cpp
Aspose::Slides::MathText::MathBox::MathBox(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The base element to which the box is applied. Can be null. |
## Remarks



Example: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)