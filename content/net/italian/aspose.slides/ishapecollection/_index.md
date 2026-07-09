---
title: IShapeCollection
second_title: Aspose.Sildes per .NET Riferimento API
description: Rappresenta una raccolta di forme.
type: docs
weight: 6980
url: /it/aspose.slides/ishapecollection/
---
## IShapeCollection interfaccia

Rappresenta una raccolta di forme.

```csharp
public interface IShapeCollection : IGenericCollection<IShape>
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Item](../../aspose.slides/ishapecollection/item) { get; } | Restituisce l'elemento all'indice specificato. Solo lettura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/ishapecollection/parentgroup) { get; } | Restituisce l'oggetto gruppo di forme genitore per la raccolta di forme. Solo lettura [`IGroupShape`](../igroupshape). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/ishapecollection/addaudioframecd)(float, float, float, float) | Crea un nuovo fotogramma audio collegato a una traccia CD e lo aggiunge alla fine della raccolta di forme. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crea un nuovo fotogramma audio e lo aggiunge alla fine della raccolta di forme utilizzando un oggetto audio esistente dall'elenco Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/ishapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crea un nuovo fotogramma audio con un file WAV incorporato e lo aggiunge alla fine della raccolta di forme. L'audio incorporato viene aggiunto alla raccolta Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/ishapecollection/addaudioframelinked)(float, float, float, float, string) | Crea un nuovo fotogramma audio collegato a un file audio esterno e lo aggiunge alla fine della raccolta di forme. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della raccolta di forme. |
| [AddAutoShape](../../aspose.slides/ishapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crea una nuova forma automatica e la aggiunge alla fine della raccolta di forme, opzionalmente inizializzandola con la formattazione predefinita del modello. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme. |
| [AddChart](../../aspose.slides/ishapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone)(IShape) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La forma clonata conserva la posizione e le dimensioni dell'originale. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_1)(IShape, float, float) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La nuova forma conserva la larghezza e l'altezza della *sourceShape*. |
| [AddClone](../../aspose.slides/ishapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crea una nuova forma connettore con stile predefinito del modello e la aggiunge alla fine della raccolta di forme. |
| [AddConnector](../../aspose.slides/ishapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crea una nuova forma connettore e la aggiunge alla fine della raccolta di forme, opzionalmente applicando lo stile predefinito del modello. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape)() | Crea una nuova forma di gruppo vuota e la aggiunge alla fine della raccolta di forme. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte. |
| [AddGroupShape](../../aspose.slides/ishapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della raccolta di forme. |
| [AddMathShape](../../aspose.slides/ishapecollection/addmathshape)(float, float, float, float) | Crea una nuova forma automatica rettangolare per contenere contenuto matematico e la aggiunge alla fine della raccolta di forme. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della raccolta di forme. |
| [AddOleObjectFrame](../../aspose.slides/ishapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della raccolta di forme. |
| [AddPictureFrame](../../aspose.slides/ishapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crea un nuovo frame immagine contenente l'immagine specificata e lo aggiunge alla fine della raccolta di forme. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crea un nuovo frame Section Zoom e lo aggiunge alla fine della raccolta di forme. |
| [AddSectionZoomFrame](../../aspose.slides/ishapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crea un nuovo frame Section Zoom con un'immagine predefinita e lo aggiunge alla fine della raccolta di forme. |
| [AddSmartArt](../../aspose.slides/ishapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crea un diagramma SmartArt e lo aggiunge alla fine della raccolta di forme. |
| [AddSummaryZoomFrame](../../aspose.slides/ishapecollection/addsummaryzoomframe)(float, float, float, float) | Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della raccolta di forme. |
| [AddTable](../../aspose.slides/ishapecollection/addtable)(float, float, double[], double[]) | Crea una nuova tabella e la aggiunge alla fine della raccolta di forme. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crea un nuovo frame video e lo aggiunge alla fine della raccolta di forme. |
| [AddVideoFrame](../../aspose.slides/ishapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crea un nuovo frame video e lo aggiunge alla fine della raccolta di forme. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme. |
| [AddZoomFrame](../../aspose.slides/ishapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme, includendo un'immagine predefinita. |
| [Clear](../../aspose.slides/ishapecollection/clear)() | Rimuove tutte le forme dalla raccolta di forme. |
| [IndexOf](../../aspose.slides/ishapecollection/indexof)(IShape) | Restituisce l'indice base zero della prima occorrenza della forma specificata nella raccolta. |
| [InsertAudioFrameCD](../../aspose.slides/ishapecollection/insertaudioframecd)(int, float, float, float, float) | Crea un nuovo fotogramma audio collegato a una traccia CD e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crea un nuovo fotogramma audio e lo inserisce nella raccolta di forme all'indice specificato utilizzando un oggetto audio esistente dall'elenco Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/ishapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crea un nuovo fotogramma audio con un file WAV incorporato e lo inserisce nella raccolta di forme all'indice specificato. L'audio incorporato viene aggiunto alla raccolta Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/ishapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crea un nuovo fotogramma audio collegato a un file audio esterno e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, applicando la formattazione predefinita del modello. |
| [InsertAutoShape](../../aspose.slides/ishapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertChart](../../aspose.slides/ishapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone)(int, IShape) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La forma clonata conserva la posizione e le dimensioni dell'originale. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La nuova forma conserva la larghezza e l'altezza della *sourceShape*. |
| [InsertClone](../../aspose.slides/ishapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, applicando lo stile predefinito del modello. |
| [InsertConnector](../../aspose.slides/ishapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, opzionalmente applicando lo stile predefinito del modello. |
| [InsertGroupShape](../../aspose.slides/ishapecollection/insertgroupshape)(int) | Crea una nuova forma di gruppo vuota e la inserisce nella raccolta di forme all'indice specificato. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuovo frame oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertOleObjectFrame](../../aspose.slides/ishapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crea un nuovo frame oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertPictureFrame](../../aspose.slides/ishapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crea un nuovo frame immagine contenente l'immagine specificata e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crea un nuovo frame Section Zoom e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertSectionZoomFrame](../../aspose.slides/ishapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crea un nuovo frame Section Zoom con un'immagine predefinita e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertSummaryZoomFrame](../../aspose.slides/ishapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crea un nuovo frame Summary Zoom e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertTable](../../aspose.slides/ishapecollection/inserttable)(int, float, float, double[], double[]) | Crea una nuova tabella e la inserisce nella raccolta di forme all'indice specificato. |
| [InsertVideoFrame](../../aspose.slides/ishapecollection/insertvideoframe)(int, float, float, float, float, string) | Crea un nuovo frame video e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crea un nuovo frame Zoom e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertZoomFrame](../../aspose.slides/ishapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crea un nuovo frame Zoom con un'immagine predefinita e lo inserisce nella raccolta di forme all'indice specificato. |
| [Remove](../../aspose.slides/ishapecollection/remove)(IShape) | Rimuove la prima occorrenza della forma specificata dalla raccolta di forme. |
| [RemoveAt](../../aspose.slides/ishapecollection/removeat)(int) | Rimuove la forma all'indice specificato dalla raccolta di forme. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder)(int, IShape) | Sposta la forma specificata in una nuova posizione all'interno della raccolta di forme. |
| [Reorder](../../aspose.slides/ishapecollection/reorder#reorder_1)(int, params IShape[]) | Sposta le forme specificate all'interno della raccolta di forme, posizionandole a partire dall'indice indicato. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray)() | Crea e restituisce un array che contiene tutte le forme. |
| [ToArray](../../aspose.slides/ishapecollection/toarray#toarray_1)(int, int) | Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato. |

### Vedi anche

* interfaccia [IGenericCollection&lt;T&gt;](../igenericcollection-1)
* interfaccia [IShape](../ishape)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->