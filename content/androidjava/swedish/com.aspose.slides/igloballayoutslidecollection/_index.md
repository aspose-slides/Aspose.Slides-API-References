---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en samling av alla layoutbilder i presentationen.
type: docs
url: /sv/com.aspose.slides/igloballayoutslidecollection/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Representerar en samling av alla layoutbilder i presentationen. Utökar ILayoutSlideCollection-gränssnittet med metoder för att lägga till/klona layoutbilder i samband med att förena de enskilda samlingarna av mästarens layoutbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en angiven layoutbild i presentationen. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Lägger till en kopia av en angiven layoutbild i presentationen. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Lägger till en ny layoutbild i presentationen. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Lägger till en kopia av en angiven layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona.

--------------------

När en layout klonas mellan olika presentationer kan layoutens master också klonas för att behålla källformatet. Ett internt register används för att spåra automatiskt klonade mastrar för att förhindra skapandet av flera kloner av samma master-bild. Manuell kloning av master-bilder varken hindras eller registreras. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Lägger till en kopia av en angiven layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-bild för den nya layouten.

--------------------

Den nya layouten kommer att länkas till den definierade master-bilden i målpresentationen. Detta är analogt med kopiera/klistra in med alternativet ”Use Destination Theme” i PowerPoint. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Lägger till en ny layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master-bild för den nya layouten. |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouter: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouter stöds för närvarande inte: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om det angivna namnet redan används kastas ArgumentException. Om null skickas som parameter genereras namn automatiskt utifrån angiven layouttyp (t.ex. ”Title Slide” eller ”1_Title Slide”, ”2_..”, osv.).

--------------------

1) En layout för värdet SlideLayoutType.Custom av layoutType innehåller inga platshållare och inga former. 2) Analogen till denna metod är metoden [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) som nås via egenskapen ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Tillagd bild.