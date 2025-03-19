---
title: set_SkipJavaScriptLinks()
second_title: Aspose.Slides for C++ API Reference
description: Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Write bool. The default value is false.
type: docs
weight: 118
url: /aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) method


Specifies whether to skip hyperlinks with JavaScript calls when saving the presentation. Write **bool**. The default value is **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## Remarks


When this property is set to **true**, hyperlinks with JavaScript calls will be ignored while saving.

When this property is set to **false**, all hyperlinks will be saved.

Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## See Also

* Class [SaveOptions](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)