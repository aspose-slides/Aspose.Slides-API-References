---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides für Android über die Java-API-Referenz
description: Stellt eine Sammlung aller Layout-Folien einer definierten Master-Folie dar.
type: docs
url: /de/com.aspose.slides/masterlayoutslidecollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Stellt eine Sammlung aller Layout-Folien einer definierten Master-Folien dar. Erweitert die Klasse LayoutSlideCollection mit Methoden zum Hinzufügen/Einf��gen/Entfernen/Klonen/Neuordnen von Layout-Folien im Kontext der einzelnen Sammlungen der Master-Folien.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position der Sammlung ein. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Fügt eine neue Layout-Folie am Ende der Sammlung hinzu. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Fügt eine neue Layout-Folie an der angegebenen Position der Sammlung ein. |
| [removeAt(int index)](#removeAt-int-) | Entfernt das Element am angegebenen Index der Sammlung. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Verschiebt die Layout-Folie aus der Sammlung an die angegebene Position. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide zum Klonen. |

--------------------

1) Das neue Layout wird mit dem übergeordneten Master-Slide für diese Layout-Folien-Sammlung verknüpft. Dies entspricht dem Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) über die Eigenschaft ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) zugänglich.

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position der Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide zum Klonen. |

--------------------

Das neue Layout wird mit dem übergeordneten Master-Slide für diese Layout-Folien-Sammlung verknüpft. Dies entspricht dem Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint.

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eingefügte Folie.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Fügt eine neue Layout-Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wird ein bereits verwendeter Name übergeben, wird eine ArgumentException ausgelöst. Wird ein null-Parameter übergeben, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert (z. B. „Title Slide“ oder „1\_Title Slide“, „2\_…“ usw.). |

--------------------

1) Das hinzugefügte Layout für den Wert SlideLayoutType.Custom des layoutType enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) über die Eigenschaft ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) zugänglich.

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Fügt eine neue Layout-Folie an der angegebenen Position der Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| layoutType | byte | Layout-Typ für ein neues Layout. Unterstützte Layout-Typen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere Layout-Typen werden derzeit nicht unterstützt: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wird ein bereits verwendeter Name übergeben, wird eine ArgumentException ausgelöst. Wird ein null-Parameter übergeben, wird der Name automatisch in Bezug auf den übergebenen Layout-Typ generiert (z. B. „Title Slide“ oder „1\_Title Slide“, „2\_…“ usw.). |

--------------------

Das eingefügte Layout für den Wert SlideLayoutType.Custom des layoutType enthält keine Platzhalter und keine Formen.

**Rückgabe:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eingefügte Folie.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements. |

--------------------

1) Um das Auslösen einer PptxEditException zu vermeiden, prüfen Sie zuvor die Eigenschaft HasDependingSlides des Layouts. 2) Sie können auch die Methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) verwenden, um den Code zu vereinfachen.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Verschiebt die Layout-Folie aus der Sammlung an die angegebene Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Ziel-Index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide zum Verschieben. |