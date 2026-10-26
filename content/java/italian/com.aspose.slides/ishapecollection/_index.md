---
title: IShapeCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di forme.
type: docs
url: /it/com.aspose.slides/ishapecollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Rappresenta una collezione di shape.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [getParentGroup()](#getParentGroup--) | Ottiene l'oggetto parent group shape per la collezione di shapes. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della shape collection. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della shape collection. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Crea un diagramma SmartArt e lo aggiunge alla fine della shape collection. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella shape collection all'indice specificato. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella shape collection all'indice specificato. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuovo OLE object frame e lo aggiunge alla fine della shape collection. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuovo OLE object frame e lo aggiunge alla fine della shape collection. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuovo OLE object frame e lo inserisce nella shape collection all'indice specificato. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuovo OLE object frame e lo inserisce nella shape collection all'indice specificato. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuovo Zoom frame e lo aggiunge alla fine della shape collection. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuovo Zoom frame e lo aggiunge alla fine della shape collection. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuovo Zoom frame e lo inserisce nella shape collection all'indice specificato. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuovo Zoom frame con immagine predefinita e lo inserisce nella shape collection all'indice specificato. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuovo Section Zoom frame e lo aggiunge alla fine della shape collection. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuovo Section Zoom frame con immagine predefinita e lo aggiunge alla fine della shape collection. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuovo Section Zoom frame e lo inserisce nella shape collection all'indice specificato. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuovo Section Zoom frame con immagine predefinita e lo inserisce nella shape collection all'indice specificato. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Crea un nuovo Summary Zoom frame e lo aggiunge alla fine della shape collection. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Crea un nuovo Summary Zoom frame e lo inserisce nella shape collection all'indice specificato. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Crea un nuovo video frame e lo aggiunge alla fine della shape collection. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Crea un nuovo video frame e lo aggiunge alla fine della shape collection. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Crea un nuovo video frame e lo inserisce nella shape collection all'indice specificato. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Crea un nuovo audio frame collegato a una traccia CD e lo aggiunge alla fine della shape collection. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Crea un nuovo audio frame collegato a una traccia CD e lo inserisce nella shape collection all'indice specificato. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Crea un nuovo audio frame collegato a un file audio esterno e lo aggiunge alla fine della shape collection. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Crea un nuovo audio frame collegato a un file audio esterno e lo inserisce nella shape collection all'indice specificato. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Crea un nuovo audio frame con file WAV incorporato e lo aggiunge alla fine della shape collection. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuovo audio frame e lo aggiunge alla fine della shape collection usando un oggetto audio esistente dalla lista Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Crea un nuovo audio frame con file WAV incorporato e lo inserisce nella shape collection all'indice specificato. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuovo audio frame e lo inserisce nella shape collection all'indice specificato usando un oggetto audio esistente dalla lista Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Restituisce l'indice basato su zero della prima occorrenza della shape specificata nella collezione. |
| [toArray()](#toArray--) | Crea e restituisce un array che contiene tutte le shape. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array che contiene tutte le shape nell'intervallo specificato. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Sposta la shape specificata in una nuova posizione all'interno della shape collection. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Sposta le shape specificate all'interno della shape collection, posizionandole a partire dall'indice fornito. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Crea una nuova auto shape con formattazione predefinita e la aggiunge alla fine della shape collection. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Crea una nuova auto shape e la aggiunge alla fine della shape collection, opzionalmente inizializzandola con la formattazione predefinita del modello. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Crea una nuova auto shape rettangolare per contenere contenuti matematici e la aggiunge alla fine della shape collection. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Crea una nuova auto shape e la inserisce nella shape collection all'indice specificato, applicando la formattazione predefinita del modello. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Crea una nuova auto shape e la inserisce nella shape collection all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello. |
| [addGroupShape()](#addGroupShape--) | Crea una nuova group shape vuota e la aggiunge alla fine della shape collection. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Crea una nuova group shape, converte l'immagine SVG specificata in shape individuali, e aggiunge il gruppo risultante alla fine della shape collection. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Crea una nuova group shape vuota e la inserisce nella shape collection all'indice specificato. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Crea una nuova connector shape con stile predefinito del modello e la aggiunge alla fine della shape collection. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Crea una nuova connector shape e la aggiunge alla fine della shape collection, opzionalmente applicando lo stile predefinito del modello. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Crea una nuova connector shape e la inserisce nella shape collection all'indice specificato, applicando lo stile predefinito del modello. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Crea una nuova connector shape e la inserisce nella shape collection all'indice specificato, opzionalmente applicando lo stile predefinito del modello. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuovo picture frame contenente l'immagine specificata e lo aggiunge alla fine della shape collection. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuovo picture frame contenente l'immagine specificata e lo inserisce nella shape collection all'indice specificato. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Crea una nuova table e la aggiunge alla fine della shape collection. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Crea una nuova table e la inserisce nella shape collection all'indice specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la shape all'indice specificato dalla shape collection. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Rimuove la prima occorrenza della shape specificata dalla shape collection. |
| [clear()](#clear--) | Rimuove tutte le shape dalla shape collection. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia della shape specificata e la aggiunge alla fine della shape collection. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Crea una copia della shape specificata e la aggiunge alla fine della shape collection. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Crea una copia della shape specificata e la aggiunge alla fine della shape collection. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia della shape specificata e la inserisce nella shape collection all'indice specificato. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Crea una copia della shape specificata e la inserisce nella shape collection all'indice specificato. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Crea una copia della shape specificata e la inserisce nella shape collection all'indice specificato. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Ottiene l'elemento all'indice specificato. Sola lettura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Ottiene l'oggetto parent group shape per la collezione di shapes. Sola lettura [IGroupShape](../../com.aspose.slides/igroupshape).

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della shape collection.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di chart da aggiungere. |
| x | float | La coordinata x del nuovo chart, in punti. |
| y | float | La coordinata y del nuovo chart, in punti. |
| width | float | La larghezza del chart, in punti. |
| height | float | L'altezza del chart, in punti. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart) creato.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della shape collection.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di chart da aggiungere. |
| x | float | La coordinata x del nuovo chart, in punti. |
| y | float | La coordinata y del nuovo chart, in punti. |
| width | float | La larghezza del chart, in punti. |
| height | float | L'altezza del chart, in punti. |
| initWithSample | boolean | True per inizializzare il nuovo chart con dati di serie di esempio e impostazioni; false per creare il chart senza serie e solo con impostazioni minime, rendendo la creazione più veloce. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart) creato.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Crea un diagramma SmartArt e lo aggiunge alla fine della shape collection.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del frame del diagramma, in punti. |
| y | float | La coordinata y del frame del diagramma, in punti. |
| width | float | La larghezza del frame del diagramma, in punti. |
| height | float | L'altezza del frame del diagramma, in punti. |
| layoutType | int | Il tipo di layout SmartArt. |

**Restituisce:**
[ISmartArt](../../com.aspose.slides/ismartart) - Il nuovo [ISmartArt](../../com.aspose.slides/ismartart) creato.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella shape collection all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di chart da creare. |
| x | float | La coordinata x del nuovo chart, in punti. |
| y | float | La coordinata y del nuovo chart, in punti. |
| width | float | La larghezza del nuovo chart, in punti. |
| height | float | L'altezza del nuovo chart, in punti. |
| index | int | L'indice basato su zero al quale inserire il nuovo chart nella shape collection. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart) creato.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Crea un nuovo chart, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella shape collection all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di chart da creare. |
| x | float | La coordinata x del nuovo chart, in punti. |
| y | float | La coordinata y del nuovo chart, in punti. |
| width | float | La larghezza del nuovo chart, in punti. |
| height | float | L'altezza del nuovo chart, in punti. |
| index | int | L'indice basato su zero al quale inserire il nuovo chart nella shape collection. |
| initWithSample | boolean | True per inizializzare il nuovo chart con dati di serie di esempio e impostazioni; false per creare il chart senza serie e solo con impostazioni minime. |
| initWithSample | boolean | True per inizializzare il nuovo grafico con dati e impostazioni di serie di esempio; false per creare il grafico senza serie e solo con impostazioni minime, il che rende la creazione più veloce. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart) creato.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L’altezza del nuovo frame OLE, in punti. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Le informazioni dei dati OLE incorporati ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) creato.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L’altezza del nuovo frame OLE, in punti. |
| className | java.lang.String | Il nome della classe dell’oggetto OLE. |
| path | java.lang.String | Il percorso al file collegato.  

Questo percorso è memorizzato così com’è nella presentazione. Se viene specificato un percorso relativo, il file sarà inaccessibile aprendo la presentazione da una directory diversa. |

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) creato.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuovo frame oggetto OLE e lo inserisce nella raccolta di forme all’indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero a cui inserire il frame oggetto OLE. |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L’altezza del nuovo frame OLE, in punti. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Le informazioni dei dati OLE incorporati ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) creato.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Crea un nuovo frame oggetto OLE e lo inserisce nella raccolta di forme all’indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero a cui inserire il frame oggetto OLE. |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L’altezza del nuovo frame OLE, in punti. |
| className | java.lang.String | Il nome della classe dell’oggetto OLE. |
| path | java.lang.String | Il percorso al file collegato.  

