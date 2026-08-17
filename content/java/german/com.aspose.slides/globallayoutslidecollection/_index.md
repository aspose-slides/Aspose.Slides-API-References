---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung aller Layout-Folien in einer Präsentation dar.
type: docs
url: /de/com.aspose.slides/globallayoutslidecollection/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Stellt eine Sammlung aller Layout-Folien in einer Präsentation dar. Erweitert die Klasse LayoutSlideCollection mit Methoden zum Hinzufügen/Klonen von Layout-Folien im Kontext der Zusammenführung der einzelnen Sammlungen der Master-Layout-Folien.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Fügt eine neue Layout-Folie zur Präsentation hinzu. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu klonende Folie. |

--------------------

Beim Klonen eines Layouts zwischen verschiedenen Präsentationen kann der Master des Layouts ebenfalls geklont werden, um die Quellformatierung beizubehalten. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone desselben Master-Folien zu verhindern. Manuelles Klonen von Master-Folien wird weder verhindert noch registriert. |

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Fügt eine Kopie einer angegebenen Layout-Folie zur Präsentation hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu klonende Folie. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-Folie für ein neues Layout. |

--------------------

1) Das neue Layout wird mit dem definierten Master in der Zielpräsentation verknüpft. Dies entspricht dem Kopieren/Einfügen mit der Option „Zieldesign verwenden“ in PowerPoint. 2) Das Gegenstück zu dieser Methode ist die Methode [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-), auf die über die Eigenschaft ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) zugegriffen wird. |

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Fügt der Präsentation eine neue Layout-Folie hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-Folie für ein neues Layout. |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wird ein bereits vorhandener Name übergeben, wird eine ArgumentException ausgelöst. Wird null übergeben, wird der Name automatisch in Abhängigkeit vom übergebenen Layout-Typ generiert (zum Beispiel "Title Slide" oder "1_Title Slide", "2_.." usw.). |

--------------------

1) Das hinzugefügte Layout für den Wert SlideLayoutType.Custom von layoutType enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-), auf die über die Eigenschaft ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) zugegriffen wird. |

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.