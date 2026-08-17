---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine Sammlung aller Layout-Folien einer definierten Master-Folie dar.
type: docs
url: /de/com.aspose.slides/masterlayoutslidecollection/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Stellt eine Sammlung aller Layout-Folien einer definierten Master-Folie dar. Erweitert die Klasse LayoutSlideCollection mit Methoden zum Hinzufügen/Einfügen/Entfernen/Klonen/Umsortieren von Layout-Folien im Kontext der einzelnen Sammlungen der Layout-Folien des Masters.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie am Ende der Sammlung hinzu. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position in die Sammlung ein. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Fügt eine neue Layout-Folie am Ende der Sammlung hinzu. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Fügt eine neue Layout-Folie an der angegebenen Position in die Sammlung ein. |
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
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Folie zum Klonen.

--------------------

1) Das neue Layout wird mit der übergeordneten Master-Folie für diese Layout-Folien-Sammlung verknüpft. Dies entspricht also Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) über die Eigenschaft ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) zugänglich.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Fügt eine Kopie einer angegebenen Layout-Folie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Folie zum Klonen.

--------------------

Neues Layout wird mit der übergeordneten Master-Folie für diese Layout-Folien-Sammlung verknüpft. Dies entspricht also Kopieren/Einfügen mit der Option „Use Destination Theme“ in PowerPoint.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eingefügte Folie.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Fügt eine neue Layout-Folie am Ende der Sammlung hinzu.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| layoutType | byte | Layouttyp für ein neues Layout. Unterstützte Layouttypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst. Ist der Parameter null, wird der Name automatisch in Abhängigkeit vom übergebenen Layouttyp generiert (z. B. „Title Slide“ oder „1_Title Slide“, „2_…“ usw.). |

--------------------

1) Hinzugefügtes Layout für den Wert SlideLayoutType.Custom von layoutType enthält keine Platzhalter und keine Formen. 2) Das Gegenstück zu dieser Methode ist die Methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) über die Eigenschaft ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) zugänglich.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hinzugefügte Folie.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Fügt eine neue Layout-Folie an der angegebenen Position in die Sammlung ein.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Index der neuen Folie. |
| layoutType | byte | Layouttyp für ein neues Layout. Unterstützte Layouttypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name für ein neues Layout. Wenn der übergebene Name bereits verwendet wird, wird eine ArgumentException ausgelöst. Ist der Parameter null, wird der Name automatisch in Abhängigkeit vom übergebenen Layouttyp generiert (z. B. „Title Slide“ oder „1_Title Slide“, „2_…“ usw.). |

--------------------

Eingefügtes Layout für den Wert SlideLayoutType.Custom von layoutType enthält keine Platzhalter und keine Formen.

**Rückgabewert:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Eingefügte Folie.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Entfernt das Element am angegebenen Index der Sammlung.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Der nullbasierte Index des zu entfernenden Elements.

--------------------

1) Um das Werfen der PptxEditException zu vermeiden, prüfen Sie vorher die Eigenschaft HasDependingSlides des Layouts. 2) Sie können außerdem die Methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) verwenden, um den Code zu vereinfachen.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Verschiebt die Layout-Folie aus der Sammlung an die angegebene Position.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Zielindex. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Zu verschiebende Folie.