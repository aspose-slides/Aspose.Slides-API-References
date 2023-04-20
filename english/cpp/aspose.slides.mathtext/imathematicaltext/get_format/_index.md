---
title: get_Format()
second_title: Aspose.Slides for C++ API Reference
description: Text formatting properties
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() method


Text formatting properties

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## Remarks


Example: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPortionFormat](../../../aspose.slides/iportionformat/)
* Class [IMathematicalText](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)