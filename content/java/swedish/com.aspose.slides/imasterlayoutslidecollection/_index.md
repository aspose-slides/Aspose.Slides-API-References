---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av alla layoutbilder för en definierad masterbild.
type: docs
url: /sv/com.aspose.slides/imasterlayoutslidecollection/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Representerar en samling av alla layoutbilder för en definierad masterbild. Ärver ILayoutSlideCollection-gränssnittet med metoder för att lägga till/infoga/ta bort/klona layoutbilder i kontexten av de individuella samlingarna av masterens layoutbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en specificerad layoutbild i slutet av samlingen. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en specificerad layoutbild på den angivna positionen i samlingen. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Lägger till en ny layoutbild i slutet av samlingen. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Infogar en ny layoutbild på den angivna positionen i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Flyttar layoutbild från samlingen till den angivna positionen. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Lägger till en kopia av en specificerad layoutbild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona.

--------------------

1) Det nya layoutet kommer att länkas till överordnad masterbild för denna layoutbildssamling. Detta motsvarar kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint. 2) En motsvarande metod för detta är metoden [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) som nås via egenskapen [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd slide.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Infogar en kopia av en specificerad layoutbild på den angivna positionen i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona.

--------------------

Det nya layoutet kommer att länkas till överordnad masterbild för denna layoutbildssamling. Detta motsvarar kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint.

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Infogad slide.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```


Lägger till en ny layoutbild i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan är i bruk kastas ett ArgumentException. Om en null-parameter skickas genereras namnet automatiskt utifrån den angivna layouttypen (t.ex. "Title Slide" eller "1\_Title Slide", "2\_..", osv.). |

--------------------

1) Tillagd layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former. 2) En motsvarande metod för detta är metoden [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) som nås via egenskapen [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd slide.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Infogar en ny layoutbild på den angivna positionen i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya bilden. |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan är i bruk kastas ett ArgumentException. Om en null-parameter skickas genereras namnet automatiskt utifrån den angivna layouttypen (t.ex. "Title Slide" eller "1\_Title Slide", "2\_..", osv.). |

--------------------

Infogad layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former.

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Infogad slide.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Tar bort elementet på det angivna indexet i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort.

--------------------

1) För att undvika att ett PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap i förväg. 2) Du kan även använda metoden [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) för att förenkla koden.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```


Flyttar layoutbild från samlingen till den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att flytta. |