Questo percorso è memorizzato così com’è nella presentazione. Se viene specificato un percorso relativo, il file sarà inaccessibile aprendo la presentazione da una directory diversa. |

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) creato.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Zoom, in punti. |
| width | float | La larghezza del nuovo frame Zoom, in punti. |
| height | float | L’altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Il [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom; deve appartenere a questa presentazione. |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe) creato.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme.

--------------------

> ```
> Questo esempio dimostra come aggiungere un oggetto Zoom alla fine di una collezione
>  (supponiamo che ci siano almeno due diapositive nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Zoom, in punti. |
| width | float | La larghezza del nuovo frame Zoom, in punti. |
| height | float | L’altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Il [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom; deve appartenere a questa presentazione. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L’immagine per la diapositiva referenziata [IPPImage](../../com.aspose.slides/ippimage). |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe) creato.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Crea un nuovo frame Zoom e lo inserisce nella raccolta di forme all’indice specificato.

--------------------

> ```
> This example demonstrates creation and inserting a Zoom object at the specified index of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero a cui inserire il frame Zoom. |
| x | float | La coordinata x del nuovo frame Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Zoom, in punti. |
| width | float | La larghezza del nuovo frame Zoom, in punti. |
| height | float | L’altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Il [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom. |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe) creato.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuovo frame Zoom con un’immagine predefinita e lo inserisce nella raccolta di forme all’indice specificato.

