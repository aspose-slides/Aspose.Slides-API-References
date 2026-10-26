---
title: set_SkipJavaScriptLinks()
second_title: مرجع API Aspose.Slides للغة C++
description: يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات جافا سكريبت عند حفظ العرض التقديمي. اكتب bool. القيمة الافتراضية هي false.
type: docs
weight: 118
url: /ar/aspose.slides.export/isaveoptions/set_skipjavascriptlinks/
---
## ISaveOptions::set_SkipJavaScriptLinks(bool) طريقة

يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات جافا سكريبت عند حفظ العرض التقديمي. اكتب **bool**. القيمة الافتراضية هي **false**.

```cpp
virtual void Aspose::Slides::Export::ISaveOptions::set_SkipJavaScriptLinks(bool value)=0
```

## ملاحظات

عند ضبط هذه الخاصية إلى **true**، سيتم تجاهل الروابط التشعبية ذات استدعاءات جافا سكريبت أثناء الحفظ.

عند ضبط هذه الخاصية إلى **false**، سيتم حفظ جميع الروابط التشعبية.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## انظر أيضًا

* الفئة [ISaveOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)