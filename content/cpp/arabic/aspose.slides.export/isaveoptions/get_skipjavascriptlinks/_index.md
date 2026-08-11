---
title: get_SkipJavaScriptLinks()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحدد ما إذا كان يجب تخطي الروابط الفائقة التي تستدعي جافا سكريبت عند حفظ العرض التقديمي. القراءة bool. القيمة الافتراضية هي false.
type: docs
weight: 105
url: /ar/aspose.slides.export/isaveoptions/get_skipjavascriptlinks/
---
## ISaveOptions::get_SkipJavaScriptLinks() طريقة

يحدد ما إذا كان يجب تخطي الروابط الفائقة التي تستدعي جافا سكريبت عند حفظ العرض التقديمي. القراءة **bool**. القيمة الافتراضية هي **false**.

```cpp
virtual bool Aspose::Slides::Export::ISaveOptions::get_SkipJavaScriptLinks()=0
```

## ملاحظات

عند تعيين هذه الخاصية إلى **true**، سيتم تجاهل الروابط الفائقة التي تستدعي جافا سكريبت أثناء الحفظ.

عند تعيين هذه الخاصية إلى **false**، سيتم حفظ جميع الروابط الفائقة.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## انظر أيضًا

* الفئة [ISaveOptions](../)
* المجال [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)