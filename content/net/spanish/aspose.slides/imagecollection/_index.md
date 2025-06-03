---
title: ImageCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa la colección de PPImage.
type: docs
weight: 7200
url: /es/aspose.slides/imagecollection/
---

## Clase ImageCollection

Representa la colección de PPImage.

```csharp
public sealed class ImageCollection : DomObject<Presentation>, IImageCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/imagecollection/count) { get; } | Devuelve el número de imágenes en la colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/imagecollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura Boolean. |
| [Item](../../aspose.slides/imagecollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`IPPImage`](../ippimage). |
| [SyncRoot](../../aspose.slides/imagecollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddImage](../../aspose.slides/imagecollection/addimage#addimage_3)(byte[]) | Agrega una imagen a una presentación desde el búfer especificado. |
| [AddImage](../../aspose.slides/imagecollection/addimage#addimage)(IImage) | Agrega una imagen a una presentación. |
| [AddImage](../../aspose.slides/imagecollection/addimage#addimage_1)(IPPImage) | Agrega una copia de una imagen de otra presentación. |
| [AddImage](../../aspose.slides/imagecollection/addimage#addimage_2)(ISvgImage) | Agrega una imagen a una presentación desde un objeto Svg. |
| [AddImage](../../aspose.slides/imagecollection/addimage#addimage_5)(MemoryStream) | Agrega una imagen a una presentación desde un flujo. |
| [AddImage](../../aspose.slides/imagecollection/addimage#addimage_6)(Stream) | Agrega una imagen a una presentación desde un flujo. |
| [AddImage](../../aspose.slides/imagecollection/addimage#addimage_7)(Stream, LoadingStreamBehavior) | Crea y agrega una imagen a una presentación desde un flujo. |
| [CopyTo](../../aspose.slides/imagecollection/copyto)(Array, int) | Copia todos los elementos de la colección al arreglo especificado. |
| [GetEnumerator](../../aspose.slides/imagecollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |

### Véase también

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Presentation](../presentation)
* interfaz [IImageCollection](../iimagecollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->