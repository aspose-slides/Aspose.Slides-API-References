---
title: AddFromPdf()
second_title: Aspose.Slides för C++ API-referens
description: Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.
type: docs
weight: 131
url: /sv/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) metod

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | En sökväg till PDF-dokumentet |

### Returvärde

Tillagda bilder
## Anmärkningar



Exempel: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) metod

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen med beaktande av pdf-importalternativen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | En sökväg till PDF-dokumentet |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Alternativ för pdf-import |

### Returvärde

Tillagda bilder
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) metod

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En ström som kommer att användas som källa för PDF-dokumentet |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Alternativ för pdf-import |

### Returvärde

Tillagda bilder
## Anmärkningar



Exempel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// sätt detektering av tabeller
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) metod

Skapar bilder från PDF-dokumentet och lägger till dem i slutet av samlingen.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | En ström som kommer att användas som källa för PDF-dokumentet |

### Returvärde

Tillagda bilder
## Anmärkningar



Exempel: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [String](../../../system/string/)
* Klass [ISlideCollection](../)
* Klass [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Klass [Stream](../../../system.io/stream/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)