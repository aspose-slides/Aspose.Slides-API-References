---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av alla layoutbilder i en definierad masterslide.
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

Representerar en samling av alla layoutbilder i en definierad masterslide. Ärver LayoutSlideCollection klass med metoder för att lägga till/infoga/ta bort/klona/ordna om layoutbilder i sammanhanget av de individuella samlingarna av masterslides layoutbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en specificerad layoutslide i slutet av samlingen. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en specificerad layoutslide på en angiven position i samlingen. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Lägger till en ny layoutslide i slutet av samlingen. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Infogar en ny layoutslide på en angiven position i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på det angivna indexet i samlingen. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Flyttar layoutslide från samlingen till den angivna positionen. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Lägger till en kopia av en specificerad layoutslide i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide att klona.

--------------------

1) Ny layout kommer att länkas till den överordnade mastersliden för den här layoutbildssamlingen. Så detta är en analogi till klipp/klistra med alternativet "Use Destination Theme" i PowerPoint. 2) En analogi till denna metod är metod [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) som nås via ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) egenskap. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Infogar en kopia av en specificerad layoutslide på en angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ny slide. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide att klona.

--------------------

Ny layout kommer att länkas till den överordnade mastersliden för den här layoutbildssamlingen. Så detta är en analogi till klipp/klistra med alternativet "Use Destination Theme" i PowerPoint. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Infogad bild.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Lägger till en ny layoutslide i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan används kastas ArgumentException. Om null skickas som parameter genereras namnet automatiskt utifrån den angivna layouttypen (t.ex. "Title Slide" eller "1_Title Slide", "2_..", etc.).

--------------------

1) Lagt till layout för värdet SlideLayoutType.Custom av layoutType som inte innehåller platshållare eller former. 2) En analogi till denna metod är metod [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) som nås via ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) egenskap. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Infogar en ny layoutslide på en angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för ny slide. |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan används kastas ArgumentException. Om null skickas som parameter genereras namnet automatiskt utifrån den angivna layouttypen (t.ex. "Title Slide" eller "1_Title Slide", "2_..", etc.).

--------------------

Lagd till layout för värdet SlideLayoutType.Custom av layoutType som inte innehåller platshållare eller former. |

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
| index | int | Det nollbaserade indexet för elementet som ska tas bort.

--------------------

1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides egenskap först. 2) Du kan även använda [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metod för att förenkla kod. |
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Flyttar layoutslide från samlingen till den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide att flytta. |