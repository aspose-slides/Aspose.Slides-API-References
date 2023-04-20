---
title: MathRadical()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathRadical class.
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathradical/mathradical/
---
## MathRadical::MathRadical(System::SharedPtr\<IMathElement\>, System::SharedPtr\<IMathElement\>) constructor


Initializes a new instance of the [MathRadical](../) class.

```cpp
Aspose::Slides::MathText::MathRadical::MathRadical(System::SharedPtr<IMathElement> baseArgument, System::SharedPtr<IMathElement> degreeArgument)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| baseArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Base |
| degreeArgument | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | Degree |
## Remarks



Example: 
```cpp
auto radical = System::MakeObject<MathRadical>(System::MakeObject<MathematicalText>(u"x"), System::MakeObject<MathematicalText>(u"3"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathRadical](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)