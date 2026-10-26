---
title: ToTiff()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la presentación de entrada en un conjunto de imágenes en formato TIFF. Si el nombre del archivo de salida se proporciona como \"myPath/myFilename.tiff\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.tiff\", donde N es el número de la diapositiva.
type: docs
weight: 66
url: /es/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) método


Convierte la presentación de entrada en un conjunto de imágenes en formato TIFF. 

 Si el nombre del archivo de salida se proporciona como \"myPath/myFilename.tiff\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.tiff\", donde N es el número de la diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre del archivo de salida. |
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) método


Convierte la presentación de entrada a formato TIFF con opciones personalizadas. Si el nombre del archivo de salida se proporciona como \"myPath/myFilename.tiff\" y *multipage* es **false**, el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.tiff\", donde N es el número de la diapositiva. De lo contrario, si *multipage* es **true**, el resultado será un documento multipágina \"myPath/myFilename.tiff\".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre del archivo de salida. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Las opciones de guardado TIFF. |
| multipage | **bool** | Especifica si el documento TIFF generado debe ser multipágina. |
## Observaciones




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)