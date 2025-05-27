---
title: GetImage
second_title: Referencia de API de Aspose.Slides para .NET
description: Devuelve un objeto de imagen en miniatura con escalado personalizado.
type: docs
weight: 80
url: /es/aspose.slides/slide/getimage/
---

## GetImage(float, float) {#getimage_5}

Devuelve un objeto de imagen en miniatura con escalado personalizado.

```csharp
public IImage GetImage(float scaleX, float scaleY)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| scaleX | Single | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scaleY | Single | El valor por el cual escalar esta miniatura en la dirección del eje y. |

### Valor de retorno

Objeto IImage.

### Ejemplos

El siguiente ejemplo muestra cómo generar miniaturas a partir de presentaciones de PowerPoint.

```csharp
[C#]
// Instanciar una clase Presentation que representa el archivo de presentación
using (Presentation pres = new Presentation("ThumbnailFromSlide.pptx"))
{
    // Acceder a la primera diapositiva
    ISlide sld = pres.Slides[0];
    // Crear una imagen a escala completa
    IImage bmp = sld.GetImage(1f, 1f);
    // Guardar la imagen en disco en formato JPEG
    bmp.Save("Thumbnail_out.jpg", ImageFormat.Jpeg);
}
```

El siguiente ejemplo muestra cómo convertir diapositivas a bitmap y guardar las imágenes en formato PNG.

```csharp
[C#]
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Convierte la primera diapositiva de la presentación a un objeto Bitmap
    using (IImage bmp = pres.Slides[0].GetImage())
    {
        // Guarda la imagen en formato PNG
        bmp.Save("Slide_0.png", ImageFormat.Png);
    }
}
```

El siguiente ejemplo muestra cómo convertir presentaciones PowerPoint PPT/PPTX a JPG.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.ppt"))
{
	foreach (ISlide sld in pres.Slides)
	{
		// Crear una imagen a escala completa
		IImage bmp = sld.GetImage(1f, 1f);
		// Guardar la imagen en disco en formato JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

El siguiente ejemplo muestra cómo convertir presentaciones PowerPoint PPT/PPTX a JPG con dimensiones personalizadas.

```csharp
[C#]
using (Presentation pres = new Presentation("PowerPoint-Presentation.pptx"))
{
	// Definir dimensiones
	int desiredX = 1200;
	int desiredY = 800;
	// Obtener valores escalados de X y Y
	float ScaleX = (float)(1.0 / pres.SlideSize.Size.Width) * desiredX;
	float ScaleY = (float)(1.0 / pres.SlideSize.Size.Height) * desiredY;
	foreach (ISlide sld in pres.Slides)
	{
		// Crear una imagen a escala completa
		IImage bmp = sld.GetImage(ScaleX, ScaleY);
		// Guardar la imagen en disco en formato JPEG
		bmp.Save(string.Format("Slide_{0}.jpg", sld.SlideNumber), ImageFormat.Jpeg);
	}
}
```

### Ver también

* interfaz [IImage](../../iimage)
* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblado [Aspose.Slides](../../../)

---

## GetImage() {#getimage}

Devuelve un objeto de imagen en miniatura (20% del tamaño real).

```csharp
public IImage GetImage()
```

### Ver también

* interfaz [IImage](../../iimage)
* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblado [Aspose.Slides](../../../)

---

## GetImage(Size) {#getimage_6}

Devuelve un objeto de imagen en miniatura con tamaño especificado.

```csharp
public IImage GetImage(Size imageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| imageSize | Size | Tamaño de la imagen a crear. |

### Valor de retorno

Objeto de imagen.

### Ejemplos

El siguiente ejemplo muestra cómo convertir diapositivas a imágenes con tamaños personalizados usando C#.

```csharp
using (Presentation pres = new Presentation("Presentation.pptx"))
{
    // Convierte la primera diapositiva en la presentación a un Bitmap con el tamaño especificado
    using (IImage bmp = pres.Slides[0].GetImage(new Size(1820, 1040)))
    {
        // Guarda la imagen en formato JPEG
        bmp.Save("Slide_0.jpg", ImageFormat.Jpeg);
    }
}
```

### Ver también

* interfaz [IImage](../../iimage)
* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblado [Aspose.Slides](../../../)

---

## GetImage(ITiffOptions) {#getimage_4}

Devuelve un objeto de imagen tiff en miniatura con parámetros especificados.

```csharp
public IImage GetImage(ITiffOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | ITiffOptions | Opciones de Tiff. |

### Valor de retorno

Objeto de imagen.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza cuando options.SlideLayoutOption es NotesCommentsLayoutingOptions y su propiedad NotesPosition toma el valor NotesPositions.BottomFull. |

### Ver también

* interfaz [IImage](../../iimage)
* interfaz [ITiffOptions](../../../aspose.slides.export/itiffoptions)
* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblado [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions) {#getimage_1}

Devuelve un objeto de imagen en miniatura.

```csharp
public IImage GetImage(IRenderingOptions options)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | IRenderingOptions | Opciones de renderizado. |

### Valor de retorno

Objeto de imagen.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza cuando notesCommentsLayouting.NotesPosition toma el valor NotesPositions.BottomFull |

### Ver también

* interfaz [IImage](../../iimage)
* interfaz [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblado [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, float, float) {#getimage_2}

Devuelve un objeto de imagen en miniatura con escalado personalizado.

```csharp
public IImage GetImage(IRenderingOptions options, float scaleX, float scaleY)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | IRenderingOptions | Opciones de renderizado. |
| scaleX | Single | El valor por el cual escalar esta miniatura en la dirección del eje x. |
| scaleY | Single | El valor por el cual escalar esta miniatura en la dirección del eje y. |

### Valor de retorno

Objetos Bitmap.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza cuando notesCommentsLayouting.NotesPosition toma el valor NotesPositions.BottomFull |

### Ejemplos

El siguiente ejemplo muestra cómo convertir diapositivas con notas y comentarios a imágenes usando C#.

```csharp
using (Presentation pres = new Presentation("PresentationNotesComments.pptx"))
{
    // Crear las opciones de renderizado
    IRenderingOptions options = new RenderingOptions();
    // Crear opciones de disposición de notas y comentarios
    NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
    // Establecer la posición de las notas en la página
    notesCommentsLayouting.NotesPosition = NotesPositions.BottomTruncated;
    // Establecer la posición de los comentarios en la página
    notesCommentsLayouting.CommentsPosition = CommentsPositions.Right;
    // Establecer el ancho del área de salida de comentarios
    notesCommentsLayouting.CommentsAreaWidth = 500;
    // Establecer el color para el área de comentarios
    notesCommentsLayouting.CommentsAreaColor = Color.AntiqueWhite;
    // Establecer opciones de disposición para renderizado
    options.SlidesLayoutOptions = notesCommentsLayouting;
    // Convierte la primera diapositiva de la presentación a un objeto IImage
    IImage image = pres.Slides[0].GetImage(options, 2f, 2f);
    // Guarda la imagen en formato GIF
    image.Save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
}
```

### Ver también

* interfaz [IImage](../../iimage)
* interfaz [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblado [Aspose.Slides](../../../)

---

## GetImage(IRenderingOptions, Size) {#getimage_3}

Devuelve un objeto de imagen en miniatura con tamaño especificado.

```csharp
public IImage GetImage(IRenderingOptions options, Size imageSize)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | IRenderingOptions | Opciones de renderizado. |
| imageSize | Size | Tamaño de la imagen a crear. |

### Valor de retorno

Objeto de imagen.

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | Se lanza cuando options.SlideLayoutOption es NotesCommentsLayoutingOptions y su propiedad NotesPosition toma el valor NotesPositions.BottomFull. |

### Ver también

* interfaz [IImage](../../iimage)
* interfaz [IRenderingOptions](../../../aspose.slides.export/irenderingoptions)
* clase [Slide](../../slide)
* espacio de nombres [Aspose.Slides](../../slide)
* ensamblado [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->