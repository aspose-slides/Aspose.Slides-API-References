---
title: IShapeCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
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
| [get_Item(int index)](#get-Item-int-) | Gibt das Element am angegebenen Index zurück. |
| [getParentGroup()](#getParentGroup--) | Gibt das übergeordnete Gruppenformenobjekt für die Formen-Sammlung zurück. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formen-Sammlung hinzu. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formen-Sammlung hinzu. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formen-Sammlung hinzu. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an der angegebenen Position in die Formen-Sammlung ein. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an der angegebenen Position in die Formen-Sammlung ein. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | Erstellt einen neuen Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | Erstellt einen neuen Zoom-Frame mit vordefiniertem Bild und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitt-Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitt-Zoom-Frame mit vordefiniertem Bild und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | Erstellt einen neuen Abschnitt-Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | Erstellt einen neuen Abschnitt-Zoom-Frame mit vordefiniertem Bild und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | Erstellt einen neuen Zusammenfassungs-Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | Erstellt einen neuen Audio-Frame, der mit einem CD-Track verknüpft ist, und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | Erstellt einen neuen Audio-Frame, der mit einem CD-Track verknüpft ist, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Frame mit eingebetteter WAV-Datei und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Frame und fügt ihn am Ende der Formen-Sammlung unter Verwendung eines bestehenden Audio-Objekts aus der Presentation.Audios-Liste hinzu. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | Erstellt einen neuen Audio-Frame mit eingebetteter WAV-Datei und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein, wobei ein bestehendes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Form in der Sammlung zurück. |
| [toArray()](#toArray--) | Erstellt und gibt ein Array zurück, das alle Formen enthält. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | Erstellt und gibt ein Array zurück, das alle Formen im angegebenen Bereich enthält. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | Verschiebt die angegebene Form an eine neue Position innerhalb der Formen-Sammlung. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | Verschiebt die angegebenen Formen innerhalb der Formen-Sammlung, beginnend an dem angegebenen Index. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formen-Sammlung hinzu. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | Erstellt eine neue Autoform und fügt sie am Ende der Formen-Sammlung hinzu, optional mit Standard-Template-Formatierung inicialisiert. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | Erstellt eine neue rechteckige Autoform zum Einbetten mathematischer Inhalte und fügt sie am Ende der Formen-Sammlung hinzu. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formen-Sammlung ein, wobei die Standard-Template-Formatierung angewendet wird. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formen-Sammlung ein, optional mit Standard-Template-Stil inicialisiert. |
| [addGroupShape()](#addGroupShape--) | Erstellt eine neue leere Gruppenform und fügt sie am Ende der Formen-Sammlung hinzu. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | Erstellt eine neue Gruppenform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formen-Sammlung hinzu. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | Erstellt eine neue leere Gruppenform und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | Erstellt eine neue Verbindungslinie mit Standard-Template-Stil und fügt sie am Ende der Formen-Sammlung hinzu. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | Erstellt eine neue Verbindungslinie und fügt sie am Ende der Formen-Sammlung hinzu, optional mit Standard-Template-Stil. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein, wobei der Standard-Template-Stil angewendet wird. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein, optional mit Standard-Template-Stil. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn am Ende der Formen-Sammlung hinzu. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie am Ende der Formen-Sammlung hinzu. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | Erstellt eine neue Tabelle und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt die Form am angegebenen Index aus der Formen-Sammlung. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | Entfernt das erste Vorkommen der angegebenen Form aus der Formen-Sammlung. |
| [clear()](#clear--) | Entfernt alle Formen aus der Formen-Sammlung. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

Gibt das Element am angegebenen Index zurück. Nur lesend [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int |  |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape)
### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

Gibt das übergeordnete Gruppenformenobjekt für die Formen-Sammlung zurück. Nur lesend [IGroupShape](../../com.aspose.slides/igroupshape).

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape)
### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der zu erstellende Diagrammtyp. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des Diagramms in Punkten. |
| height | float | Die Höhe des Diagramms in Punkten. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der zu erstellende Diagrammtyp. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des Diagramms in Punkten. |
| height | float | Die Höhe des Diagramms in Punkten. |
| initWithSample | boolean | true, um das neue Diagramm mit Beispieldaten zu initialisieren; false, um das Diagramm ohne Serien und nur mit Minimal-Einstellungen zu erstellen, was die Erstellung beschleunigt. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

Erstellt ein SmartArt-Diagramm und fügt es am Ende der Formen-Sammlung hinzu.

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
| x | float | Die x-Koordinate des Diagramm-Frames in Punkten. |
| y | float | Die y-Koordinate des Diagramm-Frames in Punkten. |
| width | float | Die Breite des Diagramm-Frames in Punkten. |
| height | float | Die Höhe des Diagramm-Frames in Punkten. |
| layoutType | int | Der Layout-Typ des SmartArt. |

**Rückgabewert:**
[ISmartArt](../../com.aspose.slides/ismartart) – Das neu erstellte [ISmartArt](../../com.aspose.slides/ismartart).
### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der zu erstellende Diagrammtyp. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des neuen Diagramms in Punkten. |
| height | float | Die Höhe des neuen Diagramms in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue Diagramm in die Formen-Sammlung eingefügt werden soll. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

Erstellt ein neues Diagramm, initialisiert es mit Beispieldaten und -einstellungen und fügt es an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| type | int | Der zu erstellende Diagrammtyp. |
| x | float | Die x-Koordinate des neuen Diagramms in Punkten. |
| y | float | Die y-Koordinate des neuen Diagramms in Punkten. |
| width | float | Die Breite des neuen Diagramms in Punkten. |
| height | float | Die Höhe des neuen Diagramms in Punkten. |
| index | int | Der nullbasierte Index, an dem das neue Diagramm in die Formen-Sammlung eingefügt werden soll. |
| initWithSample | boolean | true, um das neue Diagramm mit Beispieldaten zu initialisieren; false, um das Diagramm ohne Serien und nur mit Minimal-Einstellungen zu erstellen, was die Erstellung beschleunigt. |

**Rückgabewert:**
[IChart](../../com.aspose.slides/ichart) – Das neu erstellte [IChart](../../com.aspose.slides/ichart).
### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen OLE-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames in Punkten. |
| width | float | Die Breite des neuen OLE-Frames in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

Erstellt einen neuen OLE-Objekt-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen OLE-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames in Punkten. |
| width | float | Die Breite des neuen OLE-Frames in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht erreichbar. |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der OLE-Objekt-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen OLE-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames in Punkten. |
| width | float | Die Breite des neuen OLE-Frames in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames in Punkten. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Die eingebetteten OLE-Dateninformationen ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

Erstellt einen neuen OLE-Objekt-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der OLE-Objekt-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen OLE-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen OLE-Frames in Punkten. |
| width | float | Die Breite des neuen OLE-Frames in Punkten. |
| height | float | Die Höhe des neuen OLE-Frames in Punkten. |
| className | java.lang.String | Der Klassenname des OLE-Objekts. |
| path | java.lang.String | Der Pfad zur verknüpften Datei.

Dieser Pfad wird unverändert in der Präsentation gespeichert. Wird ein relativer Pfad angegeben, ist die Datei beim Öffnen der Präsentation aus einem anderen Verzeichnis nicht erreichbar. |

**Rückgabewert:**
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) – Der neu erstellte [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Folien):
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
| x | float | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Die [ISlide](../../com.aspose.slides/islide) auf die sich der Zoom-Frame bezieht; muss zu dieser Präsentation gehören. |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Zoom-Objekts am Ende einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Folien):
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


**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Die [ISlide](../../com.aspose.slides/islide) auf die sich der Zoom-Frame bezieht; muss zu dieser Präsentation gehören. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

Erstellt einen neuen Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung
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
| index | int | Der nullbasierte Index, an dem der Zoom-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Die [ISlide](../../com.aspose.slides/islide) auf die sich der Zoom-Frame bezieht. |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

Erstellt einen neuen Zoom-Frame mit vordefiniertem Bild und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Zoom-Objekts an dem angegebenen Index einer Sammlung
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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Zoom-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Zoom-Frames in Punkten. |
| slide | [ISlide](../../com.aspose.slides/islide) | Die [ISlide](../../com.aspose.slides/islide) auf die sich der Zoom-Frame bezieht. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild für die referenzierte Folie [IPPImage](../../com.aspose.slides/ippimage). |

**Rückgabewert:**
[IZoomFrame](../../com.aspose.slides/izoomframe) – Der neu erstellte [IZoomFrame](../../com.aspose.slides/izoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Abschnitt-Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Section-Zoom-Objekts am Ende einer Sammlung
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
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Frames in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Die [ISection](../../com.aspose.slides/isection) auf die sich der Abschnitt-Zoom-Frame bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Abschnitt-Zoom-Frame mit vordefiniertem Bild und fügt ihn am Ende der Formen-Sammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Section-Zoom-Objekts am Ende einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
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
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Frames in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Die [ISection](../../com.aspose.slides/isection) auf die sich der Abschnitt-Zoom-Frame bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) das im Abschnitt-Zoom-Frame angezeigt werden soll. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

Erstellt einen neuen Abschnitt-Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Section-Zoom-Objekts am angegebenen Index einer Sammlung
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
| index | int | Der nullbasierte Index, an dem der Abschnitt-Zoom-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Frames in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Die [ISection](../../com.aspose.slides/isection) auf die sich der Abschnitt-Zoom-Frame bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

Erstellt einen neuen Abschnitt-Zoom-Frame mit vordefiniertem Bild und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Section-Zoom-Objekts an dem angegebenen Index einer Sammlung
>  (angenommen, die Präsentation "Presentation.pptx" enthält mindestens zwei Abschnitte):
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
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Abschnitt-Zoom-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Abschnitt-Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Abschnitt-Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Abschnitt-Zoom-Frames in Punkten. |
| section | [ISection](../../com.aspose.slides/isection) | Die [ISection](../../com.aspose.slides/isection) auf die sich der Abschnitt-Zoom-Frame bezieht; muss zu dieser Präsentation gehören und mindestens eine Folie enthalten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das Bild, das im Abschnitt-Zoom-Frame angezeigt werden soll. |

**Rückgabewert:**
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) – Der neu erstellte [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe).
### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

Erstellt einen neuen Zusammenfassungs-Zoom-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

--------------------

> ```
> Dieses Beispiel demonstriert das Hinzufügen eines Summary-Zoom-Objekts am Ende einer Sammlung
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
| x | float | Die x-Koordinate des neuen Zusammenfassungs-Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Zusammenfassungs-Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Zusammenfassungs-Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Zusammenfassungs-Zoom-Frames in Punkten. |

--------------------

Diese Methode erstellt einen Zusammenfassungs-Zoom-Frame, der Zusammenfassungs-Links für alle Abschnitte in der Präsentation aggregiert. 

**Rückgabewert:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Der neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

Erstellt einen neuen Zusammenfassungs-Zoom-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

--------------------

> ```
> Dieses Beispiel demonstriert das Erzeugen und Einfügen eines Summary-Zoom-Objekts an dem angegebenen Index einer Sammlung
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
| index | int | Der nullbasierte Index, an dem der Zusammenfassungs-Zoom-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Zusammenfassungs-Zoom-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Zusammenfassungs-Zoom-Frames in Punkten. |
| width | float | Die Breite des neuen Zusammenfassungs-Zoom-Frames in Punkten. |
| height | float | Die Höhe des neuen Zusammenfassungs-Zoom-Frames in Punkten. |

--------------------

Diese Methode erstellt einen Zusammenfassungs-Zoom-Frame, der Zusammenfassungs-Links für alle Abschnitte in der Präsentation aggregiert. 

**Rückgabewert:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) – Der neu erstellte [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | float | Die Breite des neuen Video-Frames in Punkten. |
| height | float | Die Höhe des neuen Video-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabewert:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Der neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

Erstellt einen neuen Video-Frame und fügt ihn am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | float | Die Breite des neuen Video-Frames in Punkten. |
| height | float | Die Höhe des neuen Video-Frames in Punkten. |
| video | [IVideo](../../com.aspose.slides/ivideo) | Das [IVideo](../../com.aspose.slides/ivideo) das im Video-Frame eingebettet werden soll. |

**Rückgabewert:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Der neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

Erstellt einen neuen Video-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Video-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Video-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Video-Frames in Punkten. |
| width | float | Die Breite des neuen Video-Frames in Punkten. |
| height | float | Die Höhe des neuen Video-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der einzubettenden Videodatei. |

**Rückgabewert:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) – Der neu erstellte [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

Erstellt einen neuen Audio-Frame, der mit einem CD-Track verknüpft ist, und fügt ihn am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

Erstellt einen neuen Audio-Frame, der mit einem CD-Track verknüpft ist, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

Erstellt einen neuen Audio-Frame, der mit einer externen Audiodatei verknüpft ist, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| fname | java.lang.String | Der Pfad oder Name der externen Audiodatei, die verknüpft werden soll. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

Erstellt einen neuen Audio-Frame mit eingebetteter WAV-Datei und fügt ihn am Ende der Formen-Sammlung hinzu. Die eingebettete Audiodatei wird zur Presentation.Audios-Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

Erstellt einen neuen Audio-Frame und fügt ihn am Ende der Formen-Sammlung unter Verwendung eines bestehenden Audio-Objekts aus der Presentation.Audios-Liste hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Eine [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Sammlung. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

Erstellt einen neuen Audio-Frame mit eingebetteter WAV-Datei und fügt ihn an der angegebenen Position in die Formen-Sammlung ein. Die eingebettete Audiodatei wird zur Presentation.Audios-Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio_stream | java.io.InputStream | Ein Eingabestream, der WAV-Audiodaten zum Einbetten enthält. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

Erstellt einen neuen Audio-Frame und fügt ihn an der angegebenen Position in die Formen-Sammlung ein, wobei ein bestehendes Audio-Objekt aus der Presentation.Audios-Liste verwendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem der Audio-Frame eingefügt werden soll. |
| x | float | Die x-Koordinate des neuen Audio-Frames in Punkten. |
| y | float | Die y-Koordinate des neuen Audio-Frames in Punkten. |
| width | float | Die Breite des neuen Audio-Frames in Punkten. |
| height | float | Die Höhe des neuen Audio-Frames in Punkten. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Eine [IAudio](../../com.aspose.slides/iaudio)-Instanz aus der Presentation.Audios-Sammlung zum Einbetten. |

**Rückgabewert:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) – Der neu erstellte [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

Gibt den nullbasierten Index des ersten Vorkommens der angegebenen Form in der Sammlung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Die Form, die in der Sammlung gesucht werden soll. |

**Rückgabewert:**
int – Der nullbasierte Index des ersten Vorkommens der Form in der Formen-Sammlung, falls gefunden; andernfalls \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

Erstellt ein Array, das alle Formen enthält, und gibt es zurück.

**Rückgabewert:**
com.aspose.slides.IShape[] – Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

Erstellt ein Array, das alle Formen im angegebenen Bereich enthält, und gibt es zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | int | Der Index der ersten zurückzugebenden Form. |
| count | int | Die Anzahl der zurückzugebenden Formen. |

**Rückgabewert:**
com.aspose.slides.IShape[] – Ein Array von [IShape](../../com.aspose.slides/ishape)-Objekten.
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

Verschiebt die angegebene Form an eine neue Position innerhalb der Formen-Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Ziel-Index, an dem die Form platziert werden soll. |
| shape | [IShape](../../com.aspose.slides/ishape) | Das [IShape](../../com.aspose.slides/ishape) das innerhalb der Sammlung verschoben werden soll. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

Verschiebt die angegebenen Formen innerhalb der Formen-Sammlung, beginnend an dem angegebenen Index.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Ziel-Index, an dem die erste angegebene Form platziert werden soll; nachfolgende Formen folgen in der angegebenen Reihenfolge. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | Ein oder mehrere [IShape](../../com.aspose.slides/ishape)-Instanzen, die innerhalb der Sammlung verschoben werden sollen. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Autoform mit Standardformatierung und fügt sie am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Autoform. |
| x | float | Die x-Koordinate des Form-Frames in Punkten. |
| y | float | Die y-Koordinate des Form-Frames in Punkten. |
| width | float | Die Breite des Form-Frames in Punkten. |
| height | float | Die Höhe des Form-Frames in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie am Ende der Formen-Sammlung hinzu, optional mit Standard-Template-Formatierung inicialisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Autoform. |
| x | float | Die x-Koordinate des Form-Frames in Punkten. |
| y | float | Die y-Koordinate des Form-Frames in Punkten. |
| width | float | Die Breite des Form-Frames in Punkten. |
| height | float | Die Höhe des Form-Frames in Punkten. |
| createFromTemplate | boolean | true, um den Standard-Template-Stil (einfacher Stil, zentrierter Text und nicht leerer Name) auf die neue Form anzuwenden; false, um die Form mit allen Standard-Eigenschaften zu erstellen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

Erstellt eine neue rechteckige Autoform zur Darstellung mathematischer Inhalte und fügt sie am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate des Form-Frames in Punkten. |
| y | float | Die y-Koordinate des Form-Frames in Punkten. |
| width | float | Die Breite des Form-Frames in Punkten. |
| height | float | Die Höhe des Form-Frames in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formen-Sammlung ein, wobei die Standard-Template-Formatierung angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die neue Autoform eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Autoform. |
| x | float | Die x-Koordinate des Form-Frames in Punkten. |
| y | float | Die y-Koordinate des Form-Frames in Punkten. |
| width | float | Die Breite des Form-Frames in Punkten. |
| height | float | Die Höhe des Form-Frames in Punkten. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Autoform und fügt sie an der angegebenen Position in die Formen-Sammlung ein, optional mit Standard-Template-Stil inicialisiert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Autoform eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Autoform. |
| x | float | Die x-Koordinate des Form-Frames in Punkten. |
| y | float | Die y-Koordinate des Form-Frames in Punkten. |
| width | float | Die Breite des Form-Frames in Punkten. |
| height | float | Die Höhe des Form-Frames in Punkten. |
| createFromTemplate | boolean | true, um den Standard-Template-Stil (einschließlich nicht leerem Namen, einfachem Stil und zentriertem Text) anzuwenden; false, um die Form mit allen Standard-Eigenschaften zu erstellen. |

**Rückgabewert:**
[IAutoShape](../../com.aspose.slides/iautoshape) – Die neu erstellte [IAutoShape](../../com.aspose.slides/iautoshape).
### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

Erstellt eine neue leere Gruppenform und fügt sie am Ende der Formen-Sammlung hinzu. Der Rahmen der Gruppe passt sich automatisch an alle hinzugefügten Formen an.

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

Erstellt eine neue Gruppenform, konvertiert das angegebene SVG-Bild in einzelne Formen und fügt die resultierende Gruppe am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | Das [ISvgImage](../../com.aspose.slides/isvgimage) mit Vektorinhalt, das in Formen konvertiert werden soll. |
| x | float | Die x-Koordinate des Gruppen-Frames in Punkten. |
| y | float | Die y-Koordinate des Gruppen-Frames in Punkten. |
| width | float | Die Breite des Gruppen-Frames in Punkten. |
| height | float | Die Höhe des Gruppen-Frames in Punkten. |

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

Erstellt eine neue leere Gruppenform und fügt sie an der angegebenen Position in die Formen-Sammlung ein. Der Rahmen der Gruppe passt sich automatisch an alle hinzugefügten Formen an.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Gruppenform eingefügt werden soll. |

**Rückgabewert:**
[IGroupShape](../../com.aspose.slides/igroupshape) – Die neu erstellte [IGroupShape](../../com.aspose.slides/igroupshape).
### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbindungslinie mit Standard-Template-Stil und fügt sie am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der hinzuzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Verbindungslinien-Frames in Punkten. |
| y | float | Die y-Koordinate des Verbindungslinien-Frames in Punkten. |
| width | float | Die Breite des Verbindungslinien-Frames in Punkten. |
| height | float | Die Höhe des Verbindungslinien-Frames in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

Erstellt eine neue Verbindungslinie und fügt sie am Ende der Formen-Sammlung hinzu, optional mit Standard-Template-Stil.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der zu erstellenden Verbindungslinie. |
| x | float | Die x-Koordinate des Verbindungslinien-Frames in Punkten. |
| y | float | Die y-Koordinate des Verbindungslinien-Frames in Punkten. |
| width | float | Die Breite des Verbindungslinien-Frames in Punkten. |
| height | float | Die Höhe des Verbindungslinien-Frames in Punkten. |
| createFromTemplate | boolean | true, um den Standard-Template-Stil (nicht leerer Name, einfacher Stil) anzuwenden; false, um die Verbindungslinie mit Standard-Eigenschaften zu erstellen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein, wobei Standard-Template-Stil angewendet wird.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbindungslinie eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Verbindungslinien-Frames in Punkten. |
| y | float | Die y-Koordinate des Verbindungslinien-Frames in Punkten. |
| width | float | Die Breite des Verbindungslinien-Frames in Punkten. |
| height | float | Die Höhe des Verbindungslinien-Frames in Punkten. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract I
```

Erstellt eine neue Verbindungslinie und fügt sie an der angegebenen Position in die Formen-Sammlung ein, optional mit Standard-Template-Stil.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Verbindungslinie eingefügt werden soll. |
| shapeType | int | Der [ShapeType](../../com.aspose.slides/shapetype) der einzufügenden Verbindungslinie. |
| x | float | Die x-Koordinate des Verbindungslinien-Frames in Punkten. |
| y | float | Die y-Koordinate des Verbindungslinien-Frames in Punkten. |
| width | float | Die Breite des Verbindungslinien-Frames in Punkten. |
| height | float | Die Höhe des Verbindungslinien-Frames in Punkten. |
| createFromTemplate | boolean | true, um den Standard-Template-Stil (nicht leerer Name, einfacher Stil) anzuwenden; false, um die Verbindungslinie mit Standard-Eigenschaften zu erstellen. |

**Rückgabewert:**
[IConnector](../../com.aspose.slides/iconnector) – Die neu erstellte [IConnector](../../com.aspose.slides/iconnector).
### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn am Ende der Formen-Sammlung hinzu.

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
| x | float | Die x-Koordinate des Bild-Frames in Punkten. |
| y | float | Die y-Koordinate des Bild-Frames in Punkten. |
| width | float | Die Breite des Bild-Frames in Punkten. |
| height | float | Die Höhe des Bild-Frames in Punkten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) das im Bild-Frame angezeigt wird. |

**Rückgabewert:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Der neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

Erstellt einen neuen Bild-Frame, der das angegebene Bild enthält, und fügt ihn an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem das Bild-Frame eingefügt werden soll. |
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
| x | float | Die x-Koordinate des Bild-Frames in Punkten. |
| y | float | Die y-Koordinate des Bild-Frames in Punkten. |
| width | float | Die Breite des Bild-Frames in Punkten. |
| height | float | Die Höhe des Bild-Frames in Punkten. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | Das [IPPImage](../../com.aspose.slides/ippimage) das im Bild-Frame angezeigt wird. |

**Rückgabewert:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) – Der neu erstellte [IPictureFrame](../../com.aspose.slides/ipictureframe).
### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

Erstellt eine neue Tabelle und fügt sie am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | float | Die x-Koordinate der Tabelle in Punkten. |
| y | float | Die y-Koordinate der Tabelle in Punkten. |
| columnWidths | double[] | Ein Array von Doubles, das die Breiten der Tabellenspalten in Punkten enthält. |
| rowHeights | double[] | Ein Array von Doubles, das die Höhen der Tabellenzeilen in Punkten enthält. |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) – Die neu erstellte [ITable](../../com.aspose.slides/itable).
### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

Erstellt eine neue Tabelle und fügt sie an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die Tabelle eingefügt werden soll. |
| x | float | Die x-Koordinate der Tabelle in Punkten. |
| y | float | Die y-Koordinate der Tabelle in Punkten. |
| columnWidths | double[] | Ein Array von Doubles, das die Breiten der Tabellenspalten in Punkten enthält. |
| rowHeights | double[] | Ein Array von Doubles, das die Höhen der Tabellenzeilen in Punkten enthält. |

**Rückgabewert:**
[ITable](../../com.aspose.slides/itable) – Die neu erstellte [ITable](../../com.aspose.slides/itable).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt die Form am angegebenen Index aus der Formen-Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index der zu entfernenden Form. |
### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

Entfernt das erste Vorkommen der angegebenen Form aus der Formen-Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | Die [IShape](../../com.aspose.slides/ishape) die entfernt werden soll. |
### clear() {#clear--}
```
public abstract void clear()
```

Entfernt alle Formen aus der Formen-Sammlung.
### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende Form. |
| x | float | Die x-Koordinate des geklonten Form-Frames in Punkten. |
| y | float | Die y-Koordinate des geklonten Form-Frames in Punkten. |
| width | float | Die Breite des geklonten Form-Frames in Punkten. |
| height | float | Die Höhe des geklonten Form-Frames in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. Die neue Form behält die Breite und Höhe der  sourceShape  bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |
| x | float | Die x-Koordinate des geklonten Form-Frames in Punkten. |
| y | float | Die y-Koordinate des geklonten Form-Frames in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

Erstellt eine Kopie der angegebenen Form und fügt sie am Ende der Formen-Sammlung hinzu. Die geklonte Form behält die ursprüngliche Position und Größe bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |
| x | float | Die x-Koordinate des geklonten Form-Frames in Punkten. |
| y | float | Die y-Koordinate des geklonten Form-Frames in Punkten. |
| width | float | Die Breite des geklonten Form-Frames in Punkten. |
| height | float | Die Höhe des geklonten Form-Frames in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. Die neue Form behält die Breite und Höhe der  sourceShape  bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |
| x | float | Die x-Koordinate des geklonten Form-Frames in Punkten. |
| y | float | Die y-Koordinate des geklonten Form-Frames in Punkten. |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

Erstellt eine Kopie der angegebenen Form und fügt sie an der angegebenen Position in die Formen-Sammlung ein. Die geklonte Form behält die ursprüngliche Position und Größe bei.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index, an dem die geklonte Form eingefügt werden soll. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | Die zu klonende [IShape](../../com.aspose.slides/ishape). |

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape) – Die neu erstellte [IShape](../../com.aspose.slides/ishape).