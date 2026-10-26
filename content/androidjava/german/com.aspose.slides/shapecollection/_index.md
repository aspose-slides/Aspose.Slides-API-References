---
title: ShapeCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
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

Stellt eine Sammlung von Formen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [size()](#size--) | Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. |
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formensammlung hinzu. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formensammlung hinzu. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formensammlung hinzu. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an dem angegebenen Index in die Formensammlung ein. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an dem angegebenen Index in die Formensammlung ein. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Rahmen mit vordefiniertem Bild und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen mit vordefiniertem Bild und fügt ihn am Ende der Formensammlung hinzu. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen mit vordefiniertem Bild und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn am Ende der Formensammlung hinzu. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Formensammlung hinzu. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Rahmen mit eingebetteter WAV-Datei und fügt ihn am Ende der Formensammlung hinzu. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Rahmen mit eingebetteter WAV-Datei und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Rahmen und fügt ihn am Ende der Formensammlung mithilfe eines vorhandenen Audio-Objekts aus der Liste Presentation.Audios hinzu. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein, wobei ein vorhandenes Audio-Objekt aus der Liste Presentation.Audios verwendet wird. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Form in der Sammlung zurück. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array zurück, das alle Formen enthält. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Verschiebt die angegebene Form an eine neue Position innerhalb der Formensammlung. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Verschiebt die angegebenen Formen innerhalb der Formensammlung und platziert sie beginnend am angegebenen Index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formensammlung hinzu. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Erstellt eine neue Autoform und fügt sie am Ende der Formensammlung hinzu, optional mit Standardvorlagenformatierung initialisiert. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Erstellt eine neue rechteckige Autoform für mathematischen Inhalt und fügt sie am Ende der Formensammlung hinzu. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Erstellt eine neue Autoform und fügt sie an dem angegebenen Index in die Formensammlung ein, wobei die Standardvorlagenformatierung angewendet wird. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Erstellt eine neue Autoform und fügt sie an dem angegebenen Index in die Formensammlung ein, optional mit Standardvorlagenstil initialisiert. |
| [addGroupShape()](#addGroupShape--) | Erstellt eine neue leere Gruppierung und fügt sie am Ende der Formensammlung hinzu. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Erstellt eine neue Gruppierung, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formensammlung hinzu. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Erstellt eine neue leere Gruppierung und fügt sie an dem angegebenen Index in die Formensammlung ein. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Erstellt eine neue Verbinder-Form mit Standardvorlagenstil und fügt sie am Ende der Formensammlung hinzu. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Erstellt eine neue Verbinder-Form und fügt sie am Ende der Formensammlung hinzu, optional mit Standardvorlagenstil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Erstellt eine neue Verbinder-Form und fügt sie an dem angegebenen Index in die Formensammlung ein, wobei der Standardvorlagenstil angewendet wird. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Erstellt eine neue Verbinder-Form und fügt sie an dem angegebenen Index in die Formensammlung ein, optional mit Standardvorlagenstil. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen Bild-Rahmen, der das angegebene Bild enthält, und fügt ihn am Ende der Formensammlung hinzu. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen Bild-Rahmen, der das angegebene Bild enthält, und fügt ihn an dem angegebenen Index in die Formensammlung ein. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie am Ende der Formensammlung hinzu. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie an dem angegebenen Index in die Formensammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Form am angegebenen Index aus der Formensammlung. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Entfernt das erste Vorkommen der angegebenen Form aus der Formensammlung. |
| [clear()](#clear--) | Entfernt alle Formen aus der Formensammlung. |
| [iterator()](#iterator--) | Gibt einen Enumerator zurück, der die Sammlung durchläuft. |
| [iteratorJava()](#iteratorJava--) | Gibt einen Java-Iterator für die gesamte Sammlung zurück. |
| [getParentGroup()](#getParentGroup--) | Liefert das übergeordnete Gruppen-Form-Objekt für die Formensammlung. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiert alle Elemente der Sammlung in das angegebene Array. |
| [isSynchronized()](#isSynchronized--) | Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. |
| [getSyncRoot()](#getSyncRoot--) | Gibt die Synchronisationswurzel zurück. |
### size() {#size--}
```
public final int size()
```

Ermittelt die tatsächlich in der Sammlung enthaltene Anzahl von Elementen. Nur lesbar  int .

**Rückgabewert:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IShape get_Item(int index)
```

Gibt das Element am angegebenen Index zurück. Nur lesbar [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public final IChart addChart(int type, float x, float y, float width, float height)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formensammlung hinzu.

--------------------

> ```
> The following example shows how to create Chart in PowerPoint Presentation.
>  
>  // Instanziert die Presentation-Klasse, die eine PPTX-Datei repräsentiert
>  Presentation pres = new Presentation();
>  try {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Fügt ein Diagramm mit den Standarddaten hinzu
>      IChart chart = sld.getShapes().addChart(ChartType.ClusteredColumn, 0, 0, 500, 500);
>      // Legt den Diagrammtitel fest
>      chart.getChartTitle().addTextFrameForOverriding("Sample Title");
>      chart.getChartTitle().getTextFrameForOverriding().getTextFrameFormat().setCenterText(NullableBool.True);
>      chart.getChartTitle().setHeight(20);
>      chart.setTitle(true);
>      // Legt fest, dass die erste Serie Werte anzeigen soll
>      chart.getChartData().getSeries().get_Item(0).getLabels().getDefaultDataLabelFormat().setShowValue(true);
>      // Legt den Index für das Diagrammdatenblatt fest
>      int defaultWorksheetIndex = 0;
>      // Holt das Arbeitsblatt für die Diagrammdaten
>      IChartDataWorkbook fact = chart.getChartData().getChartDataWorkbook();
>      // Löscht die standardmäßig erzeugten Serien und Kategorien
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
>      // Befüllt die Seriendaten
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 1, 20));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 1, 50));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 1, 30));
>      // Setzt die Füllfarbe für die Serie
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.RED);
>      // Nimmt die zweite Diagrammserie
>      series = chart.getChartData().getSeries().get_Item(1);
>      // Befüllt die Seriendaten
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 1, 2, 30));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 2, 2, 10));
>      series.getDataPoints().addDataPointForBarSeries(fact.getCell(defaultWorksheetIndex, 3, 2, 60));
>      // Setzt die Füllfarbe für die Serie
>      series.getFormat().getFill().setFillType(FillType.Solid);
>      series.getFormat().getFill().getSolidFillColor().setColor(Color.GREEN);
>      // Setzt das erste Datenetikett, um den Kategorienamen anzuzeigen
>      IDataLabel lbl = series.getDataPoints().get_Item(0).getLabel();
>      lbl.getDataLabelFormat().setShowCategoryName(true);
>      lbl = series.getDataPoints().get_Item(1).getLabel();
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      // Legt fest, dass die Serie den Wert für das dritte Datenetikett anzeigt
>      lbl = series.getDataPoints().get_Item(2).getLabel();
>      lbl.getDataLabelFormat().setShowValue(true);
>      lbl.getDataLabelFormat().setShowSeriesName(true);
>      lbl.getDataLabelFormat().setSeparator("/");
>      // Speichert die PPTP-Datei auf der Festplatte...
>      pres.save("AsposeChart_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des hinzuzufügenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des Diagramms in Punkten. |
| height | float | Die Höhe des Diagramms in Punkten. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public final IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des hinzuzufügenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des Diagramms in Punkten. |
| height | float | Die Höhe des Diagramms in Punkten. |
| initWithSample | boolean | true, um das neue Diagramm mit Beispieldaten und -einstellungen zu initialisieren; false, um das Diagramm ohne Daten und nur mit Minimal-Einstellungen zu erstellen, wodurch die Erstellung schneller ist. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public final ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formensammlung hinzu.

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
| x | float | Die x-Koordinate des Diagramm-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Diagramm-Rahmens in Punkten. |
| width | float | Die Breite des Diagramm-Rahmens in Punkten. |
| height | float | Die Höhe des Diagramm-Rahmens in Punkten. |
| layoutType | int | Der Layout-Typ des SmartArt. |

**Rückgabewert:**
[ISmartArt](../../com.aspose.slides/ismartart) – Das neu erstellte [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des zu erstellenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des neuen Diagramms in Punkten. |
| height | float | Die Höhe des neuen Diagramms in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue Diagramm in die Formensammlung eingefügt werden soll. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public final IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des zu erstellenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des neuen Diagramms in Punkten. |
| height | float | Die Höhe des neuen Diagramms in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue Diagramm in die Formensammlung eingefügt werden soll. |
| initWithSample | boolean | true, um das neue Diagramm mit Beispieldaten zu initialisieren; false, um das Diagramm ohne Daten und nur mit Minimal-Einstellungen zu erstellen, wodurch die Erstellung schneller ist. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Folien enthält):
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
| x | float | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide) auf den sich der Zoom-Rahmen bezieht; muss zu dieser Präsentation gehören. |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Folien enthält):
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
| x | float | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide) auf den sich der Zoom-Rahmen bezieht; muss zu dieser Präsentation gehören. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein.

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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Zoom-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide) auf den sich der Zoom-Rahmen bezieht. |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public final IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-Rahmen mit vordefiniertem Bild und fügt ihn an dem angegebenen Index in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Zoom-Objekts am angegebenen Index einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Folien enthält):
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
| index | int | Der nullbasierte Index, an dem der Zoom-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der [ISlide](../../com.aspose.slides/islide) auf den sich der Zoom-Rahmen bezieht. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Abschnitt-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Section-Zoom-Objekts am Ende einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
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
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection) auf den sich der Abschnitt-Zoom-Rahmen bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Abschnitt-Zoom-Rahmen mit vordefiniertem Bild und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> This example demonstrates adding a Section Zoom object to the end of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection) auf den sich der Abschnitt-Zoom-Rahmen bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) das im Abschnitt-Zoom-Rahmen angezeigt werden soll. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Abschnitt-Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Section-Zoom-Objekts am angegebenen Index einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
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
| index | int | Der nullbasierte Index, an dem der Abschnitt-Zoom-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection) auf den sich der Abschnitt-Zoom-Rahmen bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public final ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Abschnitt-Zoom-Rahmen mit vordefiniertem Bild und fügt ihn an dem angegebenen Index in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert die Erstellung und das Einfügen eines Section-Zoom-Objekts am angegebenen Index einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Abschnitt-Zoom-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der [ISection](../../com.aspose.slides/isection) auf den sich der Abschnitt-Zoom-Rahmen bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild, das im Abschnitt-Zoom-Rahmen angezeigt werden soll. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public final ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Summary-Zoom-Objekts am Ende einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
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
| x | float | Die x-Koordinate des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |

--------------------

Diese Methode erstellt einen neuen Zusammenfassungs-Zoom und legt eine Sammlung von Objekten für alle Abschnitte in dieser Präsentation an. |

**Rückgabewert:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Der neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public final ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erstellen und Einfügen eines Summary-Zoom-Objekts am angegebenen Index einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
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
| index | int | Der nullbasierte Index, an dem der Zusammenfassungs-Zoom-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zusammenfassungs-Zoom-Rahmens in Punkten. |

--------------------

Diese Methode erstellt einen Zusammenfassungs-Zoom-Rahmen, der Zusammenfassungs-Links für alle Abschnitte in der Präsentation aggregiert. |

**Rückgabewert:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Der neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man OLE-Objekt-Frames zu Folien einer PowerPoint-Präsentation hinzufügt.
>  
>  // Instanziiert die Presentation-Klasse, die die PPTX repräsentiert
>  Presentation pres = new Presentation();
>  try
>  {
>      // Greift auf die erste Folie zu
>      ISlide sld = pres.getSlides().get_Item(0);
> 
>      // Lädt eine Excel-Datei in einen Stream
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
>      // Erstellt ein Datenobjekt zum Einbetten
>      IOleEmbeddedDataInfo dataInfo = new OleEmbeddedDataInfo(mstream.toByteArray(), "xlsx");
> 
>      // Fügt ein OLE-Objekt-Frame-Shape hinzu
>      IOleObjectFrame oleObjectFrame = sld.getShapes().addOleObjectFrame(0, 0, (float)pres.getSlideSize().getSize().getWidth(),
>              (float)pres.getSlideSize().getSize().getHeight(), dataInfo);
> 
>      // Schreibt die PPTX-Datei auf die Festplatte
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
| x | float | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-Rahmens in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die Informationen zu den eingebetteten OLE-Daten ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-Rahmens in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich. |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Einfügen eines OLE-Objekts am zweiten Index:
>  
>  byte[] fileData = ... // "test.zip"
>  IOleDataInfo dataInfo = new OleDataInfo(fileData, "zip");
>  IOleObjectFrame oleObjectFrame = slides.getShapes().addOleObjectFrame(2, 150, 20, 50, 50, dataInfo);
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das OLE-Objekt-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-Rahmens in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public final IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Erstellt ein neues OLE-Objekt-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das OLE-Objekt-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-Rahmens in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich. |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte OLE-Objekt-Rahmen.
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Rahmens in Punkten. |
| width | float | Die Breite des neuen Video-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Video-Rahmens in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabewert:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Der neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public final IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Rahmens in Punkten. |
| width | float | Die Breite des neuen Video-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Video-Rahmens in Punkten. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Das [IVideo](../../com.aspose.slides/ivideo) zum Einbetten in den Video-Rahmen. |

**Rückgabewert:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Der neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public final IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Erstellt einen neuen Video-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Video-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Video-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Rahmens in Punkten. |
| width | float | Die Breite des neuen Video-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Video-Rahmens in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabewert:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Der neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public final IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public final IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public final IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public  int  size  ()
```

Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Erstellt einen neuen Audio-Rahmen mit eingebetteter WAV-Datei und fügt ihn am Ende der Formensammlung hinzu. Der eingebettete Ton wird zur Collection Presentation.Audios hinzugefügt.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man einen Audio-Frame erstellt.
>  
>  // Instanziert eine Präsentationsklasse, die eine Präsentationsdatei repräsentiert
>  Presentation pres = new Presentation();
>  try {
>      // Lädt die erste Folie
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Lädt die WAV-Audiodatei in einen Stream
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
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten enthält, die eingebettet werden sollen. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Erstellt einen neuen Audio-Rahmen mit eingebetteter WAV-Datei und fügt ihn an dem angegebenen Index in die Formensammlung ein. Der eingebettete Ton wird zur Collection Presentation.Audios hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten enthält, die eingebettet werden sollen. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Erstellt einen neuen Audio-Rahmen und fügt ihn am Ende der Formensammlung hinzu, wobei ein vorhandenes Audio-Objekt aus der Collection Presentation.Audios verwendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Ein [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Collection Presentation.Audios. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public final IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Erstellt einen neuen Audio-Rahmen und fügt ihn an dem angegebenen Index in die Formensammlung ein, wobei ein vorhandenes Audio-Objekt aus der Collection Presentation.Audios verwendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Rahmens in Punkten. |
| width | float | Die Breite des neuen Audio-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Audio-Rahmens in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Ein [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Collection Presentation.Audios zum Einbetten. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public final int indexOf(IShape shape)
```

Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Form in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Die Form, die in der Sammlung gesucht werden soll. |

**Rückgabewert:**
int – Der nullbasierte Index des ersten Vorkommens der Form in der Formensammlung, falls gefunden; andernfalls \\u20131.
### toArray() {#toArray--}
```
public final IShape[] toArray()
```

Erstellt und gibt ein Array zurück, das alle Formen enthält.

**Rückgabewert:**
com.aspose.slides.IShape[] – Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public final IShape[] toArray(int startIndex, int count)
```

Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Der Index der ersten zurückzugebenden Form. |
| count | int | Die Anzahl der zurückzugebenden Formen. |

**Rückgabewert:**
com.aspose.slides.IShape[] – Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public final void reorder(int index, IShape shape)
```

Verschiebt die angegebene Form an eine neue Position innerhalb der Formensammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Ziel-Index, an dem die Form platziert wird. |
| shape | [IShape](../../com.aspose.slides/ishape) | Die [IShape](../../com.aspose.slides/ishape) zum Verschieben innerhalb der Sammlung. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public final void reorder(int index, IShape[] shapes)
```

Verschiebt die angegebenen Formen innerhalb der Formensammlung und platziert sie beginnend am angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Ziel-Index, an dem die erste angegebene Form platziert wird; nachfolgende Formen folgen in der angegebenen Reihenfolge. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Ein oder mehrere [IShape](../../com.aspose.slides/ishape)-Instanzen zum Verschieben innerhalb der Sammlung. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Autoform. |
| x | float | Die x-Koordinate des Formrahmens in Punkten. |
| y | float | Die y-Koordinate des Formrahmens in Punkten. |
| width | float | Die Breite des Formrahmens in Punkten. |
| height | float | Die Höhe des Formrahmens in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public final IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie am Ende der Formensammlung hinzu, optional mit Standardvorlagenformatierung initialisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Autoform. |
| x | float | Die x-Koordinate des Formrahmens in Punkten. |
| y | float | Die y-Koordinate des Formrahmens in Punkten. |
| width | float | Die Breite des Formrahmens in Punkten. |
| height | float | Die Höhe des Formrahmens in Punkten. |
| createFromTemplate | boolean | true, um den Standardvorlagenstil (einfacher Stil, zentrierter Text, nicht leerer Name) auf die neue Form anzuwenden; false, um die Form mit allen Eigenschaften auf deren Standardwerte zu setzen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public final IAutoShape addMathShape(float x, float y, float width, float height)
```

Erstellt eine neue rechteckige Autoform zur Aufnahme mathematischer Inhalte und fügt sie am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel zeigt, wie man eine mathematische Gleichung in einer PowerPoint-Präsentation hinzufügt.
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
| x | float | Die x-Koordinate des Formrahmens in Punkten. |
| y | float | Die y-Koordinate des Formrahmens in Punkten. |
| width | float | Die Breite des Formrahmens in Punkten. |
| height | float | Die Höhe des Formrahmens in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Autoform und fügt sie an dem angegebenen Index in die Formensammlung ein, wobei die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die neue Autoform eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Autoform. |
| x | float | Die x-Koordinate des Formrahmens in Punkten. |
| y | float | Die y-Koordinate des Formrahmens in Punkten. |
| width | float | Die Breite des Formrahmens in Punkten. |
| height | float | Die Höhe des Formrahmens in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public final IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie an dem angegebenen Index in die Formensammlung ein, optional mit Standardvorlagenstil initialisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Autoform eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Autoform. |
| x | float | Die x-Koordinate des Formrahmens in Punkten. |
| y | float | Die y-Koordinate des Formrahmens in Punkten. |
| width | float | Die Breite des Formrahmens in Punkten. |
| height | float | Die Höhe des Formrahmens in Punkten. |
| createFromTemplate | boolean | true, um den Standardvorlagenstil (einschließlich nicht leerem Namen, einfachem Stil und zentriertem Text) anzuwenden; false, um die Form mit allen Eigenschaften auf deren Standardwerte zu setzen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public final IGroupShape addGroupShape()
```

Erstellt eine neue leere Gruppierung und fügt sie am Ende der Formensammlung hinzu. Der Rahmen der Gruppe wird automatisch angepasst, um alle hinzugefügten Formen aufzunehmen.

--------------------

> ```
> The following example shows how to add a group shape to a slide of PowerPoint Presentation.
>  
>  // Instanziert die Presentation-Klasse
>  Presentation pres = new Presentation();
>  try {
>      // Holt die erste Folie
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Greift auf die Formensammlung der Folien zu
>      IShapeCollection slideShapes = sld.getShapes();
>      // Fügt ein Gruppen-Shape zur Folie hinzu
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
[IGroupShape](../../com.aspose.slides/igroupshape) – Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public final IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Erstellt eine neue Gruppierung, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Die [ISvgImage](../../com.aspose.slides/isvgimage) mit Vektorinhalten, die in Formen konvertiert werden sollen. |
| x | float | Die x-Koordinate des Gruppenrahmens in Punkten. |
| y | float | Die y-Koordinate des Gruppenrahmens in Punkten. |
| width | float | Die Breite des Gruppenrahmens in Punkten. |
| height | float | Die Höhe des Gruppenrahmens in Punkten. |

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public final IGroupShape insertGroupShape(int index)
```

Erstellt eine neue leere Gruppierung und fügt sie an dem angegebenen Index in die Formensammlung ein. Der Rahmen der Gruppe wird automatisch angepasst, um alle hinzugefügten Formen aufzunehmen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Gruppe eingefügt werden soll. |

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbinder-Form mit Standardvorlagenstil und fügt sie am Ende der Formensammlung hinzu.

--------------------

> ```
> Das folgende Beispiel zeigt, wie man einen Connector (einen geknickten Connector) zwischen zwei Formen (einer Ellipse und einem Rechteck) in einer PowerPoint-Präsentation hinzufügt.
>  
>  // Instanziert eine Präsentationsklasse, die eine PPTX-Datei darstellt
>  Presentation pres = new Presentation();
>  try {
>      // Greift auf die Formensammlung für eine bestimmte Folie zu
>      IShapeCollection shapes = pres.getSlides().get_Item(0).getShapes();
>      // Fügt ein Ellipse-AutoShape hinzu
>      IAutoShape ellipse = shapes.addAutoShape(ShapeType.Ellipse, 0, 100, 100, 100);
>      // Fügt ein Rechteck-AutoShape hinzu
>      IAutoShape rectangle = shapes.addAutoShape(ShapeType.Rectangle, 100, 300, 100, 100);
>      // Fügt ein Connector-Shape zur Formensammlung der Folie hinzu
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
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Verbinder-Form. |
| x | float | Die x-Koordinate des Verbinder-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Verbinder-Rahmens in Punkten. |
| width | float | Die Breite des Verbinder-Rahmens in Punkten. |
| height | float | Die Höhe des Verbinder-Rahmens in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public final IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Verbinder-Form und fügt sie am Ende der Formensammlung hinzu, optional mit Standardvorlagenstil.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der zu erstellenden Verbinder-Form. |
| x | float | Die x-Koordinate des Verbinder-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Verbinder-Rahmens in Punkten. |
| width | float | Die Breite des Verbinder-Rahmens in Punkten. |
| height | float | Die Höhe des Verbinder-Rahmens in Punkten. |
| createFromTemplate | boolean | true, um den Standardvorlagenstil (nicht leerer Name, einfacher Stil) anzuwenden; false, um die Verbinder-Form mit Standardwerten zu erstellen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbinder-Form und fügt sie an dem angegebenen Index in die Formensammlung ein, wobei die Standardvorlagenstil angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbinder-Form eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbinder-Form. |
| x | float | Die x-Koordinate des Verbinder-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Verbinder-Rahmens in Punkten. |
| width | float | Die Breite des Verbinder-Rahmens in Punkten. |
| height | float | Die Höhe des Verbinder-Rahmens in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public final IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Verbinder-Form und fügt sie an dem angegebenen Index in die Formensammlung ein, optional mit Standardvorlagenstil.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbinder-Form eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbinder-Form. |
| x | float | Die x-Koordinate des Verbinder-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Verbinder-Rahmens in Punkten. |
| width | float | Die Breite des Verbinder-Rahmens in Punkten. |
| height | float | Die Höhe des Verbinder-Rahmens in Punkten. |
| createFromTemplate | boolean | true, um den Standardvorlagenstil (nicht leerer Name, einfacher Stil) anzuwenden; false, um die Verbinder-Form mit Standardwerten zu erstellen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bild-Rahmen, der das angegebene Bild enthält, und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Gibt den Formtyp an, der in [ShapeType](../../com.aspose.slides/shapetype) enthalten ist, mit Ausnahme aller Arten von Linien:

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
| x | float | Die x-Koordinate des Bild-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Bild-Rahmens in Punkten. |
| width | float | Die Breite des Bild-Rahmens in Punkten. |
| height | float | Die Höhe des Bild-Rahmens in Punkten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) zum Anzeigen im Bild-Rahmen. |

**Rückgabewert:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Der neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public final IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bild-Rahmen, der das angegebene Bild enthält, und fügt ihn an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Bild-Rahmen eingefügt werden soll. |
| shapeType | int | Gibt den Formtyp an, der in [ShapeType](../../com.aspose.slides/shapetype) enthalten ist, mit Ausnahme aller Arten von Linien:

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
| x | float | Die x-Koordinate des Bild-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Bild-Rahmens in Punkten. |
| width | float | Die Breite des Bild-Rahmens in Punkten. |
| height | float | Die Höhe des Bild-Rahmens in Punkten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) zum Anzeigen im Bild-Rahmen. |

**Rückgabewert:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Der neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public final ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Erstellt eine neue Tabelle und fügt sie am Ende der Formensammlung hinzu.

--------------------

> ```
> The following examples shows how to add table in PowerPoint Presentation.
>  
>  // Instanziert die Presentation-Klasse, die die PPTX-Datei repräsentiert
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
>      // Fügt der Folie ein Tabellenshape hinzu
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
>      // Fügt die Zellen 1 und 2 der Zeile 1 zusammen
>      tbl.mergeCells(tbl.get_Item(0, 0), tbl.get_Item(1, 1), false);
> 
>      // Fügt dem zusammengefügten Feld Text hinzu
>      tbl.get_Item(0, 0).getTextFrame().setText("Merged Cells");
> 
>      // Speichert die PPTX-Datei auf der Festplatte
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
| x | float | Die x-Koordinate der Tabelle in Punkten. |
| y | float | Die y-Koordinate der Tabelle in Punkten. |
| columnWidths | double[] | Ein Array von Doubles, das die Breiten der Tabellenspalten in Punkten angibt. |
| rowHeights | double[] | Ein Array von Doubles, das die Höhen der Tabellenzeilen in Punkten angibt. |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) – Die neu erstellte [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public final ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Erstellt eine neue Tabelle und fügt sie an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Tabelle eingefügt werden soll. |
| x | float | Die x-Koordinate der Tabelle in Punkten. |
| y | float | Die y-Koordinate der Tabelle in Punkten. |
| columnWidths | double[] | Ein Array von Doubles, das die Breiten der Tabellenspalten in Punkten angibt. |
| rowHeights | double[] | Ein Array von Doubles, das die Höhen der Tabellenzeilen in Punkten angibt. |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) – Die neu erstellte [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt die Form am angegebenen Index aus der Formensammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index der zu entfernenden Form. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public  or     the  (…  )
```

Entfernt das erste Vorkommen der angegebenen Form aus der Formensammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Die zu entfernende [IShape](../../com.aspose.slides/ishape). |

### clear() {#clear--}
```
public final void clear()
```

Entfernt alle Formen aus der Formensammlung.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iterator()
```

Gibt einen Enumerator zurück, der die Sammlung durchläuft.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> – Ein IGenericEnumerator, der zum Durchlaufen der Sammlung verwendet werden kann.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IShape> iteratorJava()
```

Gibt einen Java-Iterator für die gesamte Sammlung zurück.

**Rückgabewert:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IShape> – Ein java.util.Iterator für die gesamte Sammlung.
### getParentGroup() {#getParentGroup--}
```
public  ……    …
```

Liefert das übergeordnete Gruppen-Form-Objekt für die Formensammlung. Nur lesbar [IGroupShape](../../com.aspose.slides/igroupshape).

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende Form. |
| x | float | Die x-Koordinate des neuen Formrahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Formrahmens in Punkten. |
| width | float | Die Breite des neuen Formrahmens in Punkten. |
| height | float | Die Höhe des neuen Formrahmens in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public final IShape addClone(IShape sourceShape, float x, float y)
```

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. Die neue Form behält die Breite und Höhe von  sourceShape .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende Form. |
| x | float | Die x-Koordinate des neuen Formrahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Formrahmens in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public final IShape addClone(IShape sourceShape)
```

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. Die geklonte Form behält die ursprüngliche Position und Größe bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |
| x | float | Die x-Koordinate des geklonten Formrahmens in Punkten. |
| y | float | Die y-Koordinate des geklonten Formrahmens in Punkten. |
| width | float | Die Breite des geklonten Formrahmens in Punkten. |
| height | float | Die Höhe des geklonten Formrahmens in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public final IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein. Die neue Form behält die Breite und Höhe von  sourceShape .

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |
| x | float | Die x-Koordinate des geklonten Formrahmens in Punkten. |
| y | float | Die y-Koordinate des geklonten Formrahmens in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public final IShape insertClone(int index, IShape sourceShape)
```

Erstellt eine Kopie der angegebenen Form und fügt sie an dem angegebenen Index in die Formensammlung ein. Die geklonte Form behält die ursprüngliche Position und Größe bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiert alle Elemente der Sammlung in das angegebene Array.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Ziel-Array. |
| index | int | Start-Index im Ziel-Array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Gibt einen Wert zurück, der angibt, ob der Zugriff auf die Sammlung synchronisiert (thread-sicher) ist. Nur lesbar  boolean .

**Rückgabewert:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Gibt die Synchronisationswurzel zurück. Nur lesbar  Object .

**Rückgabewert:**
java.lang.Object