---
title: get_IncludeOleData()
second_title: Aspose.Slides لـ C++ مرجع API
description: صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في ملف PDF الناتج. قراءة bool.
type: docs
weight: 456
url: /ar/aspose.slides.export/ipdfoptions/get_includeoledata/
---
## IPdfOptions::get_IncludeOleData() طريقة


صحيح لتحويل جميع بيانات OLE من العرض إلى ملفات مدمجة في ملف PDF الناتج. قراءة **bool**.

```cpp
virtual bool Aspose::Slides::Export::IPdfOptions::get_IncludeOleData()=0
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

* فئة [IPdfOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)