---
title: AddFromPdf()
second_title: Aspose.Slides for C++ API Referansı
description: PDF belgesinden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.
type: docs
weight: 183
url: /tr/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) metot


PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF belgesine bir yol |

### Dönüş Değeri

Eklenen slaytlar
## Açıklamalar



Örnek: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) metot


PDF belgesinden slaytlar oluşturur ve PDF içe aktarma seçeneklerini dikkate alarak koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | PDF belgesine bir yol |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF içe aktarma seçenekleri |

### Dönüş Değeri

Eklenen slaytlar
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) metot


PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF belgesinin kaynağı olarak kullanılacak bir akış |

### Dönüş Değeri

Eklenen slaytlar
## Açıklamalar



Örnek: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) metot


PDF belgesinden slaytlar oluşturur ve koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | PDF belgesinin kaynağı olarak kullanılacak bir akış |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | PDF içe aktarma seçenekleri |

### Dönüş Değeri

Eklenen slaytlar
## Açıklamalar



Örnek: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// tabloları algılamayı ayarla
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [SlideCollection](../)
* Class [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)