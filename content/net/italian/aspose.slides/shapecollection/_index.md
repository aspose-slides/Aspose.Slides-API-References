---
title: ShapeCollection
second_title: Aspose.Sildes per .NET API Reference
description: Rappresenta una raccolta di forme.
type: docs
weight: 9880
url: /it/aspose.slides/shapecollection/
---
## ShapeCollection classe

Rappresenta una raccolta di forme.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Ottiene il numero di elementi effettivamente contenuti nella raccolta. Solo lettura Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Ottiene l'elemento all'indice specificato. Solo lettura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Ottiene l'oggetto forma di gruppo genitore per la raccolta di forme. Solo lettura [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Restituisce una radice di sincronizzazione. Solo lettura Object. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Crea un nuovo fotogramma audio collegato a una traccia CD e lo aggiunge alla fine della raccolta di forme. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crea un nuovo fotogramma audio e lo aggiunge alla fine della raccolta di forme utilizzando un oggetto audio esistente dall'elenco Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crea un nuovo fotogramma audio con un file WAV incorporato e lo aggiunge alla fine della raccolta di forme. L'audio incorporato viene aggiunto alla raccolta Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Crea un nuovo fotogramma audio collegato a un file audio esterno e lo aggiunge alla fine della raccolta di forme. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della raccolta di forme. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crea una nuova forma automatica e la aggiunge alla fine della raccolta di forme, opzionalmente inizializzandola con la formattazione del modello predefinito. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La forma clonata conserva la posizione e le dimensioni originali. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La nuova forma conserva la larghezza e l'altezza di *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crea una nuova forma connettore con stile del modello predefinito e la aggiunge alla fine della raccolta di forme. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crea una nuova forma connettore e la aggiunge alla fine della raccolta di forme, opzionalmente applicando lo stile del modello predefinito. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crea una nuova forma di gruppo vuota e la aggiunge alla fine della raccolta di forme. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della raccolta di forme. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crea una nuova forma automatica rettangolare per ospitare contenuti matematici e la aggiunge alla fine della raccolta di forme. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuovo riquadro oggetto OLE e lo aggiunge alla fine della raccolta di forme. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crea un nuovo riquadro oggetto OLE e lo aggiunge alla fine della raccolta di forme. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crea un nuovo riquadro immagine contenente l'immagine specificata e lo aggiunge alla fine della raccolta di forme. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crea un nuovo riquadro Section Zoom e lo aggiunge alla fine della raccolta di forme. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crea un nuovo riquadro Section Zoom con un'immagine predefinita e lo aggiunge alla fine della raccolta di forme. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crea un diagramma SmartArt e lo aggiunge alla fine della raccolta di forme. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Crea un nuovo riquadro Summary Zoom e lo aggiunge alla fine della raccolta di forme. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crea una nuova tabella e la aggiunge alla fine della raccolta di forme. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crea un nuovo riquadro video e lo aggiunge alla fine della raccolta di forme. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crea un nuovo riquadro video e lo aggiunge alla fine della raccolta di forme. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crea un nuovo riquadro Zoom e lo aggiunge alla fine della raccolta di forme. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crea un nuovo riquadro Zoom e lo aggiunge alla fine della raccolta di forme. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Rimuove tutte le forme dalla raccolta di forme. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copia tutti gli elementi della raccolta nell'array specificato. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Restituisce un enumeratore che scorre la raccolta. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Restituisce l'indice base zero della prima occorrenza della forma specificata nella raccolta. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Crea un nuovo fotogramma audio collegato a una traccia CD e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crea un nuovo fotogramma audio e lo inserisce nella raccolta di forme all'indice specificato utilizzando un oggetto audio esistente dall'elenco Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crea un nuovo fotogramma audio con un file WAV incorporato e lo inserisce nella raccolta di forme all'indice specificato. L'audio incorporato viene aggiunto alla raccolta Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crea un nuovo fotogramma audio collegato a un file audio esterno e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, applicando la formattazione predefinita del modello. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La forma clonata conserva la posizione e le dimensioni originali. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La nuova forma conserva la larghezza e l'altezza di *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, applicando lo stile predefinito del modello. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, opzionalmente applicando lo stile predefinito del modello. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crea una nuova forma di gruppo vuota e la inserisce nella raccolta di forme all'indice specificato. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuovo riquadro oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crea un nuovo riquadro oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crea un nuovo riquadro immagine contenente l'immagine specificata e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crea un nuovo riquadro Section Zoom e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crea un nuovo riquadro Section Zoom con un'immagine predefinita e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crea un nuovo riquadro Summary Zoom e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crea una nuova tabella e la inserisce nella raccolta di forme all'indice specificato. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crea un nuovo riquadro video e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crea un nuovo riquadro Zoom e lo inserisce nella raccolta di forme all'indice specificato. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crea un nuovo riquadro Zoom con un'immagine predefinita e lo inserisce nella raccolta di forme all'indice specificato. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Rimuove la prima occorrenza della forma specificata dalla raccolta di forme. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Rimuove la forma all'indice specificato dalla raccolta di forme. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Sposta la forma specificata in una nuova posizione all'interno della raccolta di forme. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Sposta le forme specificate all'interno della raccolta di forme, posizionandole a partire dall'indice fornito. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crea e restituisce un array che contiene tutte le forme. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato. |

### Vedi anche

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [GroupShape](../groupshape)
* interfaccia [IShapeCollection](../ishapecollection)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->