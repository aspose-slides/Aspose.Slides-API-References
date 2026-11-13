---
title: PictureFillFormat
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta uno stile di riempimento immagine.
type: docs
weight: 9410
url: /it/aspose.slides/picturefillformat/
---
## PictureFillFormat classe

Rappresenta uno stile di riempimento immagine.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Proprietà

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia di base IPresentationComponent. Solo lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che viene ritagliata nella parte inferiore dell'immagine. Lettura/scrittura Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che viene ritagliata nella parte sinistra dell'immagine. Lettura/scrittura Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che viene ritagliata nella parte destra dell'immagine. Lettura/scrittura Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che viene ritagliata nella parte superiore dell'immagine. Lettura/scrittura Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Restituisce o imposta i dpi utilizzati per riempire un'immagine. Lettura/scrittura Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Restituisce l'immagine. Solo lettura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Restituisce o imposta la modalità di riempimento dell'immagine. Lettura/scrittura [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'espansione. Lettura/scrittura Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'espansione. Lettura/scrittura Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'espansione. Lettura/scrittura Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un'espansione. Lettura/scrittura Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Restituisce o imposta come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del pattern della texture e come viene ripetuto sulla forma. Lettura/scrittura [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Ribalta la tessera della texture attorno al suo asse orizzontale, verticale o entrambi. Lettura/scrittura [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Restituisce o imposta lo spostamento orizzontale della texture dall'origine della forma in punti. Un valore positivo sposta la texture a destra, mentre un valore negativo la sposta a sinistra. Lettura/scrittura Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Restituisce o imposta lo spostamento verticale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Lettura/scrittura Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Restituisce o imposta la scala orizzontale per il riempimento della texture come percentuale. Lettura/scrittura Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Restituisce o imposta la scala verticale per il riempimento della texture come percentuale. Lettura/scrittura Single. |

## Metodi

| Name | Description |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Comprime l'immagine riducendone le dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprime l'immagine riducendone le dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Elimina le aree ritagliate dell'immagine di riempimento. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IPictureFillFormat](../ipicturefillformat)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->