---
title: TextFrameFormat
second_title: Aspose.Sildes per .NET Riferimento API
description: Contiene le proprietà formatTextFrameFormatting dei TextFrames.
type: docs
weight: 10940
url: /it/aspose.slides/textframeformat/
---
## TextFrameFormat classe

Contiene le proprietà formatTextFrameFormatting del TextFrame.

```csharp
public sealed class TextFrameFormat : PVIObject, IChartTextBlockFormat, ITextFrameFormat
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TextFrameFormat](textframeformat)() | Inizializza una nuova istanza di classe [`TextFrameFormat`](../textframeformat). |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AnchoringType](../../aspose.slides/textframeformat/anchoringtype) { get; set; } | Restituisce o imposta il testo di ancoraggio verticale in un TextFrame. Lettura/scrittura [`TextAnchorType`](../textanchortype). |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Consente di ottenere l'interfaccia base IPresentationComponent. Sola lettura [`IPresentationComponent`](../ipresentationcomponent). |
| [AutofitType](../../aspose.slides/textframeformat/autofittype) { get; set; } | Restituisce o imposta la modalità di adattamento automatico del testo. Lettura/scrittura [`TextAutofitType`](../textautofittype). |
| [CenterText](../../aspose.slides/textframeformat/centertext) { get; set; } | Se NullableBool.True il testo deve essere centrato orizzontalmente nella casella. Lettura/scrittura [`NullableBool`](../nullablebool). |
| [ColumnCount](../../aspose.slides/textframeformat/columncount) { get; set; } | Restituisce o imposta il numero di colonne nell'area di testo. Questo valore deve essere un numero positivo. In caso contrario, il valore verrà impostato a zero. Il valore 0 indica valore non definito. Lettura/scrittura Int32. |
| [ColumnSpacing](../../aspose.slides/textframeformat/columnspacing) { get; set; } | Restituisce o imposta lo spazio tra le colonne di testo nell'area di testo (in punti). Questo dovrebbe applicarsi solo quando è presente più di una colonna. Questo valore deve essere un numero positivo. In caso contrario, il valore verrà impostato a zero. Lettura/scrittura Double. |
| [KeepTextFlat](../../aspose.slides/textframeformat/keeptextflat) { get; set; } | Restituisce o imposta il mantenimento del testo piatto anche se è stato applicato un effetto di rotazione 3-D. Lettura/scrittura Boolean. |
| [MarginBottom](../../aspose.slides/textframeformat/marginbottom) { get; set; } | Restituisce o imposta il margine inferiore (punti) in un TextFrame. Lettura/scrittura Double. |
| [MarginLeft](../../aspose.slides/textframeformat/marginleft) { get; set; } | Restituisce o imposta il margine sinistro (punti) in un TextFrame. Lettura/scrittura Double. |
| [MarginRight](../../aspose.slides/textframeformat/marginright) { get; set; } | Restituisce o imposta il margine destro (punti) in un TextFrame. Lettura/scrittura Double. |
| [MarginTop](../../aspose.slides/textframeformat/margintop) { get; set; } | Restituisce o imposta il margine superiore (punti) in un TextFrame. Lettura/scrittura Double. |
| [RotationAngle](../../aspose.slides/textframeformat/rotationangle) { get; set; } | Specifica la rotazione personalizzata che viene applicata al testo all'interno della casella di delimitazione. Se non specificata, viene utilizzata la rotazione della forma associata. Se specificata, viene applicata indipendentemente dalla forma. Cioè la forma può avere una rotazione applicata in aggiunta alla rotazione del testo stesso. Il valore risultante della rotazione visiva del testo è riassunto da questa proprietà e dal tipo verticale predefinito nella proprietà TextVerticalType. Lettura/scrittura Single. |
| [TextVerticalType](../../aspose.slides/textframeformat/textverticaltype) { get; set; } | Determina l'orientamento del testo. Il valore risultante della rotazione visiva del testo è riassunto da questa proprietà e dall'angolo personalizzato nella proprietà RotationAngle. Lettura/scrittura [`TextVerticalType`](../textverticaltype). |
| [ThreeDFormat](../../aspose.slides/textframeformat/threedformat) { get; } | Restituisce l'oggetto ThreeDFormat che rappresenta le proprietà dell'effetto 3D per un testo. Sola lettura [`IThreeDFormat`](../ithreedformat). |
| [Transform](../../aspose.slides/textframeformat/transform) { get; set; } | Restituisce o imposta la forma di avvolgimento del testo. Lettura/scrittura [`TextShapeType`](../textshapetype). |
| [WrapText](../../aspose.slides/textframeformat/wraptext) { get; set; } | True se il testo è avvolto ai margini del TextFrame. Lettura/scrittura [`NullableBool`](../nullablebool). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Confronta con l'oggetto specificato. |
| [GetEffective](../../aspose.slides/textframeformat/geteffective)() | Restituisce i dati di formattazione effettiva del frame di testo con l'ereditarietà applicata. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Restituisce il codice hash. |

### Vedi anche

* classe [PVIObject](../pviobject)
* interfaccia [IChartTextBlockFormat](../../aspose.slides.charts/icharttextblockformat)
* interfaccia [ITextFrameFormat](../itextframeformat)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->