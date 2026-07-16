---
title: AddFromPdf()
second_title: Référence API Aspose.Slides pour C++
description: Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection.
type: docs
weight: 131
url: /fr/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) méthode

Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Un chemin vers le document PDF |

### Valeur de retour

Diapositives ajoutées
## Remarques



Exemple : 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) méthode

Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection en tenant compte des options d'importation PDF.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Un chemin vers le document PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Options pour l'importation PDF |

### Valeur de retour

Diapositives ajoutées
## Remarques



Exemple : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) méthode

Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux qui sera utilisé comme source du document PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Options pour l'importation PDF |

### Valeur de retour

Diapositives ajoutées
## Remarques



Exemple : 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// définir la détection des tables
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) méthode

Crée des diapositives à partir du document PDF et les ajoute à la fin de la collection.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flux qui sera utilisé comme source du document PDF |

### Valeur de retour

Diapositives ajoutées
## Remarques



Exemple : 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [String](../../../system/string/)
* Classe [ISlideCollection](../)
* Classe [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Classe [Stream](../../../system.io/stream/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)