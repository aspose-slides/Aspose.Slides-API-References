---
title: ShapeCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Formen dar.
type: docs
url: /de/com.aspose.slides/shapecollection/
---
**Vererbung:**  
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**  
[com.aspose.slides.IShapeCollection](../../com.aspose.slides/ishapecollection)  
```
public final class ShapeCollection extends DomObject<GroupShape> implements IShapeCollection
```

Stellt eine Sammlung von shapes dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [get_Item(int index)](#get-Item-int-) | Ermittelt das Element am angegebenen Index. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der shape collection hinzu. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der shape collection hinzu. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der shape collection hinzu. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Stelle in die shape collection ein. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Stelle in die shape collection ein. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der shape collection hinzu. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der shape collection hinzu. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Frame und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitts-Zoom-Frame und fügt ihn am Ende der shape collection hinzu. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitts-Zoom-Frame mit einem vordefinierten Bild und fügt ihn am Ende der shape collection hinzu. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitts-Zoom-Frame und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitts-Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Frame und fügt ihn am Ende der shape collection hinzu. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Frame und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der shape collection hinzu. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der shape collection hinzu. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der shape collection hinzu. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der shape collection hinzu. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Erstellt einen neuen Audio-Frame, der mit einer CD-Titel verknüpft ist, und fügt ihn am Ende der shape collection hinzu. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Erstellt einen neuen Audio-Frame, der mit einer CD-Titel verknüpft ist, und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der shape collection hinzu. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der shape collection hinzu. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Frame und fügt ihn am Ende der shape collection hinzu, indem ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Stelle in die shape collection ein, indem ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Gibt den nullbasierten Index des ersten Vorkommens des angegebenen shape in der Sammlung zurück. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array zurück, das alle shapes enthält. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array zurück, das alle shapes im angegebenen Bereich enthält. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Verschiebt das angegebene shape an eine neue Position innerhalb der shape collection. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Verschiebt die angegebenen shapes innerhalb der shape collection und platziert sie beginnend am angegebenen Index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Erstellt ein neues auto shape mit Standardformatierung und fügt es am Ende der shape collection hinzu. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Erstellt ein neues auto shape und fügt es am Ende der shape collection hinzu, optional mit Standard-Template-Formatierung initialisiert. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Erstellt ein neues Rechteck-auto shape für mathematischen Inhalt und fügt es am Ende der shape collection hinzu. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Erstellt ein neues auto shape und fügt es an der angegebenen Stelle in die shape collection ein, wobei die Standard-Template-Formatierung angewendet wird. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Erstellt ein neues auto shape und fügt es an der angegebenen Stelle in die shape collection ein, optional mit Standard-Template-Styling initialisiert. |
| [addGroupShape()](#addGroupShape--) | Erstellt ein neues leeres group shape und fügt es am Ende der shape collection hinzu. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Erstellt ein neues group shape, konvertiert das angegebene SVG-Bild in einzelne shapes und fügt die resultierende Gruppe am Ende der shape collection hinzu. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Erstellt ein neues leeres group shape und fügt es an der angegebenen Stelle in die shape collection ein. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Erstellt ein neues connector shape mit Standard-Template-Styling und fügt es am Ende der shape collection hinzu. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Erstellt ein neues connector shape und fügt es am Ende der shape collection hinzu, optional mit Standard-Template-Styling. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Erstellt ein neues connector shape und fügt es an der angegebenen Stelle in die shape collection ein, wobei die Standard-Template-Formatierung angewendet wird. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Erstellt ein neues connector shape und fügt es an der angegebenen Stelle in die shape collection ein, optional mit Standard-Template-Styling. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen picture frame mit dem angegebenen Bild und fügt ihn am Ende der shape collection hinzu. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen picture frame mit dem angegebenen Bild und fügt ihn an der angegebenen Stelle in die shape collection ein. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie am Ende der shape collection hinzu. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Stelle in die shape collection ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das shape am angegebenen Index aus der shape collection. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Entfernt das erste Vorkommen des angegebenen shape aus der shape collection. |
| [clear()](#clear--) | Entfernt alle shapes aus der shape collection. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getParentGroup()](#getParentGroup--) | Ermittelt das übergeordnete group shape-Objekt für die shapes collection. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie des angegebenen shape und fügt sie am Ende der shape collection hinzu. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie des angegebenen shape und fügt sie am Ende der shape collection hinzu. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Erstellt eine Kopie des angegebenen shape und fügt sie am Ende der shape collection hinzu. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie des angegebenen shape und fügt sie an der angegebenen Stelle in die shape collection ein. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie des angegebenen shape und fügt sie an der angegebenen Stelle in die shape collection ein. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Erstellt eine Kopie des angegebenen shape und fügt sie an der angegebenen Stelle in die shape collection ein. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente aus der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt ein Synchronisations-Root zurück. |

### size() {#size--}
```
public final int size()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. **Nur lesbar**  int .

**Rückgabe:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Ermittelt das Element am angegebenen Index. **Nur lesbar** [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der shape collection hinzu.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instanziiert die Presentation-Klasse, die eine PPTX-Datei darstellt
>  Presentation pres = new Presentation();
>  try {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Fügt ein Diagramm mit Standarddaten hinzu
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Setzt den Diagrammtitel
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Setzt die erste Serie, um Werte anzuzeigen
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Setzt den Index für das Diagrammdatenblatt
>      int defaultWorksheetIndex = 0;
>      // Abrufen des Diagrammdaten-Arbeitsblatts
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Löscht die standardmäßig generierten Serien und Kategorien
>      chart.getChartData().getSeries().clear();
>      chart.getChartData().getCategories().clear();
>      // Fügt neue Serien hinzu
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 1, "Series 1"), chart.getType());
>      chart.getChartData().getSeries().add(fact.getCell(defaultWorksheetIndex, 0, 2, "Series 2"), chart.getType());
>      // Fügt neue Kategorien hinzu
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 1, 0, "Caetegoty 1"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 2, 0, "Caetegoty 2"));
>      chart.getChartData().getCategories().add(fact.getCell(defaultWorksheetIndex, 3, 0, "Caetegoty 3"));
>      // Nimmt die erste Diagrammserie
>      IChartSeries series = chart.getChartData().getSeries().get_Item(0);
>      // Füllt die Seriendaten
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Setzt die Füllfarbe für die Serie
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Nimmt die zweite Diagrammserie
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Füllt die Seriendaten
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Setzt die Füllfarbe für die Serie
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Setzt das erste Etikett, um den Kategorienamen anzuzeigen
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Setzt die Serie, um den Wert für das dritte Etikett anzuzeigen
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Speichert die PPTX-Datei auf die Festplatte
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des hinzuzufügenden chart. |
| x | float | Die x-Koordinate des neuen chart, in Punkten. |
| y | float | Die y-Koordinate des neuen chart, in Punkten. |
| width | float | Die Breite des chart, in Punkten. |
| height | float | Die Höhe des chart, in Punkten. |

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart) - Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der shape collection hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des hinzuzufügenden chart. |
| x | float | Die x-Koordinate des neuen chart, in Punkten. |
| y | float | Die y-Koordinate des neuen chart, in Punkten. |
| width | float | Die Breite des chart, in Punkten. |
| height | float | Die Höhe des chart, in Punkten. |
| initWithSample | boolean | True, um das neue chart mit Beispiel-Seriendaten und -Einstellungen zu initialisieren; false, um das chart ohne Serien und nur mit minimalen Einstellungen zu erstellen, was die Erstellung schneller macht. |

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart) - Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Erstellt ein SmartArt-Diagramm und fügt es am Ende der shape collection hinzu.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man eine SmartShape in einer PowerPoint-Präsentation hinzufügt.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des Diagramm-Frames, in Punkten. |
| y | float | Die y-Koordinate des Diagramm-Frames, in Punkten. |
| width | float | Die Breite des Diagramm-Frames, in Punkten. |
| height | float | Die Höhe des Diagramm-Frames, in Punkten. |
| layoutType | int | Der SmartArt-Layout-Typ. |

**Rückgabe:**
[ISmartArt](../../com.aspose.slides/ismartart) - Das neu erstellte [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Stelle in die shape collection ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des zu erstellenden chart. |
| x | float | Die x-Koordinate des neuen chart, in Punkten. |
| y | float | Die y-Koordinate des neuen chart, in Punkten. |
| width | float | Die Breite des neuen chart, in Punkten. |
| height | float | Die Höhe des neuen chart, in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue chart in die shape collection eingefügt werden soll. |

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart) - Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Erstellt ein neues chart, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Stelle in die shape collection ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des zu erstellenden chart. |
| x | float | Die x-Koordinate des neuen chart, in Punkten. |
| y | float | Die y-Koordinate des neuen chart, in Punkten. |
| width | float | Die Breite des neuen chart, in Punkten. |
| height | float | Die Höhe des neuen chart, in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue chart in die shape collection eingefügt werden soll. |
| initWithSample | boolean | True, um das neue chart mit Beispiel-Seriendaten und -Einstellungen zu initialisieren; false, um das chart ohne Serien und nur mit minimalen Einstellungen zu erstellen, was die Erstellung schneller macht. |

| x | float | Die x-Koordinate des neuen Diagramms, in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms, in Punkten. |
| width | float | Die Breite des neuen Diagramms, in Punkten. |
| height | float | Die Höhe des neuen Diagramms, in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue Diagramm in die Formensammlung eingefügt wird. |
| initWithSample | boolean | True, um das neue Diagramm mit Beispieldaten und -einstellungen zu initialisieren; false, um das Diagramm ohne Datenreihen und nur mit minimalen Einstellungen zu erstellen, wodurch die Erstellung schneller erfolgt. |

**Rückgabewert:**  
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formensammlung hinzu.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide), der vom Zoom-Frame referenziert wird; muss zu dieser Präsentation gehören. |

**Rückgabewert:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Folien):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide), der vom Zoom-Frame referenziert wird; muss zu dieser Präsentation gehören. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Rückgabewert:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-Frame und fügt ihn an der angegebenen Position in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Folien):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Zoom-Frame eingefügt wird. |
| x | float | Die x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide), der vom Zoom-Frame referenziert wird. |

**Rückgabewert:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Folien):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Zoom-Frame eingefügt wird. |
| x | float | Die x-Koordinate des neuen Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames, in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide), der vom Zoom-Frame referenziert wird. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Rückgabewert:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Section-Zoom-Frame und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Section Zoom Objekts am Ende einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Section-Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Section-Zoom-Frames, in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection), der vom Section-Zoom-Frame referenziert wird; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Rückgabewert:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Section-Zoom-Frame mit einem vordefinierten Bild und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Section Zoom Objekts am Ende einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Section-Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Section-Zoom-Frames, in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection), der vom Section-Zoom-Frame referenziert wird; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) zur Anzeige im Section-Zoom-Frame. |

**Rückgabewert:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Section-Zoom-Frame und fügt ihn an der angegebenen Position in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Section Zoom Objekts am angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Section-Zoom-Frame eingefügt wird. |
| x | float | Die x-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Section-Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Section-Zoom-Frames, in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection), der vom Section-Zoom-Frame referenziert wird; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Rückgabewert:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Section-Zoom-Frame mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Section Zoom Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Section-Zoom-Frame eingefügt wird. |
| x | float | Die x-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Section-Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Section-Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Section-Zoom-Frames, in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection), der vom Section-Zoom-Frame referenziert wird; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild zur Anzeige im Section-Zoom-Frame. |

**Rückgabewert:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Erstellt einen neuen Summary-Zoom-Frame und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Summary Zoom Objekts am Ende einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Summary-Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Summary-Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Summary-Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Summary-Zoom-Frames, in Punkten. |

--------------------

Diese Methode erstellt ein neues Summary-Zoom und fügt eine Sammlung von Objekten für alle Abschnitte in dieser Präsentation hinzu.

**Rückgabewert:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Das neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Erstellt einen neuen Summary-Zoom-Frame und fügt ihn an der angegebenen Position in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Summary Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Summary-Zoom-Frame eingefügt wird. |
| x | float | Die x-Koordinate des neuen Summary-Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Summary-Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Summary-Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Summary-Zoom-Frames, in Punkten. |

--------------------

Diese Methode erstellt einen Summary-Zoom-Frame, der Zusammenfassungs-Links für alle Abschnitte in der Präsentation aggregiert.

**Rückgabewert:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Das neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Das folgende Beispiel zeigt, wie OLE-Objekt-Frames zu Folien einer PowerPoint-Präsentation hinzugefügt werden.
>  
>  // Instanziiert die Presentation-Klasse, die die PPTX darstellt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Lädt eine cel-Datei in einen Stream
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
>      // Erstellt ein Data-Objekt zum Einbetten
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Fügt ein Ole Object Frame Shape hinzu
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Schreibt die PPTX auf die Festplatte
>      pres.save("OleEmbed_out.pptx", SaveFormat.Pptx);
>  }
>  catch (IOException e) { }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen OLE-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames, in Punkten. |
| width | float | Die Breite des neuen OLE-Frames, in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames, in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die Informationen über die eingebetteten OLE-Daten ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Rückgabewert:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen OLE-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames, in Punkten. |
| width | float | Die Breite des neuen OLE-Frames, in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames, in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wenn ein relativer Pfad angegeben wird, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich. |

**Rückgabewert:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Einfügen eines OLE-Objekts am zweiten Index:
>  
>  byte[] fileData = Files.readAllBytes(Paths.get("test.zip"));
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der OLE-Objekt-Frame eingefügt wird. |
| x | float | Die x-Koordinate des neuen OLE-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames in Punkten. |
| width | float | Die Breite des neuen OLE-Frames in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Rückgabe:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Das neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Erstellt ein neues OLE-Objekt-Frame und fügt es an der angegebenen Position in die Shape-Sammlung ein.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das OLE-Objekt-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen OLE-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames in Punkten. |
| width | float | Die Breite des neuen OLE-Frames in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.  

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht erreichbar. |

**Rückgabe:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Das neu erstellte OLE-Objekt-Frame.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Erstellt ein neues Video-Frame und fügt es am Ende der Shape-Sammlung hinzu.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | float | Die Breite des neuen Video-Frames in Punkten. |
| height | float | Die Höhe des neuen Video-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabe:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Das neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Erstellt ein neues Video-Frame und fügt es am Ende der Shape-Sammlung hinzu.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | float | Die Breite des neuen Video-Frames in Punkten. |
| height | float | Die Höhe des neuen Video-Frames in Punkten. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Das [IVideo](../../com.aspose.slides/ivideo) zum Einbetten in das Video-Frame. |

**Rückgabe:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Das neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Erstellt ein neues Video-Frame und fügt es an der angegebenen Position in die Shape-Sammlung ein.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Video-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | float | Die Breite des neuen Video-Frames in Punkten. |
| height | float | Die Höhe des neuen Video-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabe:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Das neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Erstellt ein neues Audio-Frame, das mit einer CD-Spur verknüpft ist, und fügt es am Ende der Shape-Sammlung hinzu.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Erstellt ein neues Audio-Frame, das mit einer CD-Spur verknüpft ist, und fügt es an der angegebenen Position in die Shape-Sammlung ein.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Erstellt ein neues Audio-Frame, das mit einer externen Audiodatei verknüpft ist, und fügt es am Ende der Shape-Sammlung hinzu.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public final IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Erstellt ein neues Audio-Frame, das mit einer externen Audiodatei verknüpft ist, und fügt es an der angegebenen Position in die Shape-Sammlung ein.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Erstellt ein neues Audio-Frame mit einer eingebetteten WAV-Datei und fügt es am Ende der Shape-Sammlung hinzu. Das eingebettete Audio wird zur Presentation.Audios-Sammlung hinzugefügt.

--------------------

> ```
> Das folgende Beispiel zeigt, wie ein Audio-Frame erstellt wird.
>  
>  // Instanziert eine Präsentationsklasse, die eine Präsentationsdatei darstellt
>  Presentation pres = new Presentation();
>  try {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Lädt die wav-Audiodatei in einen Stream
>      FileInputStream fstr = new FileInputStream("sampleaudio.wav");
>      try {
>          // Fügt den Audio-Frame hinzu
>          IAudioFrame audioFrame = sld.getShapes().addAudioFrameEmbedded(50, 150, 100, 100, fstr);
>          // Setzt den Wiedergabemodus und die Lautstärke des Audios
>          audioFrame.setPlayMode(AudioPlayModePreset.Auto);
>          audioFrame.setVolume(AudioVolumeMode.Loud);
>      } finally {
>          if (fstr != null) fstr.close();
>      }
>      // Schreibt die PowerPoint-Datei auf die Festplatte
>      pres.save("AudioFrameEmbed_out.pptx", SaveFormat.Pptx);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Erstellt ein neues Audio-Frame mit einer eingebetteten WAV-Datei und fügt es an der angegebenen Position in die Shape-Sammlung ein. Das eingebettete Audio wird zur Presentation.Audios-Sammlung hinzugefügt.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Erstellt ein neues Audio-Frame und fügt es am Ende der Shape-Sammlung hinzu, indem ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Eine [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Sammlung. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Erstellt ein neues Audio-Frame und fügt es an der angegebenen Position in die Shape-Sammlung ein, indem ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Eine [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Sammlung zum Einbetten. |

**Rückgabe:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Shape in der Sammlung zurück.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Die Shape, die in der Sammlung gesucht werden soll. |

**Rückgabe:**  
int - Der nullbasierte Index des ersten Vorkommens der Shape in der Shape-Sammlung, falls gefunden; andernfalls \\u20131.

### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Erstellt und gibt ein Array zurück, das alle Shapes enthält.

**Rückgabe:**  
com.aspose.slides.IShape[] - Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Erstellt und gibt ein Array zurück, das alle Shapes im angegebenen Bereich enthält.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Der Index des ersten zurückzugebenden Shapes. |
| count | int | Die Anzahl der zurückzugebenden Shapes. |

**Rückgabe:**  
com.aspose.slides.IShape[] - Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Verschiebt die angegebene Shape an eine neue Position innerhalb der Shape-Sammlung.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Ziel-Index, an dem die Shape platziert werden soll. |
| shape | [IShape](../../com.aspose.slides/ishape) | Die [IShape](../../com.aspose.slides/ishape), die innerhalb der Sammlung verschoben werden soll. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Verschiebt die angegebenen Shapes innerhalb der Shape-Sammlung und platziert sie beginnend ab dem angegebenen Index.

**Parameter:**  
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Ziel-Index, an dem das erste angegebene Shape platziert wird; nachfolgende Shapes folgen in der angegebenen Reihenfolge. |
| Formen | [IShape\[\]](../../com.aspose.slides/ishape) | Ein oder mehrere [IShape](../../com.aspose.slides/ishape)-Instanzen, die innerhalb der Sammlung verschoben werden sollen. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Autoform. |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie am Ende der Formensammlung hinzu, wobei optional die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Autoform. |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |
| createFromTemplate | boolean | **true**, um die Standardvorlagenformatierung (einfacher Stil, zentrierter Text und nicht leerer Name) auf die neue Form anzuwenden; **false**, um die Form mit allen Eigenschaften auf deren Standardwerte zu erzeugen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Erstellt eine neue rechteckige Autoform zur Aufnahme mathematischer Inhalte und fügt sie am Ende der Formensammlung hinzu.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man eine mathematische Gleichung in einer PowerPoint-Präsentation hinzufügt.
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formensammlung ein, wobei die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die neue Autoform eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Autoform. |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formensammlung ein, wobei optional die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Autoform eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Autoform. |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |
| createFromTemplate | boolean | **true**, um die Standardvorlagenformatierung (einschließlich nicht leerem Namen, einfachem Stil und zentriertem Text) anzuwenden; **false**, um die Form mit allen Eigenschaften auf deren Standardwerte zu setzen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).

### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Erstellt eine neue leere Gruppierungsform und fügt sie am Ende der Formensammlung hinzu. Der Rahmen der Gruppe wird automatisch angepasst, um alle hinzugefügten Formen aufzunehmen.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man einer Folie einer PowerPoint-Präsentation eine Gruppenform hinzufügt.
>  
>  // Instanziiert die Presentation-Klasse
>  Presentation pres = new Presentation();
>  try {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Greift auf die Shape-Sammlung der Folien zu
>      IShapeCollection slideShapes = sld.getShapes();
>      // Fügt der Folie ein Gruppen-Shape hinzu
>      IGroupShape groupShape = slideShapes.addGroupShape();
>      // Fügt Formen innerhalb des hinzugefügten Gruppen-Shapes hinzu
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 100, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 300, 300, 100, 100);
>      groupShape.getShapes().addAutoShape(ShapeType.Rectangle, 500, 300, 100, 100);
>      // Fügt den Rahmen des Gruppen-Shapes hinzu
>      groupShape.setFrame(new ShapeFrame(100, 300, 500, 40, NullableBool.False, NullableBool.False, 0));
>      // Schreibt die PPTX-Datei auf die Festplatte
>      pres.save("GroupShape_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Erstellt eine neue Gruppierungsform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Das [ISvgImage](../../com.aspose.slides/isvgimage) mit Vektorinhalt, das in Formen konvertiert werden soll. |
| x | float | Die x-Koordinate des Rahmens der Gruppe, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Gruppe, in Punkten. |
| width | float | Die Breite des Rahmens der Gruppe, in Punkten. |
| height | float | Die Höhe des Rahmens der Gruppe, in Punkten. |

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Erstellt eine neue leere Gruppierungsform und fügt sie an der angegebenen Position in die Formensammlung ein. Der Rahmen der Gruppe wird automatisch angepasst, um alle hinzugefügten Formen aufzunehmen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Gruppierungsform eingefügt werden soll. |

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbindungslinie mit Standardvorlagenstil und fügt sie am Ende der Formensammlung hinzu.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man einen Verbinder (einen geknickten Verbinder) zwischen zwei Formen (einer Ellipse und einem Rechteck) in einer PowerPoint-Präsentation hinzufügt.
>  
>  // Instanziert eine Präsentationsklasse, die eine PPTX-Datei darstellt
>  Presentation pres = new Presentation();
>  try {
>      // Greift auf die Shape-Sammlung einer bestimmten Folie zu
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Fügt ein Ellipse-AutoShape hinzu
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Fügt ein Rechteck-AutoShape hinzu
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Fügt der Folien-Shape-Sammlung ein Connector-Shape hinzu
>      IConnector connector = shapes.addConnector(ShapeType.BentConnector2, 0, 0, 10, 10);
>      // Verbindet die Formen mithilfe des Connectors
>      connector.setStartShapeConnectedTo(ellipse);
>      connector.setEndShapeConnectedTo(rectangle);
>      // Ruft reroute auf, das den automatischen kürzesten Pfad zwischen den Formen festlegt
>      connector.reroute();
>      // Speichert die Präsentation
>      pres.save("Shapes-connector.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindung, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindung, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindung, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindung, in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Verbindungslinie und fügt sie am Ende der Formensammlung hinzu, wobei optional die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der zu erstellenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindung, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindung, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindung, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindung, in Punkten. |
| createFromTemplate | boolean | **true**, um die Standardvorlagenformatierung (nicht leerer Name, einfacher Stil) anzuwenden; **false**, um die Verbindung mit Standardwerteigenschaften zu erzeugen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formensammlung ein, wobei die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbindungslinie eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindung, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindung, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindung, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindung, in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formensammlung ein, wobei optional die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbindungslinie eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindung, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindung, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindung, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindung, in Punkten. |
| createFromTemplate | boolean | **true**, um die Standardvorlagenformatierung (nicht leerer Name, einfacher Stil) anzuwenden; **false**, um die Verbindung mit Standardwerteigenschaften zu erzeugen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Gibt den Formtyp an, der in [ShapeType](../../com.aspose.slides/shapetype) enthalten ist, außer bei allen Arten von Linien:

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
| x | float | Die x-Koordinate des Bildrahmens, in Punkten. |
| y | float | Die y-Koordinate des Bildrahmens, in Punkten. |
| width | float | Die Breite des Bildrahmens, in Punkten. |
| height | float | Die Höhe des Bildrahmens, in Punkten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) im Bildrahmen anzuzeigende Bild. |

**Rückgabewert:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Der neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Bildrahmen eingefügt werden soll. |
| shapeType | int | Gibt den Formtyp an, der in [ShapeType](../../com.aspose.slides/shapetype) enthalten ist, außer bei allen Arten von Linien:

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
| x | float | Die x-Koordinate des Bildrahmens, in Punkten. |
| y | float | Die y-Koordinate des Bildrahmens, in Punkten. |
| width | float | Die Breite des Bildrahmens, in Punkten. |
| height | float | Die Höhe des Bildrahmens, in Punkten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) im Bildrahmen anzuzeigende Bild. |

**Rückgabewert:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Der neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Erstellt eine neue Tabelle und fügt sie am Ende der Formensammlung hinzu.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man eine Tabelle in einer PowerPoint-Präsentation hinzufügt.
>  
>  // Instanziert die Presentation-Klasse, die die PPTX-Datei darstellt
>  Presentation pres = new Presentation();
>  try
>  {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Definiert Spalten mit Breiten und Zeilen mit Höhen
>      double[] dblCols = {50, 50, 50};
>      double[] dblRows = {50, 30, 30, 30, 30};
> 
>      // Fügt der Folie ein Tabellen-Shape hinzu
>      ITable tbl = sld.getShapes().addTable(100, 50, dblCols, dblRows);
> 
>      // Setzt das Rahmenformat für jede Zelle
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
>      // Verbindet Zellen 1 und 2 der Zeile 1
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Fügt Text zur zusammengeführten Zelle hinzu
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Speichert die PPTX-Datei auf die Festplatte
>      pres.save("table.pptx", SaveFormat.Pptx);
>  }
>  finally
>  {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der Tabelle, in Punkten. |
| y | float | Die y-Koordinate der Tabelle, in Punkten. |
| columnWidths | double[] | Ein Array von double, das die Breiten der Tabellenspalten in Punkten darstellt. |
| rowHeights | double[] | Ein Array von double, das die Höhen der Tabellenzeilen in Punkten darstellt. |

**Rückgabe:**
[ITable](../../com.aspose.slides/itable) - Das neu erstellte [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Erstellt eine neue Tabelle und fügt sie in die shape collection an der angegebenen Position ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Tabelle eingefügt wird. |
| x | float | Die x-Koordinate der Tabelle, in Punkten. |
| y | float | Die y-Koordinate der Tabelle, in Punkten. |
| columnWidths | double[] | Ein Array von double, das die Breiten der Tabellenspalten in Punkten darstellt. |
| rowHeights | double[] | Ein Array von double, das die Höhen der Tabellenzeilen in Punkten darstellt. |

**Rückgabe:**
[ITable](../../com.aspose.slides/itable) - Das neu erstellte [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt die shape an dem angegebenen Index aus der shape collection.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index der zu entfernenden shape. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public final void remove(IShape shape)
```

Entfernt das erste Vorkommen der angegebenen shape aus der shape collection.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Die [IShape](../../com.aspose.slides/ishape) zum Entfernen. |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle shapes aus der shape collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabe:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> - Ein java.util.Iterator für die gesamte Sammlung.
### getParentGroup() {#getParentGroup--}
```
public final IGroupShape getParentGroup()
```

Ermittelt das übergeordnete Gruppen-shape-Objekt für die shapes collection. Nur-Lesen [IGroupShape](../../com.aspose.slides/igroupshape).

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie des angegebenen shapes und fügt sie am Ende der shape collection hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das zu klonende shape. |
| x | float | Die x-Koordinate des Rahmens des neuen shapes, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des neuen shapes, in Punkten. |
| width | float | Die Breite des Rahmens des neuen shapes, in Punkten. |
| height | float | Die Höhe des Rahmens des neuen shapes, in Punkten. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Das neu erstellte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Erstellt eine Kopie des angegebenen shapes und fügt sie am Ende der shape collection hinzu. Das neue shape behält die Breite und Höhe des sourceShape bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das zu klonende shape. |
| x | float | Die x-Koordinate des Rahmens des neuen shapes, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des neuen shapes, in Punkten. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Das neu erstellte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Erstellt eine Kopie des angegebenen shapes und fügt sie am Ende der shape collection hinzu. Das geklonte shape behält Position und Größe des Originals bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Das neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie des angegebenen shapes und fügt sie an dem angegebenen Index in die shape collection ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das geklonte shape eingefügt wird. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |
| x | float | Die x-Koordinate des Rahmens des geklonten shapes, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des geklonten shapes, in Punkten. |
| width | float | Die Breite des Rahmens des geklonten shapes, in Punkten. |
| height | float | Die Höhe des Rahmens des geklonten shapes, in Punkten. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Das neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Erstellt eine Kopie des angegebenen shapes und fügt sie an dem angegebenen Index in die shape collection ein. Das neue shape behält die Breite und Höhe des sourceShape bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das geklonte shape eingefügt wird. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |
| x | float | Die x-Koordinate des Rahmens des geklonten shapes, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des geklonten shapes, in Punkten. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Das neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Erstellt eine Kopie des angegebenen shapes und fügt sie an dem angegebenen Index in die shape collection ein. Das geklonte shape behält Position und Größe des Originals bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das geklonte shape eingefügt wird. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape) - Das neu erstellte [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Startindex im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur-Lesen boolean.

**Rückgabe:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt eine Synchronisationswurzel zurück. Nur-Lesen Object.

**Rückgabe:**
java.lang.Object