---
title: ToPng()
second_title: Referencia de API de Aspose.Slides para C++
description: Convierte la presentación de entrada en un conjunto de imágenes en formato PNG.  Si el nombre de archivo de salida se proporciona como \"myPath/myFilename.png\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.png\", donde N es el número de diapositiva.
type: docs
weight: 53
url: /es/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) método

Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. 

 Si el nombre de archivo de salida se proporciona como \"myPath/myFilename.png\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.png\", donde N es el número de diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre de archivo de salida. |
## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) método

Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. 

 Si el nombre de archivo de salida se proporciona como \"myPath/myFilename.png\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.png\", donde N es el número de diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada |
| outputFileName | [System::String](../../../system/string/) | El nombre de archivo de salida. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | El tamaño de cada imagen generada. |
## Observaciones

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) método

Convierte la presentación de entrada en un conjunto de imágenes en formato PNG. 

 Si el nombre de archivo de salida se proporciona como \"myPath/myFilename.png\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.png\", donde N es el número de diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre de archivo de salida. |
| scale | **float** | El factor de escala aplicado a las imágenes de salida respecto al tamaño original de la diapositiva. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Las opciones de renderizado. |
## Observaciones

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Presentation](../../../aspose.slides/presentation/)
* Clase [String](../../../system/string/)
* Clase [Convert](../)
* Clase [Size](../../../system.drawing/size/)
* Clase [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Espacio de nombres [Aspose::Slides::LowCode](../../)
* Biblioteca [Aspose.Slides](../../../)