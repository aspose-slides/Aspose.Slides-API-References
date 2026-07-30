---
title: AddFromPdf()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.
type: docs
weight: 183
url: /cs/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) metoda

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Cesta k PDF dokumentu |

### Návratová hodnota

Přidané snímky

## Poznámky

Příklad: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) metoda

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce s ohledem na možnosti importu PDF.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Cesta k PDF dokumentu |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Možnosti importu PDF |

### Návratová hodnota

Přidané snímky

## Poznámky

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) metoda

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud, který bude použit jako zdroj PDF dokumentu |

### Návratová hodnota

Přidané snímky

## Poznámky

Příklad: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) metoda

Vytvoří snímky z PDF dokumentu a přidá je na konec kolekce.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Proud, který bude použit jako zdroj PDF dokumentu |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Možnosti importu PDF |

### Návratová hodnota

Přidané snímky

## Poznámky

Příklad: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// nastavit detekci tabulek
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [String](../../../system/string/)
* Třída [SlideCollection](../)
* Třída [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Třída [Stream](../../../system.io/stream/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)