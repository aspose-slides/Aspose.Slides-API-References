---
title: set_SpellCheck()
second_title: Aspose.Slides for C++ API Reference
description: Sets a value indicating whether spell checking is enabled for the text portion. When this property is set to false, spelling checks for text elements are suppressed. When set to true, spell checking is allowed. Default value is false.
type: docs
weight: 612
url: /aspose.slides/baseportionformat/set_spellcheck/
---
## BasePortionFormat::set_SpellCheck(bool) method


Sets a value indicating whether spell checking is enabled for the text portion. When this property is set to false, spelling checks for text elements are suppressed. When set to true, spell checking is allowed. Default value is **false**.

```cpp
void Aspose::Slides::BasePortionFormat::set_SpellCheck(bool value) override
```

## Remarks


Next example demonstrates enabling the SpellCheck flag before saving the presentation: 
```cpp
auto pres = System::MakeObject<Presentation>(u"input.pptx");
// Access the first portion of text inside the first shape on the first slide
auto portion = (System::ExplicitCast<AutoShape>(pres->get_Slide(0)->get_Shape(0)))->get_TextFrame()->get_Paragraph(0)->get_Portion(0);
// Enable spell checking for this text portion
portion->get_PortionFormat()->set_SpellCheck(true);
// Save the modified presentation
pres->Save(u"output-with-spellcheck.pptx", SaveFormat::Pptx);
```

## See Also

* Class [BasePortionFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)