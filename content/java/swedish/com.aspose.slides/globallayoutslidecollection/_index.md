---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av alla layoutbilder i en presentation.
type: docs
url: /sv/com.aspose.slides/globallayoutslidecollection/
---
**Arv:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Representerar en samling av alla layoutbilder i en presentation. Ärver LayoutSlideCollection-klassen med metoder för att lägga till/klona layoutbilder i samband med förening av de enskilda samlingarna av mästares layoutbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en specificerad layoutbild i presentationen. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Lägger till en kopia av en specificerad layoutbild i presentationen. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Lägger till en ny layoutbild i presentationen. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Lägger till en kopia av en specificerad layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona. |

--------------------

När en layout klonas mellan olika presentationer kan layoutens master också klonas för att behålla källformateringen. Ett internt register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma masterbild. Manuellt kloning av masterbilder kommer varken att förhindras eller registreras.

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Lägger till en kopia av en specificerad layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbild för en ny layout. |

--------------------

1) Den nya layouten kommer att länkas till den definierade mastern i destinationspresentationen. Så detta motsvarar kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint. 2) Motsvarigheten till denna metod är metoden [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) som nås via egenskapen ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Lägger till en ny layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterbild för en ny layout. |
| layoutType | byte | Layouttype för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan används kastas ett ArgumentException. Om null-parametern skickas genereras namnet automatiskt i förhållande till den angivna layouttypen (till exempel "Title Slide" eller "1\_Title Slide", "2\_..", etc.). |

--------------------

1) Tillagd layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former. 2) Motsvarigheten till denna metod är metoden [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) som nås via egenskapen ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.