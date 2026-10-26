---
title: GetImage()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve un objeto Image de miniatura con escala personalizada.
type: docs
weight: 144
url: /es/aspose.slides/slide/getimage/
---
## Slide::GetImage(float, float) método


Devuelve un objeto Image de miniatura con escala personalizada.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(float scaleX, float scaleY) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |

### Valor de retorno

[IImage](../../iimage/) objeto.
## Observaciones



El siguiente ejemplo muestra cómo generar miniaturas a partir de PowerPoint [Presentation](../../presentation/): 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"ThumbnailFromSlide.pptx");

// Access the first slide
System::SharedPtr<ISlide> sld = pres->get_Slide(0);
// Create a full scale image
System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
// Save the image to disk in JPEG format
bmp->Save(u"Thumbnail_out.jpg", Aspose::Slides::ImageFormat::Jpeg);
```
 El siguiente ejemplo muestra cómo convertir diapositivas a bitmap y guardar las imágenes en PNG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Convierte la primera diapositiva de la presentación en un objeto Bitmap
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage();
// Guarda la imagen en formato PNG
bmp->Save(u"Slide_0.png", Aspose::Slides::ImageFormat::Png);
```
 El siguiente ejemplo muestra cómo convertir PowerPoint PPT/PPTX a JPG: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.ppt");

for (auto&& sld : pres->get_Slides())
{
    // Crear una imagen a escala completa
    System::SharedPtr<IImage> bmp = sld->GetImage(1.0f, 1.0f);
    // Guardar la imagen en disco en formato JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```
 El siguiente ejemplo muestra cómo convertir PowerPoint PPT/PPTX a JPG con dimensiones personalizadas: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PowerPoint-Presentation.pptx");

// Definir dimensiones
int32_t desiredX = 1200;
int32_t desiredY = 800;
// Obtener valores escalados de X y Y
float scaleX = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Width()) * desiredX;
float scaleY = (float)(1.0 / pres->get_SlideSize()->get_Size().get_Height()) * desiredY;

for (auto&& sld : pres->get_Slides())
{
    // Crear una imagen a escala completa
    System::SharedPtr<IImage> bmp = sld->GetImage(scaleX, scaleY);
    // Guardar la imagen en disco en formato JPEG
    bmp->Save(System::String::Format(u"Slide_{0}.jpg", sld->get_SlideNumber()), Aspose::Slides::ImageFormat::Jpeg);
}
```

## Slide::GetImage() método


Devuelve un objeto Image de miniatura (20 % del tamaño real).

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage() override
```

## Slide::GetImage(System::Drawing::Size) método


Devuelve un objeto Image de miniatura con el tamaño especificado.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::Drawing::Size imageSize) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor de retorno

Objeto Image.
## Observaciones



El siguiente ejemplo muestra cómo convertir diapositivas a imágenes con tamaños personalizados usando C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");

// Convierte la primera diapositiva de la presentación a un Bitmap con el tamaño especificado
System::SharedPtr<IImage> bmp = pres->get_Slide(0)->GetImage(System::Drawing::Size(1820, 1040));

// Guarda la imagen en formato JPEG
bmp->Save(u"Slide_0.jpg", Aspose::Slides::ImageFormat::Jpeg);
```




## Slide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) método


Devuelve un objeto de imagen tiff de miniatura con los parámetros especificados.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::ITiffOptions> options) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opciones Tiff. |

### Valor de retorno

Objeto Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) método


Devuelve un objeto Image de miniatura.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |

### Valor de retorno

Objeto Image.

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) método


Devuelve un objeto Image de miniatura con escala personalizada.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| scaleX | **float** | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scaleY | **float** | El valor por el cual escalar esta miniatura en la dirección del eje y. |

### Valor de retorno

Objetos Bitmap.
## Observaciones



El siguiente ejemplo muestra cómo convertir diapositivas con notas y comentarios a [Images](../../images/) usando C#. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"PresentationNotesComments.pptx");

// Crear las opciones de renderizado
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
// Crear opciones de diseño de notas y comentarios
System::SharedPtr<NotesCommentsLayoutingOptions> notesCommentsLayouting = System::MakeObject<NotesCommentsLayoutingOptions>();
// Establece la posición de las notas en la página
notesCommentsLayouting->set_NotesPosition(NotesPositions::BottomTruncated);
// Establece la posición de los comentarios en la página
notesCommentsLayouting->set_CommentsPosition(CommentsPositions::Right);
// Establece el ancho del área de salida de comentarios
notesCommentsLayouting->set_CommentsAreaWidth(500);
// Establece el color para el área de comentarios
notesCommentsLayouting->set_CommentsAreaColor(System::Drawing::Color::get_AntiqueWhite());
// Establecer opciones de diseño para el renderizado
options->set_SlidesLayoutOptions(notesCommentsLayouting);
// Convierte la primera diapositiva de la presentación en un objeto IImage
System::SharedPtr<IImage> image = pres->get_Slide(0)->GetImage(options, 2.0f, 2.0f);
// Guarda la imagen en formato GIF
image->Save(u"Slide_Notes_Comments_0.gif", ImageFormat::Gif);
```

## Slide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) método


Devuelve un objeto Image de miniatura con el tamaño especificado.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Slide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opciones de renderizado. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Tamaño de la imagen a crear. |

### Valor de retorno

Objeto Image.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [Slide](../)
* Class [Size](../../../system.drawing/size/)
* Class [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)