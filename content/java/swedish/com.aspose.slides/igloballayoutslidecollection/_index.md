---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides för Java API-referens
description: Representerar en samling av alla layoutbilder i en presentation.
type: docs
url: /sv/com.aspose.slides/igloballayoutslidecollection/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Representerar en samling av alla layoutbilder i en presentation. Ärver ILayoutSlideCollection-gränssnittet med metoder för att lägga till/klona layoutbilder i samband med förening av de individuella samlingarna av mästares layoutbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Lägger till en kopia av en specificerad layoutbild i presentationen. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Lägger till en kopia av en specificerad layoutbild i presentationen. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Lägger till en ny layoutbild i presentationen. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Lägger till en kopia av en specificerad layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona.

--------------------

När en layout klonas mellan olika presentationer kan layoutens master också klonas för att behålla källformatet. Ett internt register används för att spåra automatiskt klonade masters och förhindra skapandet av flera kloner av samma mastersida. Manuell kloning av mastersidor varken hindras eller registreras. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Tillagd bild.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Lägger till en kopia av en specificerad layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Bild att klona. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mastersida för den nya layouten.

--------------------

Den nya layouten kommer att länkas till den definierade mastern i destinationspresentationen. Så detta är en analogi till kopiera/klistra in med alternativet "Use Destination Theme" i PowerPoint. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Tillagd bild.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Lägger till en ny layoutbild i presentationen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mastersida för en ny layout. |
| layoutType | byte | Layouttyp för en ny layout. Stödda layouttyper: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andra layouttyper stöds för närvarande ej: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Namn för en ny layout. Om angivet namn redan används kastas ArgumentException. Om null-parameter skickas genereras namn automatiskt utifrån angiven layouttyp (t.ex. "Title Slide" eller "1\_Title Slide", "2\_..", etc.).

--------------------

1) Tillagd layout för värdet SlideLayoutType.Custom för layoutType innehåller inga platshållare och inga former. 2) En analog i denna metod är metod [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) som nås via egenskapen ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Tillagd bild.