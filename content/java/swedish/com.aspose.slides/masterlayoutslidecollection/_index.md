---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av alla layoutbilder för en definierad masternslide.
type: docs
url: /sv/com.aspose.slides/masterlayoutslidecollection/
---
**Arv:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Representerar en samling av alla layoutbilder för en definierad masternslide. Ärver LayoutSlideCollection-klassen med metoder för att lägga till/infoga/ta bort/klona/omordna layoutbilder i kontexten av de individuella samlingarna av masterns layoutbilder.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en angiven layoutbild i slutet av samlingen. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en angiven layoutbild på angiven position i samlingen. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Lägger till en ny layoutbild i slutet av samlingen. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Infogar en ny layoutbild på angiven position i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Flyttar layoutbild från samlingen till den angivna positionen. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Lägger till en kopia av en angiven layoutbild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona. |

--------------------

1) Ny layout kommer att länkas till den överordnade masternsliden för denna layoutbildssamling. Så detta är motsvarigheten till kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint. 2) Motsvarigheten till denna metod är metoden [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) som nås via egenskapen ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Lagt till bild.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Infogar en kopia av en angiven layoutbild på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ny bild. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona. |

--------------------

Ny layout kommer att länkas till den överordnade masternsliden för denna layoutbildssamling. Så detta är motsvarigheten till kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint.

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Infogad bild.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Lägger till en ny layoutbild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan är i bruk kastas ArgumentException. Om null-parameter ges genereras namnet automatiskt med hänsyn till den angivna layouttypen (t.ex. "Title Slide" eller "1_Title Slide", "2_.." osv.). |

--------------------

1) Tillagd layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former. 2) Motsvarigheten till denna metod är metoden [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) som nås via egenskapen ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Lagt till bild.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Infogar en ny layoutbild på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ny bild. |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan är i bruk kastas ArgumentException. Om null-parameter ges genereras namnet automatiskt med hänsyn till den angivna layouttypen (t.ex. "Title Slide" eller "1_Title Slide", "2_.." osv.). |

--------------------

Infogad layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former.

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Infogad bild.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

--------------------

1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap först. 2) Du kan också använda metoden [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) för att förenkla koden.
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Flyttar layoutbild från samlingen till den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att flytta. |