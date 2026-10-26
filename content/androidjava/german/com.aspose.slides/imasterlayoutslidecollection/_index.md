---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt eine Sammlung aller Layoutfolien einer definierten Master-Folie dar.
type: docs
url: /de/com.aspose.slides/imasterlayoutslidecollection/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Stellt eine Sammlung aller Layoutfolien einer definierten Master-Folien dar. Erweitert das Interface ILayoutSlideCollection um Methoden zum Hinzufügen/Einfgen/Entfernen/Klonen von Layoutfolien im Kontext der einzelnen Sammlungen der Layoutfolien des Masters.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layoutfolie am Ende der Sammlung hinzu. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layoutfolie an der angegebenen Position der Sammlung ein. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Fügt eine neue Layoutfolie am Ende der Sammlung hinzu. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Fügt eine neue Layoutfolie an der angegebenen Position der Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Verschiebt eine Layoutfolie von der Sammlung zur angegebenen Position. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layoutfolie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Folie zum Klonen. |

--------------------

1) Das neue Layout wird mit der übergeordneten Master-Folien verknüpft für diese Layout-Folien-Sammlung. Dies entspricht dem Kopieren/Einfügen mit der Option “Use Destination Theme” in PowerPoint. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) über die Eigenschaft [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layoutfolie an der angegebenen Position der Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Folie zum Klonen. |

--------------------

Das neue Layout wird mit der übergeordneten Master-Folien verknüpft für diese Layout-Folien-Sammlung. So entspricht es dem Kopieren/Einfügen mit der Option “Use Destination Theme” in PowerPoint.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eingefügte Folie.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Fügt eine neue Layoutfolie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wird ein bereits verwendeter Name übergeben, wird eine ArgumentException ausgelöst. Wird der Parameter null übergeben, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert (z. B. “Title Slide” oder “1\_Title Slide”, “2\_..” usw.). |

--------------------

1) Das hinzugefügte Layout für den Wert SlideLayoutType.Custom von layoutType enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) über die Eigenschaft [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Fügt eine neue Layoutfolie an der angegebenen Position der Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wird ein bereits verwendeter Name übergeben, wird eine ArgumentException ausgelöst. Wird der Parameter null übergeben, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert (z. B. “Title Slide” oder “1\_Title Slide”, “2\_..” usw.). |

--------------------

Das eingefügte Layout für den Wert SlideLayoutType.Custom von layoutType enthält keine Platzhalter und keine Formen.

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

1) Um das Werfen einer PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts. 2) Sie können auch die Methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) verwenden, um den Code zu vereinfachen.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Verschiebt eine Layoutfolie von der Sammlung zur angegebenen Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Ziel-Index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Folie zum Verschieben. |