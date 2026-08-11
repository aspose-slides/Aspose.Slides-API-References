---
title: get_IncludeOleData()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مدمجة في ملف PDF الناتج. قراءة bool.
type: docs
weight: 456
url: /ar/aspose.slides.export/pdfoptions/get_includeoledata/
---
## PdfOptions::get_IncludeOleData() طريقة

صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مدمجة في ملف PDF الناتج. قراءة **bool**.

```cpp
bool Aspose::Slides::Export::PdfOptions::get_IncludeOleData() override
```

## ملاحظات

الافتراضي هو **false**. 

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## انظر أيضًا

* الفئة [PdfOptions](../)
* مساحة الاسم [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)