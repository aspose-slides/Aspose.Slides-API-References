---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av alla layout-bilder för en definierad master-slide.
type: docs
url: /sv/com.aspose.slides/imasterlayoutslidecollection/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Representerar en samling av alla layout-bilder för en definierad master-slide. Utökar ILayoutSlideCollection-gränssnittet med metoder för att lägga till, infoga, ta bort och klona layout-bilder i kontexten för de enskilda samlingarna av master-slide-layoutbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en specificerad layout-slide i slutet av samlingen. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Infogar en kopia av en specificerad layout-slide på angiven position i samlingen. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Lägger till en ny layout-slide i slutet av samlingen. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Infogar en ny layout-slide på angiven position i samlingen. |
| [removeAt(int index)](#removeAt-int-) | Tar bort elementet på angivet index i samlingen. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Flyttar layout-slide från samlingen till den angivna positionen. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Lägger till en kopia av en specificerad layout-slide i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide att klona. |

--------------------

1) Ny layout kommer att länkas till den överordnade master-slide för denna layout-slides-samling. Detta motsvarar kopiera/klistra-in med alternativet "Use Destination Theme" i PowerPoint. 2) En motsvarighet till denna metod är metoden [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) som nås via egenskapen [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Tillagd slide.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Infogar en kopia av en specificerad layout-slide på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya sliden. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide att klona. |

--------------------

Ny layout kommer att länkas till den överordnade master-slide för denna layout-slides-samling. Detta motsvarar kopiera/klistra-in med alternativet "Use Destination Theme" i PowerPoint.

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Infogad slide.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Lägger till en ny layout-slide i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| layoutType | byte | Layout-typ för en ny layout. Stödda layout-typer: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layout-typer stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan används kastas ett ArgumentException. Om en null-parameter skickas genereras namnet automatiskt utifrån angiven layout-typ (till exempel "Title Slide" eller "1\_Title Slide", "2\_.." osv.). |

--------------------

1) Tillagd layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former. 2) En motsvarighet till denna metod är metoden [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) som nås via egenskapen [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Tillagd slide.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Infogar en ny layout-slide på angiven position i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Index för den nya sliden. |
| layoutType | byte | Layout-typ för en ny layout. Stödda layout-typer: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layout-typer stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan används kastas ett ArgumentException. Om en null-parameter skickas genereras namnet automatiskt utifrån angiven layout-typ (till exempel "Title Slide" eller "1\_Title Slide", "2\_.." osv.). |

--------------------

Infogad layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former.

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Infogad slide.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Tar bort elementet på angivet index i samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Det nollbaserade indexet för elementet som ska tas bort. |

--------------------

1) För att undvika att PptxEditException kastas, kontrollera layoutens HasDependingSlides-egenskap innan. 2) Du kan också använda metoden [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) för att förenkla koden.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Flyttar layout-slide från samlingen till den angivna positionen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int | Målindex. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide att flytta. |