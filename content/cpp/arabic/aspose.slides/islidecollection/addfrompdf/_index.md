---
title: AddFromPdf()
second_title: مرجع API Aspose.Slides للـ C++
description: ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.
type: docs
weight: 131
url: /ar/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) طريقة


ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```


### المعلمات

| المعامل | النوع | الوصف |
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




## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) طريقة


ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة مع مراعاة خيارات استيراد PDF.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | مسار إلى مستند PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | خيارات استيراد PDF |

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




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) طريقة


ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق سيُستخدم كمصدر لمستند PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | خيارات استيراد PDF |

### قيمة الإرجاع

الشرائح المضافة
## ملاحظات



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// تعيين اكتشاف الجداول
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) طريقة


ينشئ شرائح من مستند PDF ويضيفها إلى نهاية المجموعة.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```


### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق سيُستخدم كمصدر لمستند PDF |

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




## راجع أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISlide](../../islide/)
* فئة [String](../../../system/string/)
* فئة [ISlideCollection](../)
* فئة [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* فئة [Stream](../../../system.io/stream/)
* فضاء الأسماء [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)