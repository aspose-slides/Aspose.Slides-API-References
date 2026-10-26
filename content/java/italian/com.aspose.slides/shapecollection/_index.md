---
title: ShapeCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di forme.
type: docs
url: /it/com.aspose.slides/shapecollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Rappresenta una raccolta di forme.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di elementi effettivamente contenuti nella raccolta. |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Crea un diagramma SmartArt e lo aggiunge alla fine della raccolta di forme. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuovo frame Zoom e lo aggiunge alla fine della raccolta di forme. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Crea un nuovo frame Zoom e lo inserisce nella raccolta di forme all'indice specificato. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Crea un nuovo frame Zoom con un'immagine predefinita e lo inserisce nella raccolta di forme all'indice specificato. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuovo frame Zoom di sezione e lo aggiunge alla fine della raccolta di forme. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuovo frame Zoom di sezione con un'immagine predefinita e lo aggiunge alla fine della raccolta di forme. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Crea un nuovo frame Zoom di sezione e lo inserisce nella raccolta di forme all'indice specificato. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Crea un nuovo frame Zoom di sezione con un'immagine predefinita e lo inserisce nella raccolta di forme all'indice specificato. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Crea un nuovo frame Zoom di riepilogo e lo aggiunge alla fine della raccolta di forme. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Crea un nuovo frame Zoom di riepilogo e lo inserisce nella raccolta di forme all'indice specificato. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della raccolta di forme. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuovo frame oggetto OLE e lo aggiunge alla fine della raccolta di forme. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Crea un nuovo frame oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Crea un nuovo frame oggetto OLE e lo inserisce nella raccolta di forme all'indice specificato. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Crea un nuovo frame video e lo aggiunge alla fine della raccolta di forme. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Crea un nuovo frame video e lo aggiunge alla fine della raccolta di forme. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Crea un nuovo frame video e lo inserisce nella raccolta di forme all'indice specificato. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Crea un nuovo frame audio collegato a una traccia CD e lo aggiunge alla fine della raccolta di forme. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Crea un nuovo frame audio collegato a una traccia CD e lo inserisce nella raccolta di forme all'indice specificato. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Crea un nuovo frame audio collegato a un file audio esterno e lo aggiunge alla fine della raccolta di forme. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Crea un nuovo frame audio collegato a un file audio esterno e lo inserisce nella raccolta di forme all'indice specificato. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della raccolta di forme. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Crea un nuovo frame audio con un file WAV incorporato e lo inserisce nella raccolta di forme all'indice specificato. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuovo frame audio e lo aggiunge alla fine della raccolta di forme usando un oggetto audio esistente dalla lista Presentation.Audios. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Crea un nuovo frame audio e lo inserisce nella raccolta di forme all'indice specificato usando un oggetto audio esistente dalla lista Presentation.Audios. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Restituisce l'indice basato su zero della prima occorrenza della forma specificata nella raccolta. |
| [toArray()](#toArray--) | Crea e restituisce un array che contiene tutte le forme. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Sposta la forma specificata in una nuova posizione all'interno della raccolta di forme. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Sposta le forme specificate all'interno della raccolta di forme, posizionandole a partire dall'indice fornito. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della raccolta di forme. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Crea una nuova forma automatica e la aggiunge alla fine della raccolta di forme, opzionalmente inizializzandola con la formattazione predefinita del modello. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Crea una nuova forma automatica rettangolare per contenere contenuti matematici e la aggiunge alla fine della raccolta di forme. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, applicando la formattazione predefinita del modello. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello. |
| [addGroupShape()](#addGroupShape--) | Crea una nuova forma di gruppo vuota e la aggiunge alla fine della raccolta di forme. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali, e aggiunge il gruppo risultante alla fine della raccolta di forme. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Crea una nuova forma di gruppo vuota e la inserisce nella raccolta di forme all'indice specificato. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Crea una nuova forma connettore con lo stile predefinito del modello e la aggiunge alla fine della raccolta di forme. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Crea una nuova forma connettore e la aggiunge alla fine della raccolta di forme, opzionalmente applicando lo stile predefinito del modello. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, applicando lo stile predefinito del modello. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Crea una nuova forma connettore e la inserisce nella raccolta di forme all'indice specificato, opzionalmente applicando lo stile predefinito del modello. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuovo frame immagine contenente l'immagine specificata e lo aggiunge alla fine della raccolta di forme. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Crea un nuovo frame immagine contenente l'immagine specificata e lo inserisce nella raccolta di forme all'indice specificato. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Crea una nuova tabella e la aggiunge alla fine della raccolta di forme. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Crea una nuova tabella e la inserisce nella raccolta di forme all'indice specificato. |
| [removeAt(int index)](#removeAt-int-) | Rimuove la forma all'indice specificato dalla raccolta di forme. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Rimuove la prima occorrenza della forma specificata dalla raccolta di forme. |
| [clear()](#clear--) | Rimuove tutte le forme dalla raccolta di forme. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la raccolta. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore Java per l'intera raccolta. |
| [getParentGroup()](#getParentGroup--) | Restituisce l'oggetto gruppo forme padre per la raccolta di forme. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia tutti gli elementi dalla raccolta nell'array specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di elementi effettivamente contenuti nella raccolta. Sola lettura  int .

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Restituisce l'elemento all'indice specificato. Sola lettura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Istanzia la classe Presentation che rappresenta un file PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Accede alla prima diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Aggiunge un grafico con i dati predefiniti
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Imposta il titolo del grafico
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Imposta la prima serie per mostrare i valori
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Imposta l'indice per il foglio dati del grafico
>      int defaultWorksheetIndex = 0;
>      // Ottiene il foglio di lavoro dei dati del grafico
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Elimina le serie e le categorie generate di default
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Aggiunge nuove serie
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Aggiunge nuove categorie
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Prende la prima serie del grafico
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Popola i dati della serie
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Imposta il colore di riempimento per la serie
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Prende la seconda serie del grafico
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Popola i dati della serie
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Imposta il colore di riempimento per la serie
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Imposta la prima etichetta per mostrare il nome della categoria
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Imposta la serie per mostrare il valore per la terza etichetta
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Salva il file PPTX su disco
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di grafico da aggiungere. |
| x | float | La coordinata x del nuovo grafico, in punti. |
| y | float | La coordinata y del nuovo grafico, in punti. |
| width | float | La larghezza del grafico, in punti. |
| height | float | L'altezza del grafico, in punti. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart) creato.
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo aggiunge alla fine della raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di grafico da aggiungere. |
| x | float | La coordinata x del nuovo grafico, in punti. |
| y | float | La coordinata y del nuovo grafico, in punti. |
| width | float | La larghezza del grafico, in punti. |
| height | float | L'altezza del grafico, in punti. |
| initWithSample | boolean | True per inizializzare il nuovo grafico con dati di serie di esempio e impostazioni; false per creare il grafico senza serie e solo con impostazioni minime, il che rende la creazione più veloce. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart) creato.
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Crea un diagramma SmartArt e lo aggiunge alla fine della raccolta di forme.

--------------------

> ```
> The following example shows how to add smart shape in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
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
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di grafico da creare. |
| x | float | La coordinata x del nuovo grafico, in punti. |
| y | float | La coordinata y del nuovo grafico, in punti. |
| width | float | La larghezza del nuovo grafico, in punti. |
| height | float | L'altezza del nuovo grafico, in punti. |
| index | int | L'indice basato su zero al quale inserire il nuovo grafico nella raccolta di forme. |

**Restituisce:**
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart) creato.
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Crea un nuovo grafico, lo inizializza con dati di serie di esempio e impostazioni, e lo inserisce nella raccolta di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| type | int | Il tipo di grafico da creare. |
| x | float | La coordinata x del nuovo grafico, in punti. |
| y | float | La coordinata y del nuovo grafico, in punti. |
| width | float | La larghezza del nuovo grafico, in punti. |
| height | float | L'altezza del nuovo grafico, in punti. |
| index | int | L'indice basato su zero al quale inserire il nuovo grafico nella raccolta di forme. |
| initWithSample | boolean | True per inizializzare il nuovo grafico con dati di serie di esempio e impostazioni; false per creare il grafico senza serie e solo con impostazioni minime, il che rende la creazione più veloce. |
| x | float | La coordinata x del nuovo chart, in punti. |
| y | float | La coordinata y del nuovo chart, in punti. |
| width | float | La larghezza del nuovo chart, in punti. |
| height | float | L'altezza del nuovo chart, in punti. |
| index | int | L'indice base zero in cui inserire il nuovo chart nella collezione di forme. |
| initWithSample | boolean | True per inizializzare il nuovo chart con dati di serie di esempio e impostazioni; false per creare il chart senza series e solo impostazioni minime, il che rende la creazione più veloce. |

**Restituisce:**  
[IChart](../../com.aspose.slides/ichart) - Il nuovo [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme.

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
| height | float | L'altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Lo [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom; deve appartenere a questa presentazione. |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuovo frame Zoom e lo aggiunge alla fine della collezione di forme.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
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
| height | float | L'altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Il [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom; deve appartenere a questa presentazione. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'immagine per lo slide referenziato [IPPImage](../../com.aspose.slides/ippimage). |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Crea un nuovo frame Zoom e lo inserisce nella collezione di forme all'indice specificato.

--------------------

> ```
> Questo esempio dimostra la creazione e l'inserimento di un oggetto Zoom all'indice specificato di una collezione
>  (supponendo che ci siano almeno due diapositive nella presentazione "Presentation.pptx"):
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
| index | int | L'indice base zero in cui inserire il frame Zoom. |
| x | float | La coordinata x del nuovo frame Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Zoom, in punti. |
| width | float | La larghezza del nuovo frame Zoom, in punti. |
| height | float | L'altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Il [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom. |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Crea un nuovo frame Zoom con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato.

--------------------

> ```
> Questo esempio dimostra la creazione e l'inserimento di un oggetto Zoom all'indice specificato di una collezione
>  (supponendo che ci siano almeno due diapositive nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero in cui inserire il frame Zoom. |
| x | float | La coordinata x del nuovo frame Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Zoom, in punti. |
| width | float | La larghezza del nuovo frame Zoom, in punti. |
| height | float | L'altezza del nuovo frame Zoom, in punti. |
| slide | [ISlide](../../com.aspose.slides/islide) | Il [ISlide](../../com.aspose.slides/islide) referenziato dal frame Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'immagine per lo slide referenziato [IPPImage](../../com.aspose.slides/ippimage). |

**Restituisce:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Il nuovo [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Crea un nuovo frame Section Zoom e lo aggiunge alla fine della collezione di forme.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| x | float | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | float | La larghezza del nuovo frame Section Zoom, in punti. |
| height | float | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Section Zoom; deve appartenere a questa presentazione e contenere almeno una slide. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuovo frame Section Zoom con un'immagine predefinita e lo aggiunge alla fine della collezione di forme.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| x | float | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | float | La larghezza del nuovo frame Section Zoom, in punti. |
| height | float | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Section Zoom; deve appartenere a questa presentazione e contenere almeno una slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Il [IPPImage](../../com.aspose.slides/ippimage) da visualizzare all'interno del frame Section Zoom. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Crea un nuovo frame Section Zoom e lo inserisce nella collezione di forme all'indice specificato.

--------------------

> ```
> Questo esempio dimostra la creazione e l'inserimento di un oggetto Section Zoom nell'indice specificato di una collezione
>  (supponendo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
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
| index | int | L'indice base zero in cui inserire il frame Section Zoom. |
| x | float | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | float | La larghezza del nuovo frame Section Zoom, in punti. |
| height | float | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Section Zoom; deve appartenere a questa presentazione e contenere almeno una slide. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Crea un nuovo frame Section Zoom con un'immagine predefinita e lo inserisce nella collezione di forme all'indice specificato.

--------------------

> ```
> Questo esempio dimostra la creazione e l'inserimento di un oggetto Section Zoom all'indice specificato di una collezione
>  (supponendo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero in cui inserire il frame Section Zoom. |
| x | float | La coordinata x del nuovo frame Section Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Section Zoom, in punti. |
| width | float | La larghezza del nuovo frame Section Zoom, in punti. |
| height | float | L'altezza del nuovo frame Section Zoom, in punti. |
| section | [ISection](../../com.aspose.slides/isection) | Il [ISection](../../com.aspose.slides/isection) referenziato dal frame Section Zoom; deve appartenere a questa presentazione e contenere almeno una slide. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | L'immagine da visualizzare all'interno del frame Section Zoom. |

**Restituisce:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Il nuovo [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Crea un nuovo frame Summary Zoom e lo aggiunge alla fine della collezione di forme.

--------------------

> ```
> Questo esempio dimostra l'aggiunta di un oggetto Summary Zoom alla fine di una collezione
>  (supponendo che ci siano almeno due sezioni nella presentazione "Presentation.pptx"):
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
| x | float | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | float | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | float | L'altezza del nuovo frame Summary Zoom, in punti. |

Questo metodo crea un nuovo Summary Zoom e inserisce una collezione di oggetti al suo interno per tutte le sezioni di questa presentazione.

**Restituisce:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Il nuovo [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Crea un nuovo frame Summary Zoom e lo inserisce nella collezione di forme all'indice specificato.

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
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
| index | int | L'indice base zero in cui inserire il frame Summary Zoom. |
| x | float | La coordinata x del nuovo frame Summary Zoom, in punti. |
| y | float | La coordinata y del nuovo frame Summary Zoom, in punti. |
| width | float | La larghezza del nuovo frame Summary Zoom, in punti. |
| height | float | L'altezza del nuovo frame Summary Zoom, in punti. |

Questo metodo crea un frame Summary Zoom che aggrega i collegamenti di riepilogo per tutte le sezioni della presentazione.

**Restituisce:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Il nuovo [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuovo frame OLE object e lo aggiunge alla fine della collezione di forme.

--------------------

> ```
> The following examples shows how to adding OLE Object Frames to Slides of PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents the PPTX
>  Presentation pres = new Presentation();
>  try
>  {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Load an cel file to stream
>      FileInputStream fs = new FileInputStream("book1.xlsx");
>      ByteArrayOutputStream mstream = new ByteArrayOutputStream();
>      byte[] buf = new byte[4096];
> 
>      while (true)
>      {
>          int bytesRead = fs.read(buf, 0, buf.length);
>          if (bytesRead <= 0)
>              break;
>          mstream.write(buf, 0, bytesRead);
>      }
>      // Create data object for embedding
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Add an Ole Object Frame shape
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      //Write the PPTX to disk
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L'altezza del nuovo frame OLE, in punti. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Le informazioni sui dati OLE incorporati ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Crea un nuovo frame OLE object e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L'altezza del nuovo frame OLE, in punti. |
| className | java.lang.String | Il nome della classe dell'oggetto OLE. |
| path | java.lang.String | Il percorso al file collegato.

Questo percorso è memorizzato così com'è nella presentazione. Se viene specificato un percorso relativo, il file sarà inaccessibile quando si apre la presentazione da una directory diversa.

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Crea un nuovo frame OLE object e lo inserisce nella collezione di forme all'indice specificato.

--------------------

> ```
> Questo esempio dimostra l'inserimento di un oggetto OLE al secondo indice:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero in cui inserire il frame OLE object. |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L'altezza del nuovo frame OLE, in punti. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Le informazioni dati OLE incorporate ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) creato.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Crea un nuovo frame oggetto OLE e lo inserisce nella collezione di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il frame oggetto OLE. |
| x | float | La coordinata x del nuovo frame OLE, in punti. |
| y | float | La coordinata y del nuovo frame OLE, in punti. |
| width | float | La larghezza del nuovo frame OLE, in punti. |
| height | float | L'altezza del nuovo frame OLE, in punti. |
| className | java.lang.String | Il nome della classe dell'oggetto OLE. |
| path | java.lang.String | Il percorso al file collegato. Questo percorso è memorizzato così com'è nella presentazione. Se viene specificato un percorso relativo, il file sarà inaccessibile quando si apre la presentazione da una directory diversa. |

**Restituisce:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Il nuovo frame oggetto OLE creato.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame video, in punti. |
| y | float | La coordinata y del nuovo frame video, in punti. |
| width | float | La larghezza del nuovo frame video, in punti. |
| height | float | L'altezza del nuovo frame video, in punti. |
| fname | java.lang.String | Il percorso o il nome del file video da incorporare. |

**Restituisce:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Il nuovo [IVideoFrame](../../com.aspose.slides/ivideoframe) creato.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Crea un nuovo frame video e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame video, in punti. |
| y | float | La coordinata y del nuovo frame video, in punti. |
| width | float | La larghezza del nuovo frame video, in punti. |
| height | float | L'altezza del nuovo frame video, in punti. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Il [IVideo](../../com.aspose.slides/ivideo) da incorporare nel frame video. |

**Restituisce:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Il nuovo [IVideoFrame](../../com.aspose.slides/ivideoframe) creato.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Crea un nuovo frame video e lo inserisce nella collezione di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il frame video. |
| x | float | La coordinata x del nuovo frame video, in punti. |
| y | float | La coordinata y del nuovo frame video, in punti. |
| width | float | La larghezza del nuovo frame video, in punti. |
| height | float | L'altezza del nuovo frame video, in punti. |
| fname | java.lang.String | Il percorso o il nome del file video da incorporare. |

**Restituisce:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Il nuovo [IVideoFrame](../../com.aspose.slides/ivideoframe) creato.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Crea un nuovo frame audio collegato a una traccia CD e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Crea un nuovo frame audio collegato a una traccia CD e lo inserisce nella collezione di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Crea un nuovo frame audio collegato a un file audio esterno e lo aggiunge alla fine della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |
| fname | java.lang.String | Il percorso o il nome del file audio esterno da collegare. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Crea un nuovo frame audio collegato a un file audio esterno e lo inserisce nella collezione di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |
| fname | java.lang.String | Il percorso o il nome del file audio esterno da collegare. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuovo frame audio con un file WAV incorporato e lo aggiunge alla fine della collezione di forme. L'audio incorporato è aggiunto alla collezione Presentation.Audios.

--------------------

> ```
> The following examples shows how to create Audio Frame.
>  
>  // Istanzia una classe Presentation che rappresenta un file di presentazione
>  Presentation pres = new Presentation();
>  try {
>      // Ottiene la prima diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Carica il file audio wav nello stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Aggiunge l'Audio Frame
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Imposta la modalità di riproduzione e il volume dell'audio
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Scrive il file PowerPoint su disco
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |
| audio_stream | java.io.InputStream | Un flusso di input contenente dati audio WAV da incorporare. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Crea un nuovo frame audio con un file WAV incorporato e lo inserisce nella collezione di forme all'indice specificato. L'audio incorporato è aggiunto alla collezione Presentation.Audios.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |
| audio_stream | java.io.InputStream | Un flusso di input contenente dati audio WAV da incorporare. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Crea un nuovo frame audio e lo aggiunge alla fine della collezione di forme usando un oggetto audio esistente dalla lista Presentation.Audios.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Un'istanza [IAudio](../../com.aspose.slides/iaudio) dalla collezione Presentation.Audios. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Crea un nuovo frame audio e lo inserisce nella collezione di forme all'indice specificato usando un oggetto audio esistente dalla lista Presentation.Audios.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il frame audio. |
| x | float | La coordinata x del nuovo frame audio, in punti. |
| y | float | La coordinata y del nuovo frame audio, in punti. |
| width | float | La larghezza del nuovo frame audio, in punti. |
| height | float | L'altezza del nuovo frame audio, in punti. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Un'istanza [IAudio](../../com.aspose.slides/iaudio) dalla collezione Presentation.Audios da incorporare. |

**Restituisce:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Il nuovo [IAudioFrame](../../com.aspose.slides/iaudioframe) creato.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Restituisce l'indice base zero della prima occorrenza della forma specificata nella collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La forma da individuare nella collezione. |

**Restituisce:**
int - L'indice base zero della prima occorrenza della forma nella collezione di forme se trovata; altrimenti, \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Crea e restituisce un array che contiene tutte le forme.

**Restituisce:**
com.aspose.slides.IShape[] - Un array di oggetti [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Crea e restituisce un array che contiene tutte le forme nell'intervallo specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startIndex | int | L'indice della prima forma da restituire. |
| count | int | Il numero di forme da restituire. |

**Restituisce:**
com.aspose.slides.IShape[] - Un array di oggetti [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Sposta la forma specificata in una nuova posizione all'interno della collezione di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero di destinazione dove la forma verrà posizionata. |
| shape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da spostare all'interno della collezione. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Sposta le forme specificate all'interno della collezione di forme, posizionandole a partire dall'indice fornito.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero di destinazione dove verrà posizionata la prima forma specificata; le forme successive seguiranno nell'ordine fornito. |
| forme | [IShape\[\]](../../com.aspose.slides/ishape) | Una o più istanze [IShape](../../com.aspose.slides/ishape) da spostare all'interno della raccolta. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Crea una nuova forma automatica con formattazione predefinita e la aggiunge alla fine della raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma automatica da aggiungere. |
| x | float | La coordinata x del riquadro della forma, in punti. |
| y | float | La coordinata y del riquadro della forma, in punti. |
| width | float | La larghezza del riquadro della forma, in punti. |
| height | float | L'altezza del riquadro della forma, in punti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nuova [IAutoShape](../../com.aspose.slides/iautoshape) creata.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma automatica e la aggiunge alla fine della raccolta di forme, opzionalmente inizializzandola con la formattazione predefinita del modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma automatica da aggiungere. |
| x | float | La coordinata x del riquadro della forma, in punti. |
| y | float | La coordinata y del riquadro della forma, in punti. |
| width | float | La larghezza del riquadro della forma, in punti. |
| height | float | L'altezza del riquadro della forma, in punti. |
| createFromTemplate | boolean | True per applicare lo stile predefinito del modello (stile semplice, testo centrato e nome non vuoto) alla nuova forma; false per creare la forma con tutte le proprietà impostate ai valori predefiniti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nuova [IAutoShape](../../com.aspose.slides/iautoshape) creata.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Crea una nuova forma automatica rettangolare per ospitare contenuti matematici e la aggiunge alla fine della raccolta di forme.

--------------------

> ```
> The following example shows how to add Mathematical Equation in PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape mathShape = pres.getSlides().get_Item(0).getShapes().addMathShape(0, 0, 720, 150);
>      IMathParagraph mathParagraph = ((MathPortion)mathShape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0)).getMathParagraph();
>      IMathFraction fraction = new MathematicalText("x").divide("y");
>      mathParagraph.add(new MathBlock(fraction));
>      IMathBlock mathBlock = new MathematicalText("c")
>          .setSuperscript("2")
>          .join("=")
>          .join(new MathematicalText("a").setSuperscript("2"))
>          .join("+")
>          .join(new MathematicalText("b").setSuperscript("2"));
>      mathParagraph.add(mathBlock);
>      pres.save("math.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | float | La coordinata x del riquadro della forma, in punti. |
| y | float | La coordinata y del riquadro della forma, in punti. |
| width | float | La larghezza del riquadro della forma, in punti. |
| height | float | L'altezza del riquadro della forma, in punti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nuova [IAutoShape](../../com.aspose.slides/iautoshape) creata.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, applicando la formattazione predefinita del modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la nuova forma automatica. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma automatica da inserire. |
| x | float | La coordinata x del riquadro della forma, in punti. |
| y | float | La coordinata y del riquadro della forma, in punti. |
| width | float | La larghezza del riquadro della forma, in punti. |
| height | float | L'altezza del riquadro della forma, in punti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nuova [IAutoShape](../../com.aspose.slides/iautoshape) creata.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma automatica e la inserisce nella raccolta di forme all'indice specificato, opzionalmente inizializzandola con lo stile predefinito del modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la forma automatica. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma automatica da inserire. |
| x | float | La coordinata x del riquadro della forma, in punti. |
| y | float | La coordinata y del riquadro della forma, in punti. |
| width | float | La larghezza del riquadro della forma, in punti. |
| height | float | L'altezza del riquadro della forma, in punti. |
| createFromTemplate | boolean | True per applicare lo stile predefinito del modello (incluso un nome non vuoto, stile semplice e testo centrato); false per creare la forma con tutte le proprietà impostate ai valori predefiniti. |

**Restituisce:**
[IAutoShape](../../com.aspose.slides/iautoshape) - La nuova [IAutoShape](../../com.aspose.slides/iautoshape) creata.

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Crea una nuova forma di gruppo vuota e la aggiunge alla fine della raccolta di forme. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte.

--------------------

> ```
> Il seguente esempio mostra come aggiungere una forma di gruppo a una diapositiva di PowerPoint Presentation.
>  
>  // Istanzia la classe Presentation
>  Presentation pres = new Presentation();
>  try {
>      // Ottieni la prima diapositiva
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Accedi alla collezione di forme delle diapositive
>      IShapeCollection slideShapes = sld.getShapes();
>      // Aggiungi una forma di gruppo alla diapositiva
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Aggiungi forme all'interno della forma di gruppo aggiunta
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Aggiungi il frame della forma di gruppo
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Scrivi il file PPTX su disco
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - La nuova [IGroupShape](../../com.aspose.slides/igroupshape) creata.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Crea una nuova forma di gruppo, converte l'immagine SVG specificata in forme individuali e aggiunge il gruppo risultante alla fine della raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Il [ISvgImage](../../com.aspose.slides/isvgimage) contenente contenuto vettoriale da convertire in forme. |
| x | float | La coordinata x del riquadro del gruppo, in punti. |
| y | float | La coordinata y del riquadro del gruppo, in punti. |
| width | float | La larghezza del riquadro del gruppo, in punti. |
| height | float | L'altezza del riquadro del gruppo, in punti. |

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - La nuova [IGroupShape](../../com.aspose.slides/igroupshape) creata.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Crea una nuova forma di gruppo vuota e la inserisce nella raccolta di forme all'indice specificato. Il riquadro del gruppo si adatterà automaticamente per contenere tutte le forme aggiunte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la forma di gruppo. |

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape) - La nuova [IGroupShape](../../com.aspose.slides/igroupshape) creata.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Crea una nuova forma di connettore con lo stile predefinito del modello e la aggiunge alla fine della raccolta di forme.

--------------------

> ```
> Il seguente esempio mostra come aggiungere un connettore (un connettore flesso) tra due forme (un'ellisse e un rettangolo) in PowerPoint Presentation.
>  
>  // Istanzia una classe di presentazione che rappresenta un file PPTX
>  Presentation pres = new Presentation();
>  try {
>      // Accede alla raccolta di forme per una diapositiva specifica
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Aggiunge una forma automatica Ellisse
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Aggiunge una forma automatica Rettangolo
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Aggiunge una forma di connettore alla raccolta di forme della diapositiva
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Collega le forme usando il connettore
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Chiama reroute che imposta il percorso più breve automatico tra le forme
>      connector.reroute();
>      // Salva la presentazione
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di connettore da aggiungere. |
| x | float | La coordinata x del riquadro del connettore, in punti. |
| y | float | La coordinata y del riquadro del connettore, in punti. |
| width | float | La larghezza del riquadro del connettore, in punti. |
| height | float | L'altezza del riquadro del connettore, in punti. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma di connettore e la aggiunge alla fine della raccolta di forme, opzionalmente applicando lo stile predefinito del modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di connettore da creare. |
| x | float | La coordinata x del riquadro del connettore, in punti. |
| y | float | La coordinata y del riquadro del connettore, in punti. |
| width | float | La larghezza del riquadro del connettore, in punti. |
| height | float | L'altezza del riquadro del connettore, in punti. |
| createFromTemplate | boolean | True per applicare lo stile predefinito del modello (nome non vuoto, stile semplice); false per creare il connettore con i valori predefiniti delle proprietà. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Crea una nuova forma di connettore e la inserisce nella raccolta di forme all'indice specificato, applicando lo stile predefinito del modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la forma di connettore. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di connettore da inserire. |
| x | float | La coordinata x del riquadro del connettore, in punti. |
| y | float | La coordinata y del riquadro del connettore, in punti. |
| width | float | La larghezza del riquadro del connettore, in punti. |
| height | float | L'altezza del riquadro del connettore, in punti. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Crea una nuova forma di connettore e la inserisce nella raccolta di forme all'indice specificato, opzionalmente applicando lo stile predefinito del modello.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la forma di connettore. |
| shapeType | int | Il [ShapeType](../../com.aspose.slides/shapetype) della forma di connettore da inserire. |
| x | float | La coordinata x del riquadro del connettore, in punti. |
| y | float | La coordinata y del riquadro del connettore, in punti. |
| width | float | La larghezza del riquadro del connettore, in punti. |
| height | float | L'altezza del riquadro del connettore, in punti. |
| createFromTemplate | boolean | True per applicare lo stile predefinito del modello (nome non vuoto, stile semplice); false per creare il connettore con i valori predefiniti delle proprietà. |

**Restituisce:**
[IConnector](../../com.aspose.slides/iconnector) - Il nuovo [IConnector](../../com.aspose.slides/iconnector) creato.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuovo riquadro immagine contenente l'immagine specificata e lo aggiunge alla fine della raccolta di forme.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| shapeType | int | Specifica il tipo di forma contenuto in [ShapeType](../../com.aspose.slides/shapetype), eccetto tutti i tipi di linee:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | La coordinata x del riquadro dell'immagine, in punti. |
| y | float | La coordinata y del riquadro dell'immagine, in punti. |
| width | float | La larghezza del riquadro dell'immagine, in punti. |
| height | float | L'altezza del riquadro dell'immagine, in punti. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Il [IPPImage](../../com.aspose.slides/ippimage) da visualizzare nel riquadro immagine. |

**Restituisce:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Il nuovo [IPictureFrame](../../com.aspose.slides/ipictureframe) creato.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Crea un nuovo riquadro immagine contenente l'immagine specificata e lo inserisce nella raccolta di forme all'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire il riquadro immagine. |
| shapeType | int | Specifica il tipo di forma contenuto in [ShapeType](../../com.aspose.slides/shapetype), eccetto tutti i tipi di linee:

ShapeType.Line,

ShapeType.StraightConnector1,

ShapeType.BentConnector2,

ShapeType.BentConnector3,

ShapeType.BentConnector4,

ShapeType.BentConnector5,

ShapeType.CurvedConnector2,

ShapeType.CurvedConnector3,

ShapeType.CurvedConnector4,

ShapeType.CurvedConnector5. |
| x | float | La coordinata x del riquadro dell'immagine, in punti. |
| y | float | La coordinata y del riquadro dell'immagine, in punti. |
| width | float | La larghezza del riquadro dell'immagine, in punti. |
| height | float | L'altezza del riquadro dell'immagine, in punti. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Il [IPPImage](../../com.aspose.slides/ippimage) da visualizzare nel riquadro immagine. |

**Restituisce:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Il nuovo [IPictureFrame](../../com.aspose.slides/ipictureframe) creato.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Crea una nuova tabella e la aggiunge alla fine della raccolta di forme.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Instantiate Presentation class that represents PPTX file
>  Presentation pres = new Presentation();
>  try
>  {
>      // Access first slide
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Define columns with widths and rows with heights
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Add table shape to slide
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Set border format for each cell
>      for (int row = 0; row < tbl.getRows().size(); row++)
>      {
>          for (int cell = 0; cell < tbl.getRows().get_Item(row).size(); cell++)
>          {
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderTop().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().setFillType((FillType.Solid));
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderBottom().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderLeft().setWidth(5);
> 
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().setFillType(FillType.Solid);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().getFillFormat().getSolidFillColor().setColor(Color.RED);
>              tbl.get_Item(cell, row).getCellFormat().getBorderRight().setWidth(5);
>          }
>      }
>      // Merge cells 1 & 2 of row 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Add text to the merged cell
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Save PPTX to Disk
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```
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
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Crea una nuova tabella e la inserisce nella raccolta di forme all'indice specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la tabella. |
| x | float | La coordinata x della tabella, in punti. |
| y | float | La coordinata y della tabella, in punti. |
| columnWidths | double[] | Un array di double che rappresenta le larghezze delle colonne della tabella, in punti. |
| rowHeights | double[] | Un array di double che rappresenta le altezze delle righe della tabella, in punti. |

**Restituisce:**
[ITable](../../com.aspose.slides/itable) - Il nuovo [ITable](../../com.aspose.slides/itable) creato.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove la forma all'indice specificato dalla raccolta di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice base zero della forma da rimuovere. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Rimuove la prima occorrenza della forma specificata dalla raccolta di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | La [IShape](../../com.aspose.slides/ishape) da rimuovere. |

### clear() {#clear--}
```
public final void clear()
```

Rimuove tutte le forme dalla raccolta di forme.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Restituisce un enumeratore che itera attraverso la raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Un IGenericEnumerator che può essere usato per iterare attraverso la raccolta.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Restituisce un iteratore java per l'intera raccolta.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Un java.util.Iterator per l'intera raccolta.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Ottiene l'oggetto forma gruppo genitore per la raccolta di forme. Solo lettura [IGroupShape](../../com.aspose.slides/igroupshape).

**Restituisce:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forma da clonare. |
| x | float | La coordinata x del riquadro della nuova forma, in punti. |
| y | float | La coordinata y del riquadro della nuova forma, in punti. |
| width | float | La larghezza del riquadro della nuova forma, in punti. |
| height | float | L'altezza del riquadro della nuova forma, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La nuova forma mantiene la larghezza e l'altezza della  sourceShape .

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | La forma da clonare. |
| x | float | La coordinata x del riquadro della nuova forma, in punti. |
| y | float | La coordinata y del riquadro della nuova forma, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Crea una copia della forma specificata e la aggiunge alla fine della raccolta di forme. La forma clonata mantiene la posizione e le dimensioni originali.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la forma clonata. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |
| x | float | La coordinata x della forma clonata, in punti. |
| y | float | La coordinata y della forma clonata, in punti. |
| width | float | La larghezza della forma clonata, in punti. |
| height | float | L'altezza della forma clonata, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La nuova forma mantiene la larghezza e l'altezza della  sourceShape .

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la forma clonata. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |
| x | float | La coordinata x della forma clonata, in punti. |
| y | float | La coordinata y della forma clonata, in punti. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Crea una copia della forma specificata e la inserisce nella raccolta di forme all'indice specificato. La forma clonata mantiene la posizione e le dimensioni originali.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | L'indice base zero al quale inserire la forma clonata. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Il [IShape](../../com.aspose.slides/ishape) da clonare. |

**Restituisce:**
[IShape](../../com.aspose.slides/ishape) - Il nuovo [IShape](../../com.aspose.slides/ishape) creato.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia tutti gli elementi dalla raccolta nell'array specificato.

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array di destinazione. |
| index | int | Indice di partenza nell'array di destinazione. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla raccolta è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object