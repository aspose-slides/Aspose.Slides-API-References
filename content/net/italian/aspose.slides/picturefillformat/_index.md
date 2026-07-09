---
title: PictureFillFormat
second_title: Riferimento API Aspose.Sildes per .NET
description: Rappresenta uno stile di riempimento di immagine.
type: docs
weight: 9390
url: /it/aspose.slides/picturefillformat/
---
## PictureFillFormat classe

Rappresenta uno stile di riempimento di immagine.

```csharp
public sealed class PictureFillFormat : PVIObject, IPictureFillFormat
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Solo lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [CropBottom](../../aspose.slides/picturefillformat/cropbottom) { get; set; } | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che vengono ritagliate dal lato inferiore dell'immagine. Lettura/Scrittura Single. |
| [CropLeft](../../aspose.slides/picturefillformat/cropleft) { get; set; } | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che vengono ritagliate dal lato sinistro dell'immagine. Lettura/Scrittura Single. |
| [CropRight](../../aspose.slides/picturefillformat/cropright) { get; set; } | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che vengono ritagliate dal lato destro dell'immagine. Lettura/Scrittura Single. |
| [CropTop](../../aspose.slides/picturefillformat/croptop) { get; set; } | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che vengono ritagliate dalla parte superiore dell'immagine. Lettura/Scrittura Single. |
| [Dpi](../../aspose.slides/picturefillformat/dpi) { get; set; } | Restituisce o imposta i dpi usati per riempire un'immagine. Lettura/Scrittura Int32. |
| [Picture](../../aspose.slides/picturefillformat/picture) { get; } | Restituisce l'immagine. Solo lettura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/picturefillformat/picturefillmode) { get; set; } | Restituisce o imposta la modalità di riempimento dell'immagine. Lettura/Scrittura [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/picturefillformat/stretchoffsetbottom) { get; set; } | Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo inferiore del riquadro contenitore della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa specifica un’estensione. Lettura/Scrittura Single. |
| [StretchOffsetLeft](../../aspose.slides/picturefillformat/stretchoffsetleft) { get; set; } | Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo sinistro del riquadro contenitore della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa specifica un’estensione. Lettura/Scrittura Single. |
| [StretchOffsetRight](../../aspose.slides/picturefillformat/stretchoffsetright) { get; set; } | Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo destro del riquadro contenitore della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa specifica un’estensione. Lettura/Scrittura Single. |
| [StretchOffsetTop](../../aspose.slides/picturefillformat/stretchoffsettop) { get; set; } | Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo superiore del riquadro contenitore della forma. Una percentuale positiva indica un rientro, mentre una percentuale negativa specifica un’estensione. Lettura/Scrittura Single. |
| [TileAlignment](../../aspose.slides/picturefillformat/tilealignment) { get; set; } | Restituisce o imposta come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del motivo della trama e il modo in cui si ripete sulla forma. Lettura/Scrittura [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/picturefillformat/tileflip) { get; set; } | Capovolge la tessera della trama attorno al suo asse orizzontale, verticale o entrambi. Lettura/Scrittura [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/picturefillformat/tileoffsetx) { get; set; } | Restituisce o imposta lo spostamento orizzontale della trama dall'origine della forma in punti. Un valore positivo sposta la trama verso destra, mentre un valore negativo la sposta verso sinistra. Lettura/Scrittura Single. |
| [TileOffsetY](../../aspose.slides/picturefillformat/tileoffsety) { get; set; } | Restituisce o imposta lo spostamento verticale della trama dall'origine della forma in punti. Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto. Lettura/Scrittura Single. |
| [TileScaleX](../../aspose.slides/picturefillformat/tilescalex) { get; set; } | Restituisce o imposta la scala orizzontale per il riempimento della trama come percentuale. Lettura/Scrittura Single. |
| [TileScaleY](../../aspose.slides/picturefillformat/tilescaley) { get; set; } | Restituisce o imposta la scala verticale per il riempimento della trama come percentuale. Lettura/Scrittura Single. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage_1)(bool, float) | Comprimi l'immagine riducendo le sue dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate. |
| [CompressImage](../../aspose.slides/picturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprimi l'immagine riducendo le sue dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente, elimina anche le aree ritagliate. |
| [DeletePictureCroppedAreas](../../aspose.slides/picturefillformat/deletepicturecroppedareas)() | Elimina le aree ritagliate dell'immagine di riempimento. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IPictureFillFormat](../ipicturefillformat)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->