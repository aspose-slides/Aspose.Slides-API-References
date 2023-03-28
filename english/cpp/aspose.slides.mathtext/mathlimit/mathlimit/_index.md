---
title: MathLimit()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of the MathLimit class.
type: docs
weight: 53
url: /cpp/aspose.slides.mathtext/mathlimit/mathlimit/
---
## MathLimit::MathLimit([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, **bool**) constructor


Initializes a new instance of the [MathLimit](../) class.

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit, bool upperLimit)
```

## Remarks


Example: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"), false);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
## MathLimit::MathLimit([System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>, [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\>) constructor


Initializes a new instance of the [MathLimit](../) class with lower limit

```cpp
Aspose::Slides::MathText::MathLimit::MathLimit(System::SharedPtr<IMathElement> baseArg, System::SharedPtr<IMathElement> limit)
```

## Remarks


Example: 
```cpp
auto limitElement = System::MakeObject<MathLimit>(System::MakeObject<MathematicalText>(u"lim"), System::MakeObject<MathematicalText>(u"\U0001d45b→∞"));
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathLimit](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
