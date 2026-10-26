---
title: AddFromPdf()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.
type: docs
weight: 183
url: /pl/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) metoda

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Ścieżka do dokumentu PDF |

### Wartość zwracana

Dodane slajdy
## Uwagi



Przykład: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) metoda

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji, uwzględniając opcje importu PDF.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Ścieżka do dokumentu PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opcje importu PDF |

### Wartość zwracana

Dodane slajdy
## Uwagi



Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) metoda

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, który będzie używany jako źródło dokumentu PDF |

### Wartość zwracana

Dodane slajdy
## Uwagi



Przykład: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) metoda

Tworzy slajdy z dokumentu PDF i dodaje je na koniec kolekcji.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Strumień, który będzie używany jako źródło dokumentu PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opcje importu PDF |

### Wartość zwracana

Dodane slajdy
## Uwagi



Przykład: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// ustaw wykrywanie tabel
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ISlide](../../islide/)
* Klasa [String](../../../system/string/)
* Klasa [SlideCollection](../)
* Klasa [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Klasa [Stream](../../../system.io/stream/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)