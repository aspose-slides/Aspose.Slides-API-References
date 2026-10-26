---
title: set_IncludeOleData()
second_title: مرجع API Aspose.Slides للـ C++
description: صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمّنة في ملف PDF الناتج. اكتب bool.
type: docs
weight: 469
url: /ar/aspose.slides.export/pdfoptions/set_includeoledata/
---
## PdfOptions::set_IncludeOleData(bool) طريقة


صحيح لتحويل جميع بيانات OLE من العرض التقديمي إلى ملفات مضمّنة في ملف PDF الناتج. اكتب **bool**.

```cpp
void Aspose::Slides::Export::PdfOptions::set_IncludeOleData(bool value) override
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

* فئة [PdfOptions](../)
* نطاق [Aspose::Slides::Export](../../)
* مكتبة [Aspose.Slides](../../../)