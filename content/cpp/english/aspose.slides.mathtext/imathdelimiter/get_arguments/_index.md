---
title: get_Arguments()
second_title: Aspose.Slides for C++ API Reference
description: One or more mathematical elements separated by delimiter characters
type: docs
weight: 1
url: /aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() method


One or more mathematical elements separated by delimiter characters

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Remarks


Example: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElementCollection](../../imathelementcollection/)
* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)