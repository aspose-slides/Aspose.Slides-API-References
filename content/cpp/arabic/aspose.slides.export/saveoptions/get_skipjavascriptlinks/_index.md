---
title: get_SkipJavaScriptLinks()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحدد ما إذا كان سيُتخطى الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة bool. القيمة الافتراضية هي false.
type: docs
weight: 105
url: /ar/aspose.slides.export/saveoptions/get_skipjavascriptlinks/
---
## SaveOptions::get_SkipJavaScriptLinks() طريقة

يحدد ما إذا كان سيُتخطى الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. قراءة **bool**. القيمة الافتراضية هي **false**.

```cpp
bool Aspose::Slides::Export::SaveOptions::get_SkipJavaScriptLinks() override
```

## ملاحظات

عندما تكون هذه الخاصية مُعينة إلى **true**, سيتم تجاهل الروابط التشعبية التي تحتوي على استدعاءات JavaScript أثناء الحفظ.

عندما تكون هذه الخاصية مُعينة إلى **false**, سيتم حفظ جميع الروابط التشعبية.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## انظر أيضا

* الفئة [SaveOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)