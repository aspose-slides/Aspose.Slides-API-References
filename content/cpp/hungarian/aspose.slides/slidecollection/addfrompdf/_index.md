---
title: AddFromPdf()
second_title: Aspose.Slides C++ API referencia
description: Diákat hoz létre a PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez.
type: docs
weight: 183
url: /hu/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) metódus

Diákat hoz létre a PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | A PDF-dokumentum elérési útja |

### Visszatérési érték

Hozzáadott diák
## Megjegyzések

Példa: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) metódus

Diákat hoz létre a PDF-dokumentumból, és a pdf import beállítások figyelembevételével hozzáadja őket a gyűjtemény végéhez.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | A PDF-dokumentum elérési útja |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | A pdf import beállításai |

### Visszatérési érték

Hozzáadott diák
## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) metódus

Diákat hoz létre a PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Egy adatfolyam, amely a PDF-dokumentum forrásaként szolgál |

### Visszatérési érték

Hozzáadott diák
## Megjegyzések

Példa: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) metódus

Diákat hoz létre a PDF-dokumentumból, és hozzáadja őket a gyűjtemény végéhez.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Egy adatfolyam, amely a PDF-dokumentum forrásaként szolgál |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | A pdf import beállításai |

### Visszatérési érték

Hozzáadott diák
## Megjegyzések

Példa: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// állítsa be a táblák észlelését
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [String](../../../system/string/)
* Osztály [SlideCollection](../)
* Osztály [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Osztály [Stream](../../../system.io/stream/)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)