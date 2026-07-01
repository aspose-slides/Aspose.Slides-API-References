---
title: IPictureFillFormat
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta uno stile di riempimento con immagine.
type: docs
weight: 6630
url: /it/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat interfaccia

Rappresenta uno stile di riempimento con immagine.

```csharp
public interface IPictureFillFormat : IFillParamSource
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AsIFillParamSource](../../aspose.slides/ipicturefillformat/asifillparamsource) { get; } | Consente di ottenere l'interfaccia base IFillParamSource. Solo lettura [`IFillParamSource`](../ifillparamsource). |
| [CropBottom](../../aspose.slides/ipicturefillformat/cropbottom) { get; set; } | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che viene ritagliata dal basso dell'immagine. Lettura/Scrittura Single. |
| [CropLeft](../../aspose.slides/ipicturefillformat/cropleft) { get; set; } | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che viene ritagliata a sinistra dell'immagine. Lettura/Scrittura Single. |
| [CropRight](../../aspose.slides/ipicturefillformat/cropright) { get; set; } | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che viene ritagliata a destra dell'immagine. Lettura/Scrittura Single. |
| [CropTop](../../aspose.slides/ipicturefillformat/croptop) { get; set; } | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che viene ritagliata dalla parte superiore dell'immagine. Lettura/Scrittura Single. |
| [Dpi](../../aspose.slides/ipicturefillformat/dpi) { get; set; } | Restituisce o imposta i dpi utilizzati per riempire un'immagine. Lettura/Scrittura Int32. |
| [Picture](../../aspose.slides/ipicturefillformat/picture) { get; } | Restituisce l'immagine. Solo lettura [`ISlidesPicture`](../islidespicture). |
| [PictureFillMode](../../aspose.slides/ipicturefillformat/picturefillmode) { get; set; } | Restituisce o imposta la modalità di riempimento dell'immagine. Lettura/Scrittura [`PictureFillMode`](../picturefillmode). |
| [StretchOffsetBottom](../../aspose.slides/ipicturefillformat/stretchoffsetbottom) { get; set; } | Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo inferiore della bounding box della forma. Una percentuale positiva specifica un'inserzione, mentre una percentuale negativa specifica un'espansione. Lettura/Scrittura Single. |
| [StretchOffsetLeft](../../aspose.slides/ipicturefillformat/stretchoffsetleft) { get; set; } | Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo sinistro della bounding box della forma. Una percentuale positiva specifica un'inserzione, mentre una percentuale negativa specifica un'espansione. Lettura/Scrittura Single. |
| [StretchOffsetRight](../../aspose.slides/ipicturefillformat/stretchoffsetright) { get; set; } | Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale dal bordo destro della bounding box della forma. Una percentuale positiva specifica un'inserzione, mentre una percentuale negativa specifica un'espansione. Lettura/Scrittura Single. |
| [StretchOffsetTop](../../aspose.slides/ipicturefillformat/stretchoffsettop) { get; set; } | Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale dal bordo superiore della bounding box della forma. Una percentuale positiva specifica un'inserzione, mentre una percentuale negativa specifica un'espansione. Lettura/Scrittura Single. |
| [TileAlignment](../../aspose.slides/ipicturefillformat/tilealignment) { get; set; } | Restituisce o imposta come la texture è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del pattern della texture e come si ripete sulla forma. Lettura/Scrittura [`RectangleAlignment`](../rectanglealignment). |
| [TileFlip](../../aspose.slides/ipicturefillformat/tileflip) { get; set; } | Capovolge la tessera della texture attorno al suo asse orizzontale, verticale o entrambi. Lettura/Scrittura [`TileFlip`](../tileflip). |
| [TileOffsetX](../../aspose.slides/ipicturefillformat/tileoffsetx) { get; set; } | Restituisce o imposta lo spostamento orizzontale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso destra, mentre un valore negativo la sposta verso sinistra. Lettura/Scrittura Single. |
| [TileOffsetY](../../aspose.slides/ipicturefillformat/tileoffsety) { get; set; } | Restituisce o imposta lo spostamento verticale della texture dall'origine della forma in punti. Un valore positivo sposta la texture verso il basso, mentre un valore negativo la sposta verso l'alto. Lettura/Scrittura Single. |
| [TileScaleX](../../aspose.slides/ipicturefillformat/tilescalex) { get; set; } | Restituisce o imposta la scala orizzontale per il riempimento della texture come percentuale. Lettura/Scrittura Single. |
| [TileScaleY](../../aspose.slides/ipicturefillformat/tilescaley) { get; set; } | Restituisce o imposta la scala verticale per il riempimento della texture come percentuale. Lettura/Scrittura Single. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage_1)(bool, float) | Comprimi l'immagine riducendone le dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente elimina anche le aree ritagliate. |
| [CompressImage](../../aspose.slides/ipicturefillformat/compressimage#compressimage)(bool, PicturesCompression) | Comprimi l'immagine riducendone le dimensioni in base alla dimensione della forma e alla risoluzione specificata. Facoltativamente elimina anche le aree ritagliate. |
| [DeletePictureCroppedAreas](../../aspose.slides/ipicturefillformat/deletepicturecroppedareas)() | Elimina le aree ritagliate dell'immagine di riempimento. |

### Vedi anche

* interfaccia [IFillParamSource](../ifillparamsource)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->