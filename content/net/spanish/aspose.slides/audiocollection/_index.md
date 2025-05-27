---
title: AudioCollection
second_title: Referencia de API de Aspose.Slides para .NET
description: Representa una colección de archivos de audio incrustados.
type: docs
weight: 780
url: /es/aspose.slides/audiocollection/
---

## Clase AudioCollection

Representa una colección de archivos de audio incrustados.

```csharp
public class AudioCollection : DomObject<Presentation>, IAudioCollection
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Count](../../aspose.slides/audiocollection/count) { get; } | Devuelve el número de archivos de audio en la colección. Solo lectura Int32. |
| [IsSynchronized](../../aspose.slides/audiocollection/issynchronized) { get; } | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para hilos). Solo lectura Boolean. |
| [Item](../../aspose.slides/audiocollection/item) { get; } | Obtiene el elemento en el índice especificado. Solo lectura [`IAudio`](../iaudio). |
| [SyncRoot](../../aspose.slides/audiocollection/syncroot) { get; } | Devuelve una raíz de sincronización. Solo lectura Object. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_1)(byte[]) | Crea y agrega un audio a una presentación desde un arreglo de bytes. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio)(IAudio) | Agrega una copia de un archivo de audio desde otra presentación. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_2)(Stream) | Crea y agrega un audio a una presentación desde un flujo. |
| [AddAudio](../../aspose.slides/audiocollection/addaudio#addaudio_3)(Stream, LoadingStreamBehavior) | Crea y agrega un audio a una presentación desde un flujo. |
| [CopyTo](../../aspose.slides/audiocollection/copyto)(Array, int) | Copia audios al arreglo especificado comenzando desde el índice especificado. |
| [GetEnumerator](../../aspose.slides/audiocollection/getenumerator)() | Devuelve un enumerador que itera a través de la colección. |

### Véase También

* clase [DomObject&lt;TParent&gt;](../domobject-1)
* clase [Presentation](../presentation)
* interfaz [IAudioCollection](../iaudiocollection)
* espacio de nombres [Aspose.Slides](../../aspose.slides)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->