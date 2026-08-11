---
title: set_IncludeOleData()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في ملف PDF الناتج. اكتب **bool**.
type: docs
weight: 469
url: /ar/aspose.slides.export/ipdfoptions/set_includeoledata/
---
## IPdfOptions::set_IncludeOleData(bool) طريقة


True لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في ملف PDF الناتج. اكتب **bool**.

```cpp
virtual void Aspose::Slides::Export::IPdfOptions::set_IncludeOleData(bool value)=0
```

## ملاحظات


القيمة الافتراضية هي **false**. 

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<PdfOptions> options = System::MakeObject<PdfOptions>();
options->set_IncludeOleData(true);
pres->Save(u"pres.pdf", SaveFormat::Pdf, options);
```

## انظر أيضًا

* الفئة [IPdfOptions](../)
* النطاق [Aspose::Slides::Export](../../)
* المكتبة [Aspose.Slides](../../../)