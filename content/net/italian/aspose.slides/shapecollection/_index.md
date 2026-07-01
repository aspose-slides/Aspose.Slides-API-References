---
title: ShapeCollection
second_title: Riferimento API di Aspose.Sildes per .NET
description: Rappresenta una collezione di forme.
type: docs
weight: 9840
url: /it/aspose.slides/shapecollection/
---
## ShapeCollection classe

Rappresenta una collezione di forme.

```csharp
public sealed class ShapeCollection : DomObject<GroupShape>, IShapeCollection
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Count](../../aspose.slides/shapecollection/count) { get; } | Restituisce il numero di elementi effettivamente contenuti nella collezione. Solo lettura Int32. |
| [IsSynchronized](../../aspose.slides/shapecollection/issynchronized) { get; } | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Solo lettura Boolean. |
| [Item](../../aspose.slides/shapecollection/item) { get; } | Restituisce l'elemento all'indice specificato. Solo lettura [`IShape`](../ishape). |
| [ParentGroup](../../aspose.slides/shapecollection/parentgroup) { get; } | Restituisce l'oggetto forma di gruppo padre per la collezione di forme. Solo lettura [`IGroupShape`](../igroupshape). |
| [SyncRoot](../../aspose.slides/shapecollection/syncroot) { get; } | Restituisce una radice di sincronizzazione. Solo lettura Object. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [AddAudioFrameCD](../../aspose.slides/shapecollection/addaudioframecd)(float, float, float, float) | Crea un nuovo frame audio collegato a una traccia CD e lo aggiunge alla fine della collezione di forme. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded)(float, float, float, float, IAudio) | Crea un nuovo frame audio e lo aggiunge alla fine della collezione di forme utilizzando un oggetto audio esistente dall'elenco Presentation.Audios. |
| [AddAudioFrameEmbedded](../../aspose.slides/shapecollection/addaudioframeembedded#addaudioframeembedded_1)(float, float, float, float, Stream) | Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della collezione di forme. L'audio incorporato viene aggiunto alla collezione Presentation.Audios. |
| [AddAudioFrameLinked](../../aspose.slides/shapecollection/addaudioframelinked)(float, float, float, float, string) | Crea un nuovo frame audio collegato a un file audio esterno e lo aggiunge alla fine della collezione di forme. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape)(ShapeType, float, float, float, float) | Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della collezione di forme. |
| [AddAutoShape](../../aspose.slides/shapecollection/addautoshape#addautoshape_1)(ShapeType, float, float, float, float, bool) | Crea una nuova forma automatica e la aggiunge alla fine della collezione di forme, opzionalmente inizializzandola con la formattazione predefinita del modello. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart)(ChartType, float, float, float, float) | Crea un nuovo grafico, lo inizializza con dati e impostazioni di serie di esempio, e lo aggiunge alla fine della collezione di forme. |
| [AddChart](../../aspose.slides/shapecollection/addchart#addchart_1)(ChartType, float, float, float, float, bool) | Crea un nuovo grafico, lo inizializza con dati e impostazioni di serie di esempio, e lo aggiunge alla fine della collezione di forme. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone)(IShape) | Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. La forma clonata mantiene la posizione e le dimensioni dell'originale. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_1)(IShape, float, float) | Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. La nuova forma mantiene la larghezza e l'altezza della *sourceShape*. |
| [AddClone](../../aspose.slides/shapecollection/addclone#addclone_2)(IShape, float, float, float, float) | Crea una copia della forma specificata e la aggiunge alla fine della collezione di forme. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector)(ShapeType, float, float, float, float) | Crea una nuova forma connettore con stile predefinito del modello e la aggiunge alla fine della collezione di forme. |
| [AddConnector](../../aspose.slides/shapecollection/addconnector#addconnector_1)(ShapeType, float, float, float, float, bool) | Crea una nuova forma connettore e la aggiunge alla fine della collezione di forme, eventualmente applicando lo stile predefinito del modello. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape)() | Crea una nuova forma di gruppo vuota e la aggiunge alla fine della collezione di forme. Il frame del gruppo si adeguerà automaticamente per contenere tutte le forme aggiunte. |
| [AddGroupShape](../../aspose.slides/shapecollection/addgroupshape#addgroupshape_1)(ISvgImage, float, float, float, float) | Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della collezione di forme. |
| [AddMathShape](../../aspose.slides/shapecollection/addmathshape)(float, float, float, float) | Crea una nuova forma rettangolare automatica per ospitare contenuti matematici e la aggiunge alla fine della collezione di forme. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe)(float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della collezione di forme. |
| [AddOleObjectFrame](../../aspose.slides/shapecollection/addoleobjectframe#addoleobjectframe_1)(float, float, float, float, string, string) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della collezione di forme. |
| [AddPictureFrame](../../aspose.slides/shapecollection/addpictureframe)(ShapeType, float, float, float, float, IPPImage) | Crea un nuovo frame immagine contenente l'immagine specificata e lo aggiunge alla fine della collezione di forme. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe)(float, float, float, float, ISection) | Crea un nuovo frame Section Zoom e lo aggiunge alla fine della collezione di forme. |
| [AddSectionZoomFrame](../../aspose.slides/shapecollection/addsectionzoomframe#addsectionzoomframe_1)(float, float, float, float, ISection, IPPImage) | Crea un nuovo frame Section Zoom con un'immagine predefinita e lo aggiunge alla fine della collezione di forme. |
| [AddSmartArt](../../aspose.slides/shapecollection/addsmartart)(float, float, float, float, SmartArtLayoutType) | Crea un diagramma SmartArt e lo aggiunge alla fine della collezione di forme. |
| [AddSummaryZoomFrame](../../aspose.slides/shapecollection/addsummaryzoomframe)(float, float, float, float) | Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della collezione di forme. |
| [AddTable](../../aspose.slides/shapecollection/addtable)(float, float, double[], double[]) | Crea una nuova tabella e la aggiunge alla fine della collezione di forme. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe)(float, float, float, float, IVideo) | Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme. |
| [AddVideoFrame](../../aspose.slides/shapecollection/addvideoframe#addvideoframe_1)(float, float, float, float, string) | Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe)(float, float, float, float, ISlide) | Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme. |
| [AddZoomFrame](../../aspose.slides/shapecollection/addzoomframe#addzoomframe_1)(float, float, float, float, ISlide, IPPImage) | Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme. |
| [Clear](../../aspose.slides/shapecollection/clear)() | Rimuove tutte le forme dalla collezione di forme. |
| [CopyTo](../../aspose.slides/shapecollection/copyto)(Array, int) | Copia tutti gli elementi dalla collezione nell'array specificato. |
| [GetEnumerator](../../aspose.slides/shapecollection/getenumerator)() | Restituisce un enumeratore che itera attraverso la collezione. |
| [IndexOf](../../aspose.slides/shapecollection/indexof)(IShape) | Restituisce l'indice basato su zero della prima occorrenza della forma specificata nella collezione. |
| [InsertAudioFrameCD](../../aspose.slides/shapecollection/insertaudioframecd)(int, float, float, float, float) | Crea un nuovo frame audio collegato a una traccia CD e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded)(int, float, float, float, float, IAudio) | Crea un nuovo frame audio e lo inserisce nella collezione di forme all'indice specificato utilizzando un oggetto audio esistente dall'elenco Presentation.Audios. |
| [InsertAudioFrameEmbedded](../../aspose.slides/shapecollection/insertaudioframeembedded#insertaudioframeembedded_1)(int, float, float, float, float, Stream) | Crea un nuovo frame audio con un file WAV incorporato e lo inserisce nella collezione di forme all'indice specificato. L'audio incorporato viene aggiunto alla collezione Presentation.Audios. |
| [InsertAudioFrameLinked](../../aspose.slides/shapecollection/insertaudioframelinked)(int, float, float, float, float, string) | Crea un nuovo frame audio collegato a un file audio esterno e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape)(int, ShapeType, float, float, float, float) | Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione predefinita del modello. |
| [InsertAutoShape](../../aspose.slides/shapecollection/insertautoshape#insertautoshape_1)(int, ShapeType, float, float, float, float, bool) | Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart)(ChartType, float, float, float, float, int) | Crea un nuovo grafico, lo inizializza con dati e impostazioni di serie di esempio, e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertChart](../../aspose.slides/shapecollection/insertchart#insertchart_1)(ChartType, float, float, float, float, int, bool) | Crea un nuovo grafico, lo inizializza con dati e impostazioni di serie di esempio, e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone)(int, IShape) | Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato. La forma clonata mantiene la posizione e le dimensioni dell'originale. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_1)(int, IShape, float, float) | Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato. La nuova forma mantiene la larghezza e l'altezza della *sourceShape*. |
| [InsertClone](../../aspose.slides/shapecollection/insertclone#insertclone_2)(int, IShape, float, float, float, float) | Crea una copia della forma specificata e la inserisce nella collezione di forme all'indice specificato. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector)(int, ShapeType, float, float, float, float) | Crea una nuova forma connettore e la inserisce nella collezione di forme all'indice specificato, applicando lo stile predefinito del modello. |
| [InsertConnector](../../aspose.slides/shapecollection/insertconnector#insertconnector_1)(int, ShapeType, float, float, float, float, bool) | Crea una nuova forma connettore e la inserisce nella collezione di forme all'indice specificato, opzionalmente applicando lo stile predefinito del modello. |
| [InsertGroupShape](../../aspose.slides/shapecollection/insertgroupshape)(int) | Crea una nuova forma di gruppo vuota e la inserisce nella collezione di forme all'indice specificato. Il frame del gruppo si adeguerà automaticamente per contenere tutte le forme aggiunte. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe)(int, float, float, float, float, IOleEmbeddedDataInfo) | Crea un nuovo frame oggetto OLE e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertOleObjectFrame](../../aspose.slides/shapecollection/insertoleobjectframe#insertoleobjectframe_1)(int, float, float, float, float, string, string) | Crea un nuovo frame oggetto OLE e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertPictureFrame](../../aspose.slides/shapecollection/insertpictureframe)(int, ShapeType, float, float, float, float, IPPImage) | Crea un nuovo frame immagine contenente l'immagine specificata e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe)(int, float, float, float, float, ISection) | Crea un nuovo frame Section Zoom e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertSectionZoomFrame](../../aspose.slides/shapecollection/insertsectionzoomframe#insertsectionzoomframe_1)(int, float, float, float, float, ISection, IPPImage) | Crea un nuovo frame Section Zoom con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertSummaryZoomFrame](../../aspose.slides/shapecollection/insertsummaryzoomframe)(int, float, float, float, float) | Crea un nuovo frame Summary Zoom e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertTable](../../aspose.slides/shapecollection/inserttable)(int, float, float, double[], double[]) | Crea una nuova tabella e la inserisce nella collezione di forme all'indice specificato. |
| [InsertVideoFrame](../../aspose.slides/shapecollection/insertvideoframe)(int, float, float, float, float, string) | Crea un nuovo frame video e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe)(int, float, float, float, float, ISlide) | Crea un nuovo frame Zoom e lo inserisce nella collezione di forme all'indice specificato. |
| [InsertZoomFrame](../../aspose.slides/shapecollection/insertzoomframe#insertzoomframe_1)(int, float, float, float, float, ISlide, IPPImage) | Crea un nuovo frame Zoom con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato. |
| [Remove](../../aspose.slides/shapecollection/remove)(IShape) | Rimuove la prima occorrenza della forma specificata dalla collezione di forme. |
| [RemoveAt](../../aspose.slides/shapecollection/removeat)(int) | Rimuove la forma all'indice specificato dalla collezione di forme. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder)(int, IShape) | Sposta la forma specificata in una nuova posizione all'interno della collezione di forme. |
| [Reorder](../../aspose.slides/shapecollection/reorder#reorder_1)(int, params IShape[]) | Sposta le forme specificate all'interno della collezione di forme, posizionandole a partire dall'indice fornito. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray)() | Crea e restituisce un array che contiene tutte le forme. |
| [ToArray](../../aspose.slides/shapecollection/toarray#toarray_1)(int, int) | Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato. |

### Vedi anche

* classe [DomObject&lt;TParent&gt;](../domobject-1)
* classe [GroupShape](../groupshape)
* interfaccia [IShapeCollection](../ishapecollection)
* spazio dei nomi [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->