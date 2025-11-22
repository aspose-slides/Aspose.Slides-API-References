---
title: MathPhantom()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathPhantom class using the specified base math element.
type: docs
weight: 144
url: /aspose.slides.mathtext/mathphantom/mathphantom/
---
## MathPhantom::MathPhantom(System::SharedPtr\<IMathElement\>) constructor


Initializes a new instance of the [MathPhantom](../) class using the specified base math element.

```cpp
Aspose::Slides::MathText::MathPhantom::MathPhantom(System::SharedPtr<IMathElement> element)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | The base [IMathElement](../../imathelement/) whose visibility and layout will be controlled by the phantom. This element defines the content that may be hidden or shown, while still affecting the geometric alignment of the surrounding math. |
## Remarks



The phantom element is used to reserve or suppress the visual space of its base expression without necessarily displaying it. It corresponds to the OMML element **<m:phant>**. 

Example: 
```cpp
System::SharedPtr<IMathElement> fraction = System::MakeObject<MathFraction>(
    System::MakeObject<MathematicalText>(u"1"),
    System::MakeObject<MathematicalText>(u"2"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathPhantom](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)