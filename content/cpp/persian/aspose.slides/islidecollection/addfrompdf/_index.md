---
title: AddFromPdf()
second_title: مرجع API Aspose.Slides برای C++
description: اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.
type: docs
weight: 131
url: /fa/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) متد

اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | مسیر به سند PDF |

### مقدار برگشتی

اسلایدهای اضافه‌شده
## یادداشت‌ها



مثال: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) متد


اسلایدها را از سند PDF ایجاد می‌کند و با توجه به گزینه‌های واردات PDF به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | مسیر به سند PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | گزینه‌های واردات PDF |

### مقدار برگشتی

اسلایدهای اضافه‌شده
## یادداشت‌ها



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) متد


اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که به‌عنوان منبع سند PDF استفاده می‌شود |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | گزینه‌های واردات PDF |

### مقدار برگشتی

اسلایدهای اضافه‌شده
## یادداشت‌ها



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// تنظیم تشخیص جداول
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) متد


اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```


### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که به‌عنوان منبع سند PDF استفاده می‌شود |

### مقدار برگشتی

اسلایدهای اضافه‌شده
## یادداشت‌ها



مثال: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [String](../../../system/string/)
* کلاس [ISlideCollection](../)
* کلاس [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* کلاس [Stream](../../../system.io/stream/)
* فضای‌نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)