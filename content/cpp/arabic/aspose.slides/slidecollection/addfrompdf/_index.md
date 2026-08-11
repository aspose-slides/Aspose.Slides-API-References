---
title: AddFromPdf()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.
type: docs
weight: 183
url: /ar/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) طريقة

ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | مسار إلى مستند PDF |

### قيمة الإرجاع

الشرائح المضافة
## ملاحظات



مثال: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) طريقة


ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد pdf.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | مسار إلى مستند PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | خيارات استيراد pdf |

### قيمة الإرجاع

الشرائح المضافة
## ملاحظات



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) طريقة


ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق سيُستخدم كمصدر لمستند PDF |

### قيمة الإرجاع

الشرائح المضافة
## ملاحظات



مثال: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) طريقة


ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | دفق سيُستخدم كمصدر لمستند PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | خيارات استيراد pdf |

### قيمة الإرجاع

الشرائح المضافة
## ملاحظات



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// تعيين كشف الجداول
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## انظر أيضاً

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [String](../../../system/string/)
* فئة [SlideCollection](../)
* فئة [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* فئة [Stream](../../../system.io/stream/)
* مساحة اسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)