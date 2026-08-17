---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides für Java API Referenz
description: Stellt eine Sammlung aller Layout-Folien einer definierten Master-Folie dar.
type: docs
url: /de/com.aspose.slides/imasterlayoutslidecollection/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Stellt eine Sammlung aller Layout-Folien einer definierten Master-Folie dar. Erweitert die Schnittstelle ILayoutSlideCollection um Methoden zum Hinzufügen/Einfügen/Entfernen/Klonen von Layout-Folien im Kontext der einzelnen Sammlungen von Master-Layout-Folien.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position in die Sammlung ein. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Fügt eine neue Layout-Folie am Ende der Sammlung hinzu. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Fügt eine neue Layout-Folie an der angegebenen Position in die Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Verschiebt eine Layout-Folie innerhalb der Sammlung an die angegebene Position. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu klonende Folie. |

--------------------

1) Das neue Layout wird mit der übergeordneten Master-Folie dieser Layout-Folien-Sammlung verknüpft. Es entspricht also Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-), auf die über die Eigenschaft [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) zugegriffen wird.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu klonende Folie. |

--------------------

Das neue Layout wird mit der übergeordneten Master-Folie dieser Layout-Folien-Sammlung verknüpft. Es entspricht also Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eingefügte Folie.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Fügt eine neue Layout-Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wird ein bereits vorhandener Name übergeben, wird eine ArgumentException ausgelöst. Wird null übergeben, wird der Name automatisch basierend auf dem übergebenen Layout-Typ generiert (z. B. „Title Slide“ oder „1\_Title Slide“, „2\_…“ usw.). |

--------------------

1) Das hinzugefügte Layout für den Wert SlideLayoutType.Custom des layoutType enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-), auf die über die Eigenschaft [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) zugegriffen wird.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Fügt eine neue Layout-Folie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wird ein bereits vorhandener Name übergeben, wird eine ArgumentException ausgelöst. Wird null übergeben, wird der Name automatisch basierend auf dem übergebenen Layout-Typ generiert (z. B. „Title Slide“ oder „1\_Title Slide“, „2\_…“ usw.). |

--------------------

Das eingefügte Layout für den Wert SlideLayoutType.Custom des layoutType enthält keine Platzhalter und keine Formen.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eingefügte Folie.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

--------------------

1) Um das Werfen einer PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts. 2) Sie können zudem die Methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) verwenden, um den Code zu vereinfachen.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Verschiebt eine Layout-Folie innerhalb der Sammlung an die angegebene Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Ziel-Index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu verschiebende Folie. |