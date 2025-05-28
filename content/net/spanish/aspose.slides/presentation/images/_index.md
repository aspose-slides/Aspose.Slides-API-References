---
title: Imágenes
second_title: Referencia de la API de Aspose.Slides para .NET
description: Devuelve la colección de todas las imágenes en la presentación. Solo lectura IImageCollectionaspose.slides/iimagecollection.
type: docs
weight: 140
url: /es/aspose.slides/presentation/images/
---

## Propiedad Presentation.Images

Devuelve la colección de todas las imágenes en la presentación. Solo lectura [`IImageCollection`](../../iimagecollection).

```csharp
public IImageCollection Images { get; }
```

### Ejemplos

Los siguientes ejemplos muestran cómo agregar una imagen como BLOB en una presentación de PowerPoint.

```csharp
[C#]
string pathToLargeImage = "large_image.jpg";
// crea una nueva presentación a la que se añadirá la imagen.
using (Presentation pres = new Presentation())
{
	using (FileStream fileStream = new FileStream(pathToLargeImage, FileMode.Open))
	{
		// Agreguemos la imagen a la presentación - elegimos el comportamiento KeepLocked porque no
		// tenemos la intención de acceder al archivo "largeImage.png".
		IPPImage img = pres.Images.AddImage(fileStream, LoadingStreamBehavior.KeepLocked);
		pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 0, 0, 300, 200, img);
		// Guarda la presentación. Mientras se genera una gran presentación, el consumo de memoria
		// se mantiene bajo a lo largo del ciclo de vida del objeto pres
		pres.Save("presentationWithLargeImage.pptx", SaveFormat.Pptx);
	}
}
```

Los siguientes ejemplos agregan un hipervínculo a una imagen en una presentación de PowerPoint.

```csharp
[C#]
using (Presentation pres = new Presentation())
{
    // Agrega una imagen a la presentación
    IPPImage image = pres.Images.AddImage(File.ReadAllBytes("image.png"));
    // Crea un marco de imagen en la diapositiva 1 basado en la imagen agregada previamente
    IPictureFrame pictureFrame = pres.Slides[0].Shapes.AddPictureFrame(ShapeType.Rectangle, 10, 10, 100, 100, image);
    pictureFrame.HyperlinkClick = new Hyperlink("https://www.aspose.com/");
    pictureFrame.HyperlinkClick.Tooltip = "Más del 70% de las empresas Fortune 100 confían en las API de Aspose";
    pres.Save("pres-out.pptx", SaveFormat.Pptx);
}
```

### Véase También

* interfaz [IImageCollection](../../iimagecollection)
* clase [Presentation](../../presentation)
* espacio de nombres [Aspose.Slides](../../presentation)
* ensamblado [Aspose.Slides](../../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->