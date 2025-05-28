---
title: ComprimirImagen
second_title: Referencia de API de Aspose.Slides para .NET
description: Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.
type: docs
weight: 180
url: /es/aspose.slides/picturefillformat/compressimage/
---

## ComprimirImagen(bool, PicturesCompression) {#compressimage}

Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

```csharp
public bool CompressImage(bool deleteCroppedAreasOfImage, PicturesCompression resolution)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deleteCroppedAreasOfImage | Boolean | Si es verdadero, el método eliminará las áreas recortadas de la imagen, lo que puede reducir aún más su tamaño. |
| resolution | PicturesCompression | La resolución objetivo para la compresión, especificada como un valor de la enumeración [`PicturesCompression`](../../../aspose.slides.export/picturescompression). |

### Valor de Retorno

Un Booleano que indica si la imagen se comprimió con éxito. Devuelve `true` si la imagen fue redimensionada o recortada, de lo contrario `false`.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando la resolución no es un valor válido. |

### Comentarios

Este método cambia el tamaño y la resolución de la imagen de manera similar a la función "Formato de imagen -> Comprimir imágenes" de PowerPoint.

### Ejemplos

El siguiente ejemplo demuestra cómo usar el método `CompressImage` para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando áreas recortadas:

```csharp
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];
    IPictureFrame picFrame = slide.Shapes[0] as IPictureFrame;
    // Comprimir la imagen con una resolución objetivo de 150 DPI (resolución web) y eliminar áreas recortadas
    bool result = picFrame.PictureFormat.CompressImage(true, PicturesCompression.Dpi150);
}
```

### Véase También

* enum [PicturesCompression](../../../aspose.slides.export/picturescompression)
* class [PictureFillFormat](../../picturefillformat)
* namespace [Aspose.Slides](../../picturefillformat)
* assembly [Aspose.Slides](../../../)

---

## ComprimirImagen(bool, float) {#compressimage_1}

Comprime la imagen reduciendo su tamaño en función del tamaño de la forma y la resolución especificada. Opcionalmente, también elimina las áreas recortadas.

```csharp
public bool CompressImage(bool deleteCroppedAreasOfImage, float resolution)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| deleteCroppedAreasOfImage | Boolean | Si es verdadero, el método eliminará las áreas recortadas de la imagen, lo que puede reducir aún más su tamaño. |
| resolution | Single | La resolución objetivo en DPI. Este valor debe ser positivo y define cómo se redimensionará la imagen. |

### Valor de Retorno

Un Booleano que indica si la imagen se comprimió con éxito. Devuelve `true` si la imagen fue redimensionada o recortada, de lo contrario `false`.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | Se lanza cuando la resolución no es un valor positivo. |

### Comentarios

Este método cambia el tamaño y la resolución de la imagen de manera similar a la función "Formato de imagen -> Comprimir imágenes" de PowerPoint.

### Ejemplos

El siguiente ejemplo demuestra cómo usar el método `CompressImage` para reducir el tamaño de una imagen en una presentación estableciendo una resolución objetivo y eliminando áreas recortadas:

```csharp
[C#]
using (Presentation presentation = new Presentation("demo.pptx"))
{
    ISlide slide = presentation.Slides[0];

    // Obtiene el PictureFrame
    IPictureFrame picFrame = slide.Shapes[0] as IPictureFrame;

    // Comprimir la imagen con una resolución objetivo de 150 DPI (resolución web) y eliminar áreas recortadas
    bool result=picFrame.PictureFormat.CompressImage(true, 150f); // Resolución web
}
```

### Véase También

* class [PictureFillFormat](../../picturefillformat)
* namespace [Aspose.Slides](../../picturefillformat)
* assembly [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->