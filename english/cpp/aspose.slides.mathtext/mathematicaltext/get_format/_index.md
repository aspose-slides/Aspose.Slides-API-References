---
title: get_Format()
second_title: Aspose.Slides for C++ API Reference
description: Text formatting properties
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() method


Text formatting properties

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
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
* Class [MathematicalText](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)
