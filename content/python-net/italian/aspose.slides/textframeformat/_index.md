---
title: TextFrameFormat class
second_title: Aspose.Slides per Python via .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contiene le proprietà formatTextFrameFormatting del TextFrame.

**Eredità:**[`TextFrameFormat`](/slides/python-net/it/aspose.slides/textframeformat) → [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)

Il tipo TextFrameFormat espone i seguenti membri:

## Costruttori

| Costruttore | Descrizione |
| :- | :- |
| [`__init__(self)`](/slides/python-net/it/aspose.slides/textframeformat/__init__/#) | Inizializza una nuova istanza della classe [`TextFrameFormat`](/slides/python-net/it/aspose.slides/textframeformat). |

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`three_d_format`](/slides/python-net/it/aspose.slides/textframeformat/three_d_format/) | Restituisce l'oggetto ThreeDFormat che rappresenta le proprietà dell'effetto 3d per un testo.<br/>            Solo lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`margin_left`](/slides/python-net/it/aspose.slides/textframeformat/margin_left/) | Restituisce o imposta il margine sinistro (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_right`](/slides/python-net/it/aspose.slides/textframeformat/margin_right/) | Restituisce o imposta il margine destro (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_top`](/slides/python-net/it/aspose.slides/textframeformat/margin_top/) | Restituisce o imposta il margine superiore (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_bottom`](/slides/python-net/it/aspose.slides/textframeformat/margin_bottom/) | Restituisce o imposta il margine inferiore (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`wrap_text`](/slides/python-net/it/aspose.slides/textframeformat/wrap_text/) | **True** se il testo è avvolto ai margini del TextFrame.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/it/aspose.slides/textframeformat/anchoring_type/) | Restituisce o imposta l'ancora verticale del testo in un TextFrame.<br/>            Lettura/scrittura [`TextAnchorType`](/slides/python-net/it/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/it/aspose.slides/textframeformat/center_text/) | Se NullableBool.True, allora il testo deve essere centrato orizzontalmente nella casella.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/it/aspose.slides/textframeformat/text_vertical_type/) | Determina l'orientamento del testo.<br/>            Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dall'angolo personalizzato<br/>            nella proprietà RotationAngle.<br/>            Lettura/scrittura [`TextVerticalType`](/slides/python-net/it/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/it/aspose.slides/textframeformat/autofit_type/) | Restituisce o imposta la modalità di adattamento automatico del testo.<br/>            Lettura/scrittura [`TextAutofitType`](/slides/python-net/it/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/it/aspose.slides/textframeformat/column_count/) | Restituisce o imposta il numero di colonne nell'area di testo.<br/>            Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. <br/>            Il valore 0 indica un valore non definito.<br/>            Lettura/scrittura **int**. |
| [`column_spacing`](/slides/python-net/it/aspose.slides/textframeformat/column_spacing/) | Restituisce o imposta lo spazio tra le colonne di testo nell'area di testo (in punti). Questo dovrebbe applicarsi solo <br/>            quando è presente più di 1 colonna.<br/>            Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. <br/>            Lettura/scrittura **float**. |
| [`rotation_angle`](/slides/python-net/it/aspose.slides/textframeformat/rotation_angle/) | Specifica la rotazione personalizzata che viene applicata al testo all'interno del riquadro. Se non è<br/>            specificata, viene usata la rotazione della forma associata. Se è specificata, allora questa è<br/>            applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione applicata in<br/>            aggiunta al testo stesso che ha una rotazione applicata.<br/>            Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType.<br/>            Lettura/scrittura **float**. |
| [`transform`](/slides/python-net/it/aspose.slides/textframeformat/transform/) | Ottiene o imposta la forma di avvolgimento del testo.<br/>            Lettura/scrittura [`TextShapeType`](/slides/python-net/it/aspose.slides/textshapetype). |
| [`keep_text_flat`](/slides/python-net/it/aspose.slides/textframeformat/keep_text_flat/) | Ottiene o imposta il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3-D.<br/>            Lettura/scrittura **bool**. |
| [`slide`](/slides/python-net/it/aspose.slides/textframeformat/slide/) |  |
| [`presentation`](/slides/python-net/it/aspose.slides/textframeformat/presentation/) |  |
| [`text_style`](/slides/python-net/it/aspose.slides/textframeformat/text_style/) |  |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/textframeformat/get_effective/#) | Ottiene i dati di formattazione effective del text frame con l'ereditarietà applicata. |

### Vedi anche
* classe [`PVIObject`](/slides/python-net/it/aspose.slides/pviobject)
* classe [`TextFrameFormat`](/slides/python-net/it/aspose.slides/textframeformat)
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)