---
title: Convert
second_title: Referencia de API de Aspose.Slides for C++
description: Representa un grupo de métodos destinados a convertir Presentation.
type: docs
weight: 27
url: /es/aspose.slides.lowcode/convert/
---
## Convert clase

Representa un grupo de métodos destinados a convertir [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Métodos

| Método | Descripción |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Convierte [Presentation](../../aspose.slides/presentation/) usando la extensión de ruta de salida proporcionada para determinar el formato de exportación requerido. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. 

 Si el nombre de archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. 

 Si el nombre de archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. 

 Si el nombre de archivo de salida se proporciona como "myPath/myFilename.jpeg", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.jpeg", donde N es el número de diapositiva. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Convierte [Presentation](../../aspose.slides/presentation/) a PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Convierte [Presentation](../../aspose.slides/presentation/) a PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convierte [Presentation](../../aspose.slides/presentation/) a PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Convierte [Presentation](../../aspose.slides/presentation/) a PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. 

 Si el nombre de archivo de salida se proporciona como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.png", donde N es el número de diapositiva. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. 

 Si el nombre de archivo de salida se proporciona como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.png", donde N es el número de diapositiva. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. 

 Si el nombre de archivo de salida se proporciona como "myPath/myFilename.png", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.png", donde N es el número de diapositiva. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Convierte [Presentation](../../aspose.slides/presentation/) a SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Convierte [Presentation](../../aspose.slides/presentation/) a SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Convierte [Presentation](../../aspose.slides/presentation/) a SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Convierte [Presentation](../../aspose.slides/presentation/) a SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Convierte [Presentation](../../aspose.slides/presentation/) a SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convierte la presentación de entrada en un conjunto de imágenes en formato TIFF. 

 Si el nombre de archivo de salida se proporciona como "myPath/myFilename.tiff", el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.tiff", donde N es el número de diapositiva. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Convierte la presentación de entrada al formato TIFF con opciones personalizadas. Si el nombre de archivo de salida se proporciona como "myPath/myFilename.tiff" y *multipage* es **false**, el resultado se guardará como un conjunto de archivos "myPath/myFilename_N.tiff", donde N es el número de diapositiva. De lo contrario, si *multipage* es **true**, el resultado será un documento multipágina "myPath/myFilename.tiff". |
## Definiciones de tipo

| Definición de tipo | Descripción |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Función de devolución de llamada que se invocará para cada [Slide](../../aspose.slides/slide/), se espera que se devuelva la ruta de salida. |
## Observaciones



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Véase también

* Espacio de nombres [Aspose::Slides::LowCode](../)
* Biblioteca [Aspose.Slides](../../)