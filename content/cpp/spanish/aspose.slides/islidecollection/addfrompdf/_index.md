---
title: AddFromPdf()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea diapositivas a partir del documento PDF y las agrega al final de la colección.
type: docs
weight: 131
url: /es/aspose.slides/islidecollection/addfrompdf/
---
## ISlideCollection::AddFromPdf(System::String) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Una ruta al documento PDF |

### Valor devuelto

Diapositivas añadidas

## Observaciones



Ejemplo: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección considerando las opciones de importación de PDF.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Una ruta al documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opciones para la importación de PDF |

### Valor devuelto

Diapositivas añadidas

## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Una secuencia que se usará como origen del documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opciones para la importación de PDF |

### Valor devuelto

Diapositivas añadidas

## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<Stream> stream = System::MakeObject<FileStream>(u"document.pdf", System::IO::FileMode::Open, System::IO::FileAccess::Read, System::IO::FileShare::Read);

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

// establecer detección de tablas
pres->get_Slides()->AddFromPdf(stream, options);

pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## ISlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Una secuencia que se usará como origen del documento PDF |

### Valor devuelto

Diapositivas añadidas

## Observaciones



Ejemplo: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```




## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [String](../../../system/string/)
* Clase [ISlideCollection](../)
* Clase [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)