---
title: IPictureFillFormat class
second_title: Riferimento API di Aspose.Slides per Python via .NET
description: 
type: docs
url: /it/aspose.slides/ipicturefillformat/
---
## IPictureFillFormat classe

Rappresenta uno stile di riempimento con immagine.

Il tipo IPictureFillFormat espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`dpi`](/slides/python-net/it/aspose.slides/ipicturefillformat/dpi/) | Restituisce o imposta i DPI utilizzati per riempire un'immagine.<br/>            Lettura/scrittura **int**. |
| [`picture_fill_mode`](/slides/python-net/it/aspose.slides/ipicturefillformat/picture_fill_mode/) | Restituisce o imposta la modalità di riempimento dell'immagine.<br/>            Lettura/scrittura [`PictureFillMode`](/slides/python-net/it/aspose.slides/picturefillmode). |
| [`picture`](/slides/python-net/it/aspose.slides/ipicturefillformat/picture/) | Restituisce l'immagine.<br/>            Sola lettura [`ISlidesPicture`](/slides/python-net/it/aspose.slides/islidespicture). |
| [`crop_left`](/slides/python-net/it/aspose.slides/ipicturefillformat/crop_left/) | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che vengono ritagliate<br/>            a sinistra dell'immagine.<br/>            Lettura/scrittura **float**. |
| [`crop_top`](/slides/python-net/it/aspose.slides/ipicturefillformat/crop_top/) | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che vengono ritagliate<br/>            in alto dell'immagine.<br/>            Lettura/scrittura **float**. |
| [`crop_right`](/slides/python-net/it/aspose.slides/ipicturefillformat/crop_right/) | Restituisce o imposta il numero di percentuali della larghezza reale dell'immagine che vengono ritagliate<br/>            a destra dell'immagine.<br/>            Lettura/scrittura **float**. |
| [`crop_bottom`](/slides/python-net/it/aspose.slides/ipicturefillformat/crop_bottom/) | Restituisce o imposta il numero di percentuali dell'altezza reale dell'immagine che vengono ritagliate<br/>            in basso dell'immagine.<br/>            Lettura/scrittura **float**. |
| [`stretch_offset_left`](/slides/python-net/it/aspose.slides/ipicturefillformat/stretch_offset_left/) | Restituisce o imposta il bordo sinistro del rettangolo di riempimento definito da uno spostamento percentuale <br/>            dal bordo sinistro del riquadro di delimitazione della forma.<br/>            Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un fuoriuscita.<br/>            Lettura/scrittura **float**. |
| [`stretch_offset_top`](/slides/python-net/it/aspose.slides/ipicturefillformat/stretch_offset_top/) | Restituisce o imposta il bordo superiore del rettangolo di riempimento definito da uno spostamento percentuale <br/>            dal bordo superiore del riquadro di delimitazione della forma.<br/>            Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un fuoriuscita.<br/>            Lettura/scrittura **float**. |
| [`stretch_offset_right`](/slides/python-net/it/aspose.slides/ipicturefillformat/stretch_offset_right/) | Restituisce o imposta il bordo destro del rettangolo di riempimento definito da uno spostamento percentuale <br/>            dal bordo destro del riquadro di delimitazione della forma.<br/>            Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un fuoriuscita.<br/>            Lettura/scrittura **float**. |
| [`stretch_offset_bottom`](/slides/python-net/it/aspose.slides/ipicturefillformat/stretch_offset_bottom/) | Restituisce o imposta il bordo inferiore del rettangolo di riempimento definito da uno spostamento percentuale <br/>            dal bordo inferiore del riquadro di delimitazione della forma.<br/>            Una percentuale positiva specifica un rientro, mentre una percentuale negativa specifica un fuoriuscita.<br/>            Lettura/scrittura **float**. |
| [`tile_offset_x`](/slides/python-net/it/aspose.slides/ipicturefillformat/tile_offset_x/) | Restituisce o imposta lo spostamento orizzontale della trama dall'origine della forma in punti.<br/>             Un valore positivo sposta la trama verso destra, mentre un valore negativo la sposta verso sinistra.<br/>             Lettura/scrittura **float**. |
| [`tile_offset_y`](/slides/python-net/it/aspose.slides/ipicturefillformat/tile_offset_y/) | Restituisce o imposta lo spostamento verticale della trama dall'origine della forma in punti.<br/>             Un valore positivo sposta la trama verso il basso, mentre un valore negativo la sposta verso l'alto.<br/>             Lettura/scrittura **float**. |
| [`tile_scale_x`](/slides/python-net/it/aspose.slides/ipicturefillformat/tile_scale_x/) | Restituisce o imposta la scala orizzontale del riempimento della trama come percentuale.<br/>             Lettura/scrittura **float**. |
| [`tile_scale_y`](/slides/python-net/it/aspose.slides/ipicturefillformat/tile_scale_y/) | Restituisce o imposta la scala verticale del riempimento della trama come percentuale.<br/>             Lettura/scrittura **float**. |
| [`tile_alignment`](/slides/python-net/it/aspose.slides/ipicturefillformat/tile_alignment/) | Restituisce o imposta come la trama è allineata all'interno della forma. Questa impostazione controlla il punto di partenza del pattern della trama e come si ripete sulla forma.<br/>             Lettura/scrittura [`RectangleAlignment`](/slides/python-net/it/aspose.slides/rectanglealignment). |
| [`tile_flip`](/slides/python-net/it/aspose.slides/ipicturefillformat/tile_flip/) | Capovolge la piastrella della trama attorno al suo asse orizzontale, verticale o entrambi.<br/>             Lettura/scrittura [`TileFlip`](/slides/python-net/it/aspose.slides/tileflip). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/it/aspose.slides/ipicturefillformat/compress_image/#bool-asposeslidesexportpicturescompression) | Comprimi l'immagine riducendone le dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Opzionalmente, elimina anche le aree ritagliate. |
| [`compress_image(self, delete_cropped_areas_of_image, resolution)`](/slides/python-net/it/aspose.slides/ipicturefillformat/compress_image/#bool-float) | Comprimi l'immagine riducendone le dimensioni in base alle dimensioni della forma e alla risoluzione specificata. Opzionalmente, elimina anche le aree ritagliate. |
| [`delete_picture_cropped_areas(self)`](/slides/python-net/it/aspose.slides/ipicturefillformat/delete_picture_cropped_areas/#) | Elimina le aree ritagliate dell'immagine di riempimento. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)