--------------------

> ```
> Questo esempio dimostra la creazione e l'inserimento di un oggetto Zoom all'indice specificato di una collezione
>  (supponiamo che ci siano almeno due diapositive nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero a cui inserire il frame Zoom. |
| x | float | La coordinata x del nuovo frame Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Zoom, in punti. |
| width | float | La larghezza del nuovo frame Zoom, in punti. |
| height | float | L’altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Il [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L’immagine per la diapositiva referenziata [IPPImage](../../com.aspose.slides/ippimage). |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe) creato.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Crea un nuovo frame Zoom di sezione e lo aggiunge alla fine della raccolta di forme.

--------------------

> ```
> Questo esempio dimostra l'aggiunta di un oggetto Section Zoom alla fine di una collezione
>  (supponiamo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame Zoom di sezione, in punti. |
| y | float | La coordinata y del nuovo frame Zoom di sezione, in punti. |
| width | float | La larghezza del nuovo frame Zoom di sezione, in punti. |
| height | float | L’altezza del nuovo frame Zoom di sezione, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Zoom di sezione; deve appartenere a questa presentazione e contenere almeno una diapositiva. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) creato.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuovo frame Zoom di sezione con un’immagine predefinita e lo aggiunge alla fine della raccolta di forme.

--------------------

> ```
> Questo esempio dimostra l'aggiunta di un oggetto Section Zoom alla fine di una collezione
>  (supponiamo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame Zoom di sezione, in punti. |
| y | float | La coordinata y del nuovo frame Zoom di sezione, in punti. |
| width | float | La larghezza del nuovo frame Zoom di sezione, in punti. |
| height | float | L’altezza del nuovo frame Zoom di sezione, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Zoom di sezione; deve appartenere a questa presentazione e contenere almeno una diapositiva. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Il [IPPImage](../../com.aspose.slides/ippimage) da visualizzare all’interno del frame Zoom di sezione. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) creato.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Crea un nuovo frame Zoom di sezione e lo inserisce nella raccolta di forme all’indice specificato.

--------------------

> ```
> Questo esempio dimostra la creazione e l'inserimento di un oggetto Section Zoom all'indice specificato di una collezione
>  (supponiamo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero a cui inserire il frame Zoom di sezione. |
| x | float | La coordinata x del nuovo frame Zoom di sezione, in punti. |
| y | float | La coordinata y del nuovo frame Zoom di sezione, in punti. |
| width | float | La larghezza del nuovo frame Zoom di sezione, in punti. |
| height | float | L’altezza del nuovo frame Zoom di sezione, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Zoom di sezione; deve appartenere a questa presentazione e contenere almeno una diapositiva. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) creato.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuovo frame Zoom di sezione con un’immagine predefinita e lo inserisce nella raccolta di forme all’indice specificato.

--------------------

> ```
> This example demonstrates the creation and inserting a Section Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero a cui inserire il frame Zoom di sezione. |
| x | float | La coordinata x del nuovo frame Zoom di sezione, in punti. |
| y | float | La coordinata y del nuovo frame Zoom di sezione, in punti. |
| width | float | La larghezza del nuovo frame Zoom di sezione, in punti. |
| height | float | L’altezza del nuovo frame Zoom di sezione, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Zoom di sezione; deve appartenere a questa presentazione e contenere almeno una diapositiva. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L’immagine da visualizzare all’interno del frame Zoom di sezione. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) creato.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Crea un nuovo frame Zoom di riepilogo e lo aggiunge alla fine della raccolta di forme.

--------------------

> ```
> Questo esempio dimostra l'aggiunta di un oggetto Summary Zoom alla fine di una collezione
>  (supponiamo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame Zoom di riepilogo, in punti. |
| y | float | La coordinata y del nuovo frame Zoom di riepilogo, in punti. |
| width | float | La larghezza del nuovo frame Zoom di riepilogo, in punti. |
| height | float | L’altezza del nuovo frame Zoom di riepilogo, in punti. |
Questo metodo crea un frame di riepilogo zoom che raggruppa i collegamenti di riepilogo per tutte le sezioni della presentazione. |

**Restituisce:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Il nuovo [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Crea un nuovo frame di riepilogo zoom e lo inserisce nella collezione di forme all’indice specificato.

--------------------

> ```
> Questo esempio dimostra la creazione e l'inserimento di un oggetto Summary Zoom all'indice specificato di una collezione
>  (supponiamo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero in cui inserire il frame di riepilogo zoom. |
| x | float | La coordinata x del nuovo frame di riepilogo zoom, in punti. |
| y | float | La coordinata y del nuovo frame di riepilogo zoom, in punti. |
| width | float | La larghezza del nuovo frame di riepilogo zoom, in punti. |
| height | float | L’altezza del nuovo frame di riepilogo zoom, in punti. |

--------------------

Questo metodo crea un frame di riepilogo zoom che raggruppa i collegamenti di riepilogo per tutte le sezioni della presentazione. |

**Restituisce:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Il nuovo [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame video, in punti. |
| y | float | La coordinata y del nuovo frame video, in punti. |
| width | float | La larghezza del nuovo frame video, in punti. |
| height | float | L’altezza del nuovo frame video, in punti. |
| fname | java.lang.String | Il percorso o il nome del file video da incorporare. |

**Restituisce:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Il nuovo [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame video, in punti. |
| y | float | La coordinata y del nuovo frame video, in punti. |
| width | float | La larghezza del nuovo frame video, in punti. |
| height | float | L’altezza del nuovo frame video, in punti. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Il [IVideo](../../com.aspose.slides/ivideo) da incorporare nel frame video. |

**Restituisce:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Il nuovo [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Crea un nuovo frame video e lo inserisce nella collezione di forme all’indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero in cui inserire il frame video. |
| x | float | La coordinata x del nuovo frame video, in punti. |
| y | float | La coordinata y del nuovo frame video, in punti. |
| width | float | La larghezza del nuovo frame video, in punti. |
| height | float | L’altezza del nuovo frame video, in punti. |
| fname | java.lang.String | Il percorso o il nome del file video da incorporare. |

**Restituisce:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Il nuovo [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Crea un nuovo frame audio collegato a una traccia CD e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Crea un nuovo frame audio collegato a una traccia CD e lo inserisce nella collezione di forme all’indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero in cui inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Crea un nuovo frame audio collegato a un file audio esterno e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |
| fname | java.lang.String | Il percorso o il nome del file audio esterno da collegare. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Crea un nuovo frame audio collegato a un file audio esterno e lo inserisce nella collezione di forme all’indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero in cui inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |
| fname | java.lang.String | Il percorso o il nome del file audio esterno da collegare. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della collezione di forme. L’audio incorporato viene aggiunto alla collezione Presentation.Audios.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |
| audio_stream | java.io.InputStream | Un flusso di input contenente dati audio WAV da incorporare. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Crea un nuovo frame audio e lo aggiunge alla fine della collezione di forme utilizzando un oggetto audio esistente dalla lista Presentation.Audios.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Un’istanza [IAudio](../../com.aspose.slides/iaudio) dalla collezione Presentation.Audios. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuovo frame audio con un file WAV incorporato e lo inserisce nella collezione di forme all’indice specificato. L’audio incorporato viene aggiunto alla collezione Presentation.Audios.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero in cui inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |
| audio_stream | java.io.InputStream | Un flusso di input contenente dati audio WAV da incorporare. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Crea un nuovo frame audio e lo inserisce nella collezione di forme all’indice specificato utilizzando un oggetto audio esistente dalla lista Presentation.Audios.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice basato su zero in cui inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L’altezza del nuovo frame audio, in punti. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Un’istanza [IAudio](../../com.aspose.slides/iaudio) dalla collezione Presentation.Audios da incorporare. |

**Restituisce:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Restituisce l’indice basato su zero della prima occorrenza della forma specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La forma da individuare nella collezione. |

**Restituisce:**  
int - L’indice basato su zero della prima occorrenza della forma nella collezione di forme se trovata; altrimenti, \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Crea e restituisce un array che contiene tutte le forme.

**Restituisce:**  
com.aspose.slides.IShape[] - Un array di oggetti [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Crea e restituisce un array che contiene tutte le forme nell’intervallo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | L’indice della prima forma da restituire. |
| count | int | Il numero di forme da restituire. |

**Restituisce:**  
com.aspose.slides.IShape[] - Un array di oggetti [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Sposta la forma specificata in una nuova posizione all’interno della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice di destinazione basato su zero dove la forma sarà posizionata. |
| shape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da spostare nella collezione. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Sposta le forme specificate all’interno della collezione di forme, collocandole a partire dall’indice fornito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L’indice di destinazione basato su zero dove sarà posizionata la prima forma specificata; le forme successive seguiranno nell’ordine fornito. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Una o più istanze [IShape](../../com.aspose.slides/ishape) da spostare nella collezione. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Crea una nuova autoforma con formattazione predefinita e la aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) dell’autoforma da aggiungere. |

| x | float | La coordinata x del frame della forma, in punti. |
| y | float | La coordinata y del frame della forma, in punti. |
| width | float | La larghezza del frame della forma, in punti. |
| height | float | L'altezza del frame della forma, in punti. |

**Restituisce:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - Il nuovo [IAutoShape](../../com.aspose.slides/iautoshape) creato.  

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma automatica e la aggiunge alla fine della collezione di forme, opzionalmente inizializzandola con la formattazione del modello predefinito.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma automatica da aggiungere. |
| x | float | La coordinata x del frame della forma, in punti. |
| y | float | La coordinata y del frame della forma, in punti. |
| width | float | La larghezza del frame della forma, in punti. |
| height | float | L'altezza del frame della forma, in punti. |
| createFromTemplate | boolean | True per applicare lo stile del modello predefinito (stile semplice, testo centrato e nome non vuoto) alla nuova forma; false per creare la forma con tutte le proprietà impostate ai loro valori predefiniti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Il nuovo [IAutoShape](../../com.aspose.slides/iautoshape) creato.  

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Crea una nuova forma automatica rettangolare per contenere contenuti matematici e la aggiunge alla fine della collezione di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordinata x del frame della forma, in punti. |
| y | float | La coordinata y del frame della forma, in punti. |
| width | float | La larghezza del frame della forma, in punti. |
| height | float | L'altezza del frame della forma, in punti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Il nuovo [IAutoShape](../../com.aspose.slides/iautoshape) creato.  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, applicando la formattazione del modello predefinito.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire la nuova forma automatica. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma automatica da inserire. |
| x | float | La coordinata x del frame della forma, in punti. |
| y | float | La coordinata y del frame della forma, in punti. |
| width | float | La larghezza del frame della forma, in punti. |
| height | float | L'altezza del frame della forma, in punti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Il nuovo [IAutoShape](../../com.aspose.slides/iautoshape) creato.  

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma automatica e la inserisce nella collezione di forme all'indice specificato, opzionalmente inizializzandola con lo stile del modello predefinito.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire la forma automatica. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma automatica da inserire. |
| x | float | La coordinata x del frame della forma, in punti. |
| y | float | La coordinata y del frame della forma, in punti. |
| width | float | La larghezza del frame della forma, in punti. |
| height | float | L'altezza del frame della forma, in punti. |
| createFromTemplate | boolean | True per applicare lo stile del modello predefinito (incluso un nome non vuoto, stile semplice e testo centrato); false per creare la forma con tutte le proprietà impostate ai loro valori predefiniti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Il nuovo [IAutoShape](../../com.aspose.slides/iautoshape) creato.  

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Crea una nuova forma di gruppo vuota e la aggiunge alla fine della collezione di forme. Il frame del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte.

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Il nuovo [IGroupShape](../../com.aspose.slides/igroupshape) creato.  

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della collezione di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Il [ISvgImage](../../com.aspose.slides/isvgimage) contenente contenuto vettoriale da convertire in forme. |
| x | float | La coordinata x del frame del gruppo, in punti. |
| y | float | La coordinata y del frame del gruppo, in punti. |
| width | float | La larghezza del frame del gruppo, in punti. |
| height | float | L'altezza del frame del gruppo, in punti. |

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Il nuovo [IGroupShape](../../com.aspose.slides/igroupshape) creato.  

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Crea una nuova forma di gruppo vuota e la inserisce nella collezione di forme all'indice specificato. Il frame del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire la forma di gruppo. |

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Il nuovo [IGroupShape](../../com.aspose.slides/igroupshape) creato.  

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Crea una nuova forma di collegamento con lo stile del modello predefinito e la aggiunge alla fine della collezione di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di collegamento da aggiungere. |
| x | float | La coordinata x del frame del collegamento, in punti. |
| y | float | La coordinata y del frame del collegamento, in punti. |
| width | float | La larghezza del frame del collegamento, in punti. |
| height | float | L'altezza del frame del collegamento, in punti. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.  

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma di collegamento e la aggiunge alla fine della collezione di forme, opzionalmente applicando lo stile del modello predefinito.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di collegamento da creare. |
| x | float | La coordinata x del frame del collegamento, in punti. |
| y | float | La coordinata y del frame del collegamento, in punti. |
| width | float | La larghezza del frame del collegamento, in punti. |
| height | float | L'altezza del frame del collegamento, in punti. |
| createFromTemplate | boolean | True per applicare lo stile del modello predefinito (nome non vuoto, stile semplice); false per creare il collegamento con i valori predefiniti delle proprietà. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.  

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nuova forma di collegamento e la inserisce nella collezione di forme all'indice specificato, applicando lo stile del modello predefinito.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire la forma di collegamento. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di collegamento da inserire. |
| x | float | La coordinata x del frame del collegamento, in punti. |
| y | float | La coordinata y del frame del collegamento, in punti. |
| width | float | La larghezza del frame del collegamento, in punti. |
| height | float | L'altezza del frame del collegamento, in punti. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.  

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma di collegamento e la inserisce nella collezione di forme all'indice specificato, opzionalmente applicando lo stile del modello predefinito.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire la forma di collegamento. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di collegamento da inserire. |
| x | float | La coordinata x del frame del collegamento, in punti. |
| y | float | La coordinata y del frame del collegamento, in punti. |
| width | float | La larghezza del frame del collegamento, in punti. |
| height | float | L'altezza del frame del collegamento, in punti. |
| createFromTemplate | boolean | True per applicare lo stile del modello predefinito (nome non vuoto, stile semplice); false per creare il collegamento con i valori predefiniti delle proprietà. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.  

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuovo frame immagine contenente l'immagine specificata e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | Specifica il tipo di forma contenuto in [ShapeType](../../com.aspose.slides/shapetype), eccetto tutti i tipi di linee:\n\nShapeType.Line,\n\nShapeType.StraightConnector1,\n\nShapeType.BentConnector2,\n\nShapeType.BentConnector3,\n\nShapeType.BentConnector4,\n\nShapeType.BentConnector5,\n\nShapeType.CurvedConnector2,\n\nShapeType.CurvedConnector3,\n\nShapeType.CurvedConnector4,\n\nShapeType.CurvedConnector5. |
| x | float | La coordinata x del frame dell'immagine, in punti. |
| y | float | La coordinata y del frame dell'immagine, in punti. |
| width | float | La larghezza del frame dell'immagine, in punti. |
| height | float | L'altezza del frame dell'immagine, in punti. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Il [IPPImage](../../com.aspose.slides/ippimage) da visualizzare nel frame immagine. |

**Restituisce:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Il nuovo [IPictureFrame](../../com.aspose.slides/ipictureframe) creato.  

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuovo frame immagine contenente l'immagine specificata e lo inserisce nella collezione di forme all'indice specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice basato su zero al quale inserire il frame immagine. |
| shapeType | int | Specifica il tipo di forma contenuto in [ShapeType](../../com.aspose.slides/shapetype), eccetto tutti i tipi di linee:\n\nShapeType.Line,\n\nShapeType.StraightConnector1,\n\nShapeType.BentConnector2,\n\nShapeType.BentConnector3,\n\nShapeType.BentConnector4,\n\nShapeType.BentConnector5,\n\nShapeType.CurvedConnector2,\n\nShapeType.CurvedConnector3,\n\nShapeType.CurvedConnector4,\n\nShapeType.CurvedConnector5. |
| x | float | La coordinata x del frame dell'immagine, in punti. |
| y | float | La coordinata y del frame dell'immagine, in punti. |
| width | float | La larghezza del frame dell'immagine, in punti. |
| height | float | L'altezza del frame dell'immagine, in punti. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Il [IPPImage](../../com.aspose.slides/ippimage) da visualizzare nel frame immagine. |

**Restituisce:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Il nuovo [IPictureFrame](../../com.aspose.slides/ipictureframe) creato.  

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Crea una nuova tabella e la aggiunge alla fine della collezione di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | La coordinata x della tabella, in punti. |
| y | float | La coordinata y della tabella, in punti. |
| columnWidths | double[] | Un array di double che rappresenta le larghezze delle colonne della tabella, in punti. |
| rowHeights | double[] | Un array di double che rappresenta le altezze delle righe della tabella, in punti. |

**Restituisce:**
[ITable](../../com.aspose.slides/itable) - Il nuovo [ITable](../../com.aspose.slides/itable) creato.  

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Crea una nuova tabella e la inserisce nella raccolta di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero in cui inserire la tabella. |
| x | float | La coordinata x della tabella, in punti. |
| y | float | La coordinata y della tabella, in punti. |
| columnWidths | double[] | Un array di double che rappresenta le larghezze delle colonne della tabella, in punti. |
| rowHeights | double[] | Un array di double che rappresenta le altezze delle righe della tabella, in punti. |

**Restituisce:**
[ITable](../../com.aspose.slides/itable) - Il nuovo [ITable](../../com.aspose.slides/itable) creato.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove la forma all'indice specificato dalla raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero della forma da rimuovere. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Rimuove la prima occorrenza della forma specificata dalla raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da rimuovere. |

### clear() {#clear--}
```
public abstract void clear()
```

Rimuove tutte le forme dalla raccolta di forme.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forma da clonare. |
| x | float | La coordinata x del riquadro della forma clonata, in punti. |
| y | float | La coordinata y del riquadro della forma clonata, in punti. |
| width | float | La larghezza del riquadro della forma clonata, in punti. |
| height | float | L'altezza del riquadro della forma clonata, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La nuova forma mantiene la larghezza e l'altezza della sourceShape.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |
| x | float | La coordinata x del riquadro della forma clonata, in punti. |
| y | float | La coordinata y del riquadro della forma clonata, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La forma clonata mantiene la posizione e le dimensioni dell'originale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero in cui inserire la forma clonata. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |
| x | float | La coordinata x del riquadro della forma clonata, in punti. |
| y | float | La coordinata y del riquadro della forma clonata, in punti. |
| width | float | La larghezza del riquadro della forma clonata, in punti. |
| height | float | L'altezza del riquadro della forma clonata, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La nuova forma mantiene la larghezza e l'altezza della sourceShape.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero in cui inserire la forma clonata. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |
| x | float | La coordinata x del riquadro della forma clonata, in punti. |
| y | float | La coordinata y del riquadro della forma clonata, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La forma clonata mantiene la posizione e le dimensioni dell'originale.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero in cui inserire la forma clonata. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.