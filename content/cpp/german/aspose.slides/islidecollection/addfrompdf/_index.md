---
title: AddFromPdf()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu.
type: docs
weight: 131
url: /de/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) Methode

Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Ein Pfad zum PDF-Dokument |

### Rückgabewert

Hinzugefügte Folien
## Bemerkungen



Beispiel: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) Methode


Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung unter Berücksichtigung der PDF-Importoptionen hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Ein Pfad zum PDF-Dokument |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Optionen für den PDF-Import |

### Rückgabewert

Hinzugefügte Folien
## Bemerkungen



Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) Methode


Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream, der als Quelle des PDF-Dokuments verwendet wird |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Optionen für den PDF-Import |

### Rückgabewert

Hinzugefügte Folien
## Bemerkungen



Beispiel: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// Tabellenerkennung aktivieren
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) Methode


Erstellt Folien aus dem PDF-Dokument und fügt sie am Ende der Sammlung hinzu.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Ein Stream, der als Quelle des PDF-Dokuments verwendet wird |

### Rückgabewert

Hinzugefügte Folien
## Bemerkungen



Beispiel: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [String](../../../system/string/)
* Klasse [ISlideCollection](../)
* Klasse [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Klasse [Stream](../../../system.io/stream/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)