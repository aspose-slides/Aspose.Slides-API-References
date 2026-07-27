---
title: ToJpeg()
second_title: Referencia de la API de Aspose.Slides para C++
description: Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG.  Si el nombre del archivo de salida se da como \"myPath/myFilename.jpeg\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.jpeg\", donde N es el número de diapositiva.
type: docs
weight: 40
url: /es/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) método


Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. 

 Si el nombre del archivo de salida se proporciona como \"myPath/myFilename.jpeg\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.jpeg\", donde N es el número de diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre del archivo de salida. |
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) método


Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. 

 Si el nombre del archivo de salida se proporciona como \"myPath/myFilename.jpeg\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.jpeg\", donde N es el número de diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada |
| outputFileName | [System::String](../../../system/string/) | El nombre del archivo de salida. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | El tamaño de cada imagen generada. |
## Observaciones




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) método


Convierte la presentación de entrada en un conjunto de imágenes en formato JPEG. 

 Si el nombre del archivo de salida se proporciona como \"myPath/myFilename.jpeg\", el resultado se guardará como un conjunto de archivos \"myPath/myFilename_N.jpeg\", donde N es el número de diapositiva.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La presentación de entrada. |
| outputFileName | [System::String](../../../system/string/) | El nombre del archivo de salida. |
| scale | **float** | El factor de escala aplicado a las imágenes de salida en relación con el tamaño original de la diapositiva. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Las opciones de renderizado. |
## Observaciones




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)