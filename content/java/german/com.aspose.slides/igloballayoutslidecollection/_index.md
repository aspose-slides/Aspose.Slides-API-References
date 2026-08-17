---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Sammlung aller Layout-Folien in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/igloballayoutslidecollection/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Stellt eine Sammlung aller Layout-Folien in einer Präsentation dar. Erweitert die Schnittstelle ILayoutSlideCollection um Methoden zum Hinzufügen/Klonen von Layout-Folien im Kontext der Zusammenführung der einzelnen Sammlungen der Master-Layout-Folien.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folien zur Präsentation hinzu. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Layout-Folien zur Präsentation hinzu. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Fügt der Präsentation eine neue Layout-Folie hinzu. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layout-Folien zur Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu klonende Folie. |

--------------------

Beim Klonen eines Layouts zwischen verschiedenen Präsentationen kann der Master des Layouts ebenfalls geklont werden, um die Quellformatierung beizubehalten. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen, um die Erstellung mehrerer Klone derselben Master-Folien zu verhindern. Das manuelle Klonen von Master-Folien wird weder verhindert noch registriert.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Fügt eine Kopie einer angegebenen Layout-Folien zur Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu klonende Folie. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-Folie für ein neues Layout. |

--------------------

Das neue Layout wird mit dem im Ziel-Präsentation definierten Master verknüpft. Es ist also das Gegenstück zu Kopieren/Einfügen mit der Option „Ziel-Design verwenden“ in PowerPoint.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Fügt der Präsentation eine neue Layout-Folie hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-Folie für ein neues Layout. |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst. Wird ein null-Parameter übergeben, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert (z. B. „Title Slide“ oder „1\_Title Slide“, „2\_…“ usw.). |

--------------------

1) Hinzugefügtes Layout für den Wert SlideLayoutType.Custom von layoutType enthält keine Platzhalter und keine Formen.  
2) Das Gegenstück zu dieser Methode ist die Methode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-), auf die über die Eigenschaft ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) zugegriffen wird.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.