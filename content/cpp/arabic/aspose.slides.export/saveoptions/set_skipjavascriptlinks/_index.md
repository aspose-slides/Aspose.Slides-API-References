---
title: set_SkipJavaScriptLinks()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides لـ C++
description: يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. اكتب bool. القيمة الافتراضية هي false.
type: docs
weight: 118
url: /ar/aspose.slides.export/saveoptions/set_skipjavascriptlinks/
---
## SaveOptions::set_SkipJavaScriptLinks(bool) طريقة

يحدد ما إذا كان يجب تخطي الروابط التشعبية التي تحتوي على استدعاءات JavaScript عند حفظ العرض التقديمي. اكتب **bool**. القيمة الافتراضية هي **false**.

```cpp
void Aspose::Slides::Export::SaveOptions::set_SkipJavaScriptLinks(bool value) override
```

## ملاحظات

عند ضبط هذه الخاصية إلى **true**، سيتم تجاهل الروابط التشعبية التي تحتوي على استدعاءات JavaScript أثناء الحفظ.

عند ضبط هذه الخاصية إلى **false**، سيتم حفظ جميع الروابط التشعبية.

مثال:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"demo.pptx");

System::SharedPtr<HtmlOptions> options = System::MakeObject<HtmlOptions>();
options->set_SkipJavaScriptLinks(true);

pres->Save(u"result_without_JavaScript_links.html", SaveFormat::Html, options);
```

## انظر أيضًا

* فئة [SaveOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)