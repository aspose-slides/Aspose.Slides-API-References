---
title: AddFromPdf()
second_title: Referencia de la API de Aspose.Slides para C++
description: Crea diapositivas a partir del documento PDF y las agrega al final de la colección.
type: docs
weight: 183
url: /es/aspose.slides/slidecollection/addfrompdf/
---
## SlideCollection::AddFromPdf(System::String) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Una ruta al documento PDF |

### Valor devuelto

Diapositivas agregadas
## Observaciones



Ejemplo: 
```cpp
auto pres = MakeObject<Presentation>();
pres->get_Slides()->AddFromPdf(u"document.pdf");
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::String, System::SharedPtr\<Import::PdfImportOptions\>) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección teniendo en cuenta las opciones de importación de PDF.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::String path, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| path | [System::String](../../../system/string/) | Una ruta al documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opciones para la importación de PDF |

### Valor devuelto

Diapositivas agregadas
## Observaciones



Ejemplo: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<PdfImportOptions> options = System::MakeObject<PdfImportOptions>();
options->set_DetectTables(true);

pres->get_Slides()->AddFromPdf(u"document.pdf", options);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo que se usará como origen del documento PDF |

### Valor devuelto

Diapositivas agregadas
## Observaciones



Ejemplo: 
```cpp
auto pres = MakeObject<Presentation>();
auto stream = MakeObject<IO::FileStream>(u"document.pdf", IO::FileMode::Open, IO::FileAccess::Read, IO::FileShare::Read);
pres->get_Slides()->AddFromPdf(stream);
pres->Save(u"fromPdfDocument.pptx", SaveFormat::Pptx);
```

## SlideCollection::AddFromPdf(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::PdfImportOptions\>) método

Crea diapositivas a partir del documento PDF y las agrega al final de la colección.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromPdf(System::SharedPtr<System::IO::Stream> pdfStream, System::SharedPtr<Import::PdfImportOptions> pdfImportOptions) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pdfStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Un flujo que se usará como origen del documento PDF |
| pdfImportOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Import::PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)\> | Opciones para la importación de PDF |

### Valor devuelto

Diapositivas agregadas
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

## Véase también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ISlide](../../islide/)
* Clase [String](../../../system/string/)
* Clase [SlideCollection](../)
* Clase [PdfImportOptions](../../../aspose.slides.import/pdfimportoptions/)
* Clase [Stream](../../../system.io/stream/)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)