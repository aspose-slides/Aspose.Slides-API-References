---
title: ITextFrameFormat class
second_title: Aspose.Slides per Python tramite .NET Riferimento API
description: 
type: docs
url: /it/aspose.slides/itextframeformat/
---
## classe ITextFrameFormat

Contiene le proprietà di formattazione del TextFrame.

Il tipo ITextFrameFormat espone i seguenti membri:

## Proprietà

| Proprietà | Descrizione |
| :- | :- |
| [`text_style`](/slides/python-net/it/aspose.slides/itextframeformat/text_style/) | Restituisce lo stile del testo.<br/>            Sola lettura [`ITextStyle`](/slides/python-net/it/aspose.slides/itextstyle). |
| [`margin_left`](/slides/python-net/it/aspose.slides/itextframeformat/margin_left/) | Restituisce o imposta il margine sinistro (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_right`](/slides/python-net/it/aspose.slides/itextframeformat/margin_right/) | Restituisce o imposta il margine destro (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_top`](/slides/python-net/it/aspose.slides/itextframeformat/margin_top/) | Restituisce o imposta il margine superiore (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`margin_bottom`](/slides/python-net/it/aspose.slides/itextframeformat/margin_bottom/) | Restituisce o imposta il margine inferiore (punti) in un TextFrame.<br/>            Lettura/scrittura **float**. |
| [`wrap_text`](/slides/python-net/it/aspose.slides/itextframeformat/wrap_text/) | **True** se il testo è a capo ai margini del TextFrame.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`anchoring_type`](/slides/python-net/it/aspose.slides/itextframeformat/anchoring_type/) | Restituisce o imposta l'ancoraggio verticale del testo in un TextFrame.<br/>            Lettura/scrittura [`TextAnchorType`](/slides/python-net/it/aspose.slides/textanchortype). |
| [`center_text`](/slides/python-net/it/aspose.slides/itextframeformat/center_text/) | Se NullableBool.True il testo deve essere centrato orizzontalmente nella casella.<br/>            Lettura/scrittura [`NullableBool`](/slides/python-net/it/aspose.slides/nullablebool). |
| [`text_vertical_type`](/slides/python-net/it/aspose.slides/itextframeformat/text_vertical_type/) | Determina l'orientamento del testo.<br/>            Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dall'angolo personalizzato<br/>            nella proprietà RotationAngle.<br/>            Lettura/scrittura [`TextVerticalType`](/slides/python-net/it/aspose.slides/textverticaltype). |
| [`autofit_type`](/slides/python-net/it/aspose.slides/itextframeformat/autofit_type/) | Restituisce o imposta la modalità di adattamento automatico del testo.<br/>            Lettura/scrittura [`TextAutofitType`](/slides/python-net/it/aspose.slides/textautofittype). |
| [`column_count`](/slides/python-net/it/aspose.slides/itextframeformat/column_count/) | Restituisce o imposta il numero di colonne nell'area del testo.<br/>            Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. <br/>            Il valore 0 indica valore non definito.<br/>            Lettura/scrittura **int**. |
| [`column_spacing`](/slides/python-net/it/aspose.slides/itextframeformat/column_spacing/) | Restituisce o imposta lo spazio tra le colonne di testo nell'area del testo (in punti). Questo dovrebbe essere applicato solo <br/>            quando è presente più di 1 colonna.<br/>            Questo valore deve essere un numero positivo. Altrimenti, il valore sarà impostato a zero. <br/>            Lettura/scrittura **float**. |
| [`three_d_format`](/slides/python-net/it/aspose.slides/itextframeformat/three_d_format/) | Restituisce l'oggetto ThreeDFormat che rappresenta le proprietà dell'effetto 3D per un testo.<br/>            Sola lettura [`IThreeDFormat`](/slides/python-net/it/aspose.slides/ithreedformat). |
| [`keep_text_flat`](/slides/python-net/it/aspose.slides/itextframeformat/keep_text_flat/) | Restituisce o imposta il mantenimento del testo fuori interamente dalla scena 3D.<br/>            Lettura/scrittura **bool**. |
| [`rotation_angle`](/slides/python-net/it/aspose.slides/itextframeformat/rotation_angle/) | Specifica la rotazione personalizzata che viene applicata al testo all'interno del riquadro. Se non<br/>            specificata, viene usata la rotazione della forma associata. Se è specificata, allora questa è<br/>            applicata indipendentemente dalla forma. Ciò significa che la forma può avere una rotazione applicata<br/>            oltre a quella del testo stesso.<br/>            Il valore risultante della rotazione visiva del testo, riassunto da questa proprietà e dal tipo<br/>            verticale predefinito nella proprietà TextVerticalType.<br/>            Lettura/scrittura **float**. |
| [`transform`](/slides/python-net/it/aspose.slides/itextframeformat/transform/) | Restituisce o imposta la forma di a capo del testo.<br/>            Lettura/scrittura [`TextShapeType`](/slides/python-net/it/aspose.slides/textshapetype). |

## Metodi

| Metodo | Descrizione |
| :- | :- |
| [`get_effective(self)`](/slides/python-net/it/aspose.slides/itextframeformat/get_effective/#) | Restituisce i dati di formattazione effettiva del frame di testo con l'ereditarietà applicata. |

### Vedi anche
* modulo [`aspose.slides`](/slides/python-net/it/aspose.slides)
* libreria [`Aspose.Slides`](/slides/python-net)