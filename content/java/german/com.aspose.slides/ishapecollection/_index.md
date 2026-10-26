---
title: IShapeCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung von Formen dar.
type: docs
url: /de/com.aspose.slides/ishapecollection/
---
**Alle implementierten Schnittstellen:**
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

Stellt eine Sammlung von Formen dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Ruft das Element am angegebenen Index ab. |
| [getParentGroup()](#getParentGroup--) | Ruft das übergeordnete Gruppenform-Objekt für die Formensammlung ab. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der Formensammlung hinzu. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der Formensammlung hinzu. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formensammlung hinzu. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Position in die Formensammlung ein. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Position in die Formensammlung ein. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE-Objektrahmen und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Rahmen und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn am Ende der Formensammlung hinzu. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitt-Zoom-Rahmen mit einem vordefinierten Bild und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Rahmen und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Erstellt einen neuen Video-Rahmen und fügt ihn am Ende der Formensammlung hinzu. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Rahmen und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn am Ende der Formensammlung hinzu. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Erstellt einen neuen Audio-Rahmen, der mit einer CD-Spur verknüpft ist, und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Formensammlung hinzu. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Rahmen, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Rahmen mit einer eingebetteten WAV-Datei und fügt ihn am Ende der Formensammlung hinzu. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Rahmen und fügt ihn am Ende der Formensammlung hinzu, indem er ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Rahmen mit einer eingebetteten WAV-Datei und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Rahmen und fügt ihn an der angegebenen Position in die Formensammlung ein, indem er ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Form in der Sammlung zurück. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array zurück, das alle Formen enthält. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Verschiebt die angegebene Form an eine neue Position innerhalb der Formensammlung. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Verschiebt die angegebenen Formen innerhalb der Formensammlung und platziert sie beginnend am angegebenen Index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Erstellt eine neue AutoForm mit Standardformatierung und fügt sie am Ende der Formensammlung hinzu. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Erstellt eine neue AutoForm und fügt sie am Ende der Formensammlung hinzu, optional mit Standardvorlagen-Formatierung initialisiert. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Erstellt eine neue Rechteck-AutoForm für mathematischen Inhalt und fügt sie am Ende der Formensammlung hinzu. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Erstellt eine neue AutoForm und fügt sie an der angegebenen Position in die Formensammlung ein, wobei die Standardvorlagen-Formatierung angewendet wird. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Erstellt eine neue AutoForm und fügt sie an der angegebenen Position in die Formensammlung ein, optional mit Standardvorlagen-Stil initialisiert. |
| [addGroupShape()](#addGroupShape--) | Erstellt eine neue leere Gruppenform und fügt sie am Ende der Formensammlung hinzu. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Erstellt eine neue Gruppenform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formensammlung hinzu. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Erstellt eine neue leere Gruppenform und fügt sie an der angegebenen Position in die Formensammlung ein. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Erstellt eine neue Verbinderform mit Standardvorlagen-Stil und fügt sie am Ende der Formensammlung hinzu. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Erstellt eine neue Verbinderform und fügt sie am Ende der Formensammlung hinzu, optional mit Standardvorlagen-Stil angewendet. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Erstellt eine neue Verbinderform und fügt sie an der angegebenen Position in die Formensammlung ein, wobei die Standardvorlagen-Stil angewendet wird. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Erstellt eine neue Verbinderform und fügt sie an der angegebenen Position in die Formensammlung ein, optional mit Standardvorlagen-Stil angewendet. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen Bildrahmen mit dem angegebenen Bild und fügt ihn am Ende der Formensammlung hinzu. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen Bildrahmen mit dem angegebenen Bild und fügt ihn an der angegebenen Position in die Formensammlung ein. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie am Ende der Formensammlung hinzu. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Position in die Formensammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Form an der angegebenen Position aus der Formensammlung. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Entfernt das erste Vorkommen der angegebenen Form aus der Formensammlung. |
| [clear()](#clear--) | Entfernt alle Formen aus der Formensammlung. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formensammlung hinzu. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formensammlung ein. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formensammlung ein. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formensammlung ein. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Ruft das Element am angegebenen Index ab. Nur lesbar [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Ruft das übergeordnete Gruppenform-Objekt für die Formensammlung ab. Nur lesbar [IGroupShape](../../com.aspose.slides/igroupshape).

**Rückgabe:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des hinzuzufügenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des Diagramms in Punkten. |
| height | float | Die Höhe des Diagramms in Punkten. |

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart) - Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des hinzuzufügenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des Diagramms in Punkten. |
| height | float | Die Höhe des Diagramms in Punkten. |
| initWithSample | boolean | True, um das neue Diagramm mit Beispiel-Seriendaten und -Einstellungen zu initialisieren; false, um das Diagramm ohne Serien und nur mit minimalen Einstellungen zu erstellen, was die Erstellung beschleunigt. |

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart) - Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formensammlung hinzu.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des Diagramm-Rahmens in Punkten. |
| y | float | Die y-Koordinate des Diagramm-Rahmens in Punkten. |
| width | float | Die Breite des Diagramm-Rahmens in Punkten. |
| height | float | Die Höhe des Diagramm-Rahmens in Punkten. |
| layoutType | int | Der SmartArt-Layout-Typ. |

**Rückgabe:**
[ISmartArt](../../com.aspose.slides/ismartart) - Das neu erstellte [ISmartArt](../../com.aspose.slides/ismartart).

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Position in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des zu erstellenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des neuen Diagramms in Punkten. |
| height | float | Die Höhe des neuen Diagramms in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue Diagramm in die Formensammlung eingefügt wird. |

**Rückgabe:**
[IChart](../../com.aspose.slides/ichart) - Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispiel-Seriendaten und -Einstellungen und fügt es an der angegebenen Position in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der Typ des zu erstellenden Diagramms. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des neuen Diagramms in Punkten. |
| height | float | Die Höhe des neuen Diagramms in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue Diagramm in die Formensammlung eingefügt wird. |
| initWithSample | boolean | True to initialize the new chart with sample series data and settings; false to create the chart with no series and only minimal settings, which makes creation faster. |
**Returns:**
[IChart](../../com.aspose.slides/ichart) - Das neu erstellte [IChart](../../com.aspose.slides/ichart).

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-Rahmens in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Das neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Erstellt einen neuen OLE-Objektrahmen und fügt ihn am Ende der Formensammlung hinzu.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-rahmens in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Das neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt einen neuen OLE-Objektrahmen und fügt ihn an der angegebenen Stelle in die Formensammlung ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der OLE-Objektrahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen OLE-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-Rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-Rahmens in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Das neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Erstellt einen neuen OLE-Objektrahmen und fügt ihn an der angegebenen Stelle in die Formensammlung ein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der OLE-Objektrahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen OLE-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-rahmens in Punkten. |
| width | float | Die Breite des neuen OLE-rahmens in Punkten. |
| height | float | Die Höhe des neuen OLE-rahmens in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht zugänglich. |

**Returns:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - Das neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-Rahmen und fügt ihn am Ende der Formensammlung hinzu.

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

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der von dem Zoom-Rahmen referenzierte [ISlide](../../com.aspose.slides/islide); muss zu dieser Präsentation gehören. |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Das neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-rahmen und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel zeigt das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung
>  (nehmen Sie an, dass die Präsentation "Presentation.pptx" mindestens zwei Folien enthält):
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

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Zoom-Rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-Rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-Rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der von dem Zoom-Rahmen referenzierte [ISlide](../../com.aspose.slides/islide); muss zu dieser Präsentation gehören. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Das neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-rahmen und fügt ihn an der angegebenen Stelle in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erstellen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Folien):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Zoom-rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zoom-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der von dem Zoom-rahmen referenzierte [ISlide](../../com.aspose.slides/islide). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Das neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-rahmen mit einem vordefinierten Bild und fügt ihn an der angegebenen Stelle in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erstellen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Folien):
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

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Zoom-rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zoom-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-rahmens in Punkten. |
| width | float | Die Breite des neuen Zoom-rahmens in Punkten. |
| height | float | Die Höhe des neuen Zoom-rahmens in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Der von dem Zoom-rahmen referenzierte [ISlide](../../com.aspose.slides/islide). |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Returns:**
[IZoomFrame](../../com.aspose.slides/izoomframe) - Das neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Abschnitt-Zoom-rahmen und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Section-Zoom-Objekts am Ende einer Sammlung
>  (nehmen Sie an, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der von dem Abschnitt-Zoom-rahmen referenzierte [ISection](../../com.aspose.slides/isection); muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Das neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Abschnitt-Zoom-rahmen mit einem vordefinierten Bild und fügt ihn am Ende der Formensammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Section-Zoom-Objekts am Ende einer Sammlung
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

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der von dem Abschnitt-Zoom-rahmen referenzierte [ISection](../../com.aspose.slides/isection); muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) zur Anzeige innerhalb des Abschnitt-Zoom-rahmens. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Das neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Abschnitt-Zoom-rahmen und fügt ihn an der angegebenen Stelle in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Section-Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Abschnitt-Zoom-rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der von dem Abschnitt-Zoom-rahmen referenzierte [ISection](../../com.aspose.slides/isection); muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Das neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Abschnitt-Zoom-rahmen mit einem vordefinierten Bild und fügt ihn an der angegebenen Stelle in die Formensammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Section-Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, dass die Präsentation "Presentation.pptx" mindestens zwei Abschnitte enthält):
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

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Abschnitt-Zoom-rahmen eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-rahmens in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-rahmens in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-rahmens in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Der von dem Abschnitt-Zoom-rahmen referenzierte [ISection](../../com.aspose.slides/isection); muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild zur Anzeige innerhalb des Abschnitt-Zoom-rahmens. |

**Returns:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - Das neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Erstellt einen neuen Zusammenfassungs-Zoom-rahmen und fügt ihn am Ende der Formensammlung hinzu.

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

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Zusammenfassungs-Zoom-rahmens in Punkten. |
| y | float | Die y-Koordinate des neuen Zusammenfassungs-Zoom-rahmens in Punkten. |
| width | float | Die Breite des neuen Zusammenfassungs-Zoom-rahmens in Punkten. |
| height | float | Die Höhe des neuen Zusammenfassungs-Zoom-rahmens in Punkten. |
This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**Rückgabe:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Das neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```


Erstellt einen neuen Summary Zoom-Frame und fügt ihn an der angegebenen Position in die Shape-Collection ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Summary-Zoom-Objekts an dem angegebenen Index einer Sammlung
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
| index | int | Der nullbasierte Index, an dem der Summary Zoom-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Summary Zoom-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Summary Zoom-Frames, in Punkten. |
| width | float | Die Breite des neuen Summary Zoom-Frames, in Punkten. |
| height | float | Die Höhe des neuen Summary Zoom-Frames, in Punkten.

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**Rückgabe:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - Das neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```


Erstellt einen neuen Video-Frame und fügt ihn am Ende der Shape-Collection hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames, in Punkten. |
| width | float | Die Breite des neuen Video-Frames, in Punkten. |
| height | float | Die Höhe des neuen Video-Frames, in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabe:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Das neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```


Erstellt einen neuen Video-Frame und fügt ihn am Ende der Shape-Collection hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames, in Punkten. |
| width | float | Die Breite des neuen Video-Frames, in Punkten. |
| height | float | Die Höhe des neuen Video-Frames, in Punkten. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Das [IVideo](../../com.aspose.slides/ivideo) zum Einbetten in den Video-Frame. |

**Rückgabe:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Das neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```


Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Position in die Shape-Collection ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Video-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Video-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames, in Punkten. |
| width | float | Die Breite des neuen Video-Frames, in Punkten. |
| height | float | Die Höhe des neuen Video-Frames, in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabe:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - Das neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```


Erstellt einen neuen Audio-Frame, der mit einer CD-Spur verknüpft ist, und fügt ihn am Ende der Shape-Collection hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```


Erstellt einen neuen Audio-Frame, der mit einer CD-Spur verknüpft ist, und fügt ihn an der angegebenen Position in die Shape-Collection ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```


Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Shape-Collection hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```


Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Shape-Collection ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```


Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn am Ende der Shape-Collection hinzu. Der eingebettete Ton wird zur Presentation.Audios-Collection hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```


Erstellt einen neuen Audio-Frame und fügt ihn am Ende der Shape-Collection hinzu, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Eine [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Collection. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```


Erstellt einen neuen Audio-Frame mit einer eingebetteten WAV-Datei und fügt ihn an der angegebenen Position in die Shape-Collection ein. Der eingebettete Ton wird zur Presentation.Audios-Collection hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```


Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Position in die Shape-Collection ein, wobei ein vorhandenes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames, in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames, in Punkten. |
| width | float | Die Breite des neuen Audio-Frames, in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames, in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Eine [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Collection zum Einbetten. |

**Rückgabe:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - Das neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```


Gibt den nullbasierten Index des ersten Auftretens der angegebenen Form in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Die Form, die in der Sammlung gesucht werden soll. |

**Rückgabe:**
int - Der nullbasierte Index des ersten Auftretens der Form in der Shape-Collection, falls gefunden; andernfalls \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```


Erstellt und gibt ein Array zurück, das alle Shapes enthält.

**Rückgabe:**
com.aspose.slides.IShape[] - Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```


Erstellt und gibt ein Array zurück, das alle Shapes im angegebenen Bereich enthält.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Der Index des ersten Shapes, das zurückgegeben werden soll. |
| count | int | Die Anzahl der zurückzugebenden Shapes. |

**Rückgabe:**
com.aspose.slides.IShape[] - Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```


Verschiebt die angegebene Form an eine neue Position innerhalb der Shape-Collection.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Zielindex, an dem die Form platziert wird. |
| shape | [IShape](../../com.aspose.slides/ishape) | Die [IShape](../../com.aspose.slides/ishape) zum Verschieben innerhalb der Sammlung. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```


Verschiebt die angegebenen Shapes innerhalb der Shape-Collection und platziert sie beginnend beim angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Zielindex, an dem das erste angegebene Shape platziert wird; nachfolgende Shapes folgen in der angegebenen Reihenfolge. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Ein oder mehrere [IShape](../../com.aspose.slides/ishape)-Instanzen zum Verschieben innerhalb der Sammlung. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```


Erstellt ein neues Auto-Shape mit Standardformatierung und fügt es am Ende der Shape-Collection hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) des Auto-Shapes, das hinzugefügt werden soll. |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie am Ende der Formensammlung hinzu, optional mit einer Initialisierung der Standardvorlagenformatierung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Autoform. |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |
| createFromTemplate | boolean | True, um die Standardvorlagenformatierung (einfacher Stil, zentrierter Text und ein nicht leerer Name) auf die neue Form anzuwenden; false, um die Form mit allen Eigenschaften auf ihre Standardwerte zu setzen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Erstellt eine neue rechteckige Autoform, die mathematischen Inhalt aufnehmen kann, und fügt sie am Ende der Formensammlung hinzu.

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
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
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
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formensammlung ein, optional mit einer Initialisierung der Standardvorlagenformatierung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Autoform eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Autoform. |
| x | float | Die x-Koordinate des Rahmens der Form, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Form, in Punkten. |
| width | float | Die Breite des Rahmens der Form, in Punkten. |
| height | float | Die Höhe des Rahmens der Form, in Punkten. |
| createFromTemplate | boolean | True, um die Standardvorlagenformatierung (einschließlich eines nicht leeren Namens, einfacher Stil und zentrierter Text) anzuwenden; false, um die Form mit allen Eigenschaften auf ihre Standardwerte zu setzen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Erstellt eine neue leere Gruppierungsform und fügt sie am Ende der Formensammlung hinzu. Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Formen aufzunehmen.

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
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
public abstract IGroupShape insertGroupShape(int index)
```

Erstellt eine neue leere Gruppierungsform und fügt sie an der angegebenen Position in die Formensammlung ein. Der Rahmen der Gruppe passt sich automatisch an, um alle hinzugefügten Formen aufzunehmen.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Gruppierungsform eingefügt werden soll. |

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) - Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbindungslinie mit Standardvorlagenformatierung und fügt sie am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindungslinie, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindungslinie, in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Verbindungslinie und fügt sie am Ende der Formensammlung hinzu, optional mit Anwendung der Standardvorlagenformatierung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der zu erstellenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindungslinie, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindungslinie, in Punkten. |
| createFromTemplate | boolean | True, um die Standardvorlagenformatierung (nicht leerer Name, einfacher Stil) anzuwenden; false, um die Verbindungslinie mit Standardwerten zu erstellen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formensammlung ein, wobei die Standardvorlagenformatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbindungslinie eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindungslinie, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindungslinie, in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formensammlung ein, optional mit Anwendung der Standardvorlagenformatierung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbindungslinie eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| y | float | Die y-Koordinate des Rahmens der Verbindungslinie, in Punkten. |
| width | float | Die Breite des Rahmens der Verbindungslinie, in Punkten. |
| height | float | Die Höhe des Rahmens der Verbindungslinie, in Punkten. |
| createFromTemplate | boolean | True, um die Standardvorlagenformatierung (nicht leerer Name, einfacher Stil) anzuwenden; false, um die Verbindungslinie mit Standardwerten zu erstellen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) - Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Gibt den Formtyp an, der in [ShapeType](../../com.aspose.slides/shapetype) enthalten ist, mit Ausnahme aller Linienarten:  

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
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Die neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bildrahmen, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die Formensammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Bildrahmen eingefügt werden soll. |
| shapeType | int | Gibt den Formtyp an, der in [ShapeType](../../com.aspose.slides/shapetype) enthalten ist, mit Ausnahme aller Linienarten:  

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
[IPictureFrame](../../com.aspose.slides/ipictureframe) - Die neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Erstellt eine neue Tabelle und fügt sie am Ende der Formensammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der Tabelle, in Punkten. |
| y | float | Die y-Koordinate der Tabelle, in Punkten. |
| columnWidths | double[] | Ein Array von Double-Werten, das die Breiten der Tabellenspalten in Punkten angibt. |
| rowHeights | double[] | Ein Array von Double-Werten, das die Höhen der Tabellenzeilen in Punkten angibt. |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) - Die neu erstellte [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Erstellt eine neue Table und fügt sie an dem angegebenen Index in die Shape-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Table eingefügt wird. |
| x | float | Die x-Koordinate der Table, in Punkten. |
| y | float | Die y-Koordinate der Table, in Punkten. |
| columnWidths | double[] | Ein Array von double-Werten, das die Breiten der Spalten der Table in Punkten angibt. |
| rowHeights | double[] | Ein Array von double-Werten, das die Höhen der Zeilen der Table in Punkten angibt. |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) - Die neu erstellte [ITable](../../com.aspose.slides/itable).

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Shape am angegebenen Index aus der Shape-Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Shape. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Entfernt das erste Vorkommen des angegebenen Shape aus der Shape-Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Entfernen. |

### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Shapes aus der Shape-Sammlung.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie des angegebenen Shape und fügt sie am Ende der Shape-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das Shape, das zu klonen ist. |
| x | float | Die x-Koordinate des Rahmens des geklonten Shape, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des geklonten Shape, in Punkten. |
| width | float | Die Breite des Rahmens des geklonten Shape, in Punkten. |
| height | float | Die Höhe des Rahmens des geklonten Shape, in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - Die neu erstellte [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Erstellt eine Kopie des angegebenen Shape und fügt sie am Ende der Shape-Sammlung hinzu. Das neue Shape behält die Breite und Höhe des sourceShape bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |
| x | float | Die x-Koordinate des Rahmens des geklonten Shape, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des geklonten Shape, in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - Die neu erstellte [IShape](../../com.aspose.slides/ishape).

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Erstellt eine Kopie des angegebenen Shape und fügt sie am Ende der Shape-Sammlung hinzu. Das geklonte Shape behält die Position und Größe des Originals bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - Die neu erstellte [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie des angegebenen Shape und fügt sie an dem angegebenen Index in die Shape-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das geklonte Shape eingefügt wird. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |
| x | float | Die x-Koordinate des Rahmens des geklonten Shape, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des geklonten Shape, in Punkten. |
| width | float | Die Breite des Rahmens des geklonten Shape, in Punkten. |
| height | float | Die Höhe des Rahmens des geklonten Shape, in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - Die neu erstellte [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Erstellt eine Kopie des angegebenen Shape und fügt sie an dem angegebenen Index in die Shape-Sammlung ein. Das neue Shape behält die Breite und Höhe des sourceShape bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das geklonte Shape eingefügt wird. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |
| x | float | Die x-Koordinate des Rahmens des geklonten Shape, in Punkten. |
| y | float | Die y-Koordinate des Rahmens des geklonten Shape, in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - Die neu erstellte [IShape](../../com.aspose.slides/ishape).

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Erstellt eine Kopie des angegebenen Shape und fügt sie an dem angegebenen Index in die Shape-Sammlung ein. Das geklonte Shape behält die Position und Größe des Originals bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das geklonte Shape eingefügt wird. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) zum Klonen. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) - Die neu erstellte [IShape](../../com.aspose.slides/ishape).