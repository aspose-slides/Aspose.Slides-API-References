---
title: AddFromPdf()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea diapositive dal documento PDF e le aggiunge alla fine della collezione.
type: docs
weight: 183
url: /it/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) metodo


Crea le diapositive dal documento PDF e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Un percorso al documento PDF |

### Valore di ritorno

Diapositive aggiunte
## Note



Esempio: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) metodo


Crea le diapositive dal documento PDF e le aggiunge alla fine della collezione tenendo conto delle opzioni di importazione PDF.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Un percorso al documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opzioni per l'importazione PDF |

### Valore di ritorno

Diapositive aggiunte
## Note



Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) metodo


Crea le diapositive dal documento PDF e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uno stream che verrà utilizzato come sorgente del documento PDF |

### Valore di ritorno

Diapositive aggiunte
## Note



Esempio: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) metodo


Crea le diapositive dal documento PDF e le aggiunge alla fine della collezione.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Uno stream che verrà utilizzato come sorgente del documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opzioni per l'importazione PDF |

### Valore di ritorno

Diapositive aggiunte
## Note



Esempio: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// imposta il rilevamento delle tabelle
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [SlideCollection](../)
* Classe [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Classe [Stream](../../../system.io/stream/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)