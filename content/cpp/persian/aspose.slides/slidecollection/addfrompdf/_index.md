---
title: AddFromPdf()
second_title: Aspose.Slides برای C++ مرجع API
description: اسلایدها را از سند PDF ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.
type: docs
weight: 183
url: /fa/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) متد

اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | مسیر به سند PDF |

### مقدار بازگشت

Added slides

## توضیحات



مثال: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) متد

اسلایدها را از سند PDF ایجاد کرده و با در نظر گرفتن گزینه‌های واردات PDF، به انتهای مجموعه اضافه می‌کند.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | مسیر به سند PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | گزینه‌های واردات PDF |

### مقدار بازگشت

Added slides

## توضیحات



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) متد

اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که به عنوان منبع سند PDF استفاده می‌شود |

### مقدار بازگشت

Added slides

## توضیحات



مثال: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) متد

اسلایدها را از سند PDF ایجاد کرده و به انتهای مجموعه اضافه می‌کند.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریانی که به عنوان منبع سند PDF استفاده می‌شود |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | گزینه‌های واردات PDF |

### مقدار بازگشت

Added slides

## توضیحات



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

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISlide](../../islide/)
* کلاس [String](../../../system/string/)
* کلاس [SlideCollection](../)
* کلاس [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* کلاس [Stream](../../../system.io/stream/)
* فضای نام [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)