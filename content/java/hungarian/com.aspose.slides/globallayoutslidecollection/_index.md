---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides Java API Referenciája
description: A prezentációban lévő összes elrendezésdia gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/globallayoutslidecollection/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Minden megvalósított interfész:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

A prezentációban lévő összes elrendezésdia gyűjteményét képviseli. Kiterjeszti a LayoutSlideCollection osztályt olyan módszerekkel, amelyek elrendezésdiák hozzáadását/klónozását teszik lehetővé a mesterelrendezés diák egyedi gyűjteményeinek egyesítése során.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Hozzáad egy másolatot egy megadott elrendezésdiáról a prezentációhoz. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Hozzáad egy másolatot egy megadott elrendezésdiáról a prezentációhoz. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Új elrendezésdát ad a prezentációhoz. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Hozzáad egy másolatot egy megadott elrendezésdiáról a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia.

--------------------

Amikor egy elrendezést különböző prezentációk között klónozunk, az elrendezés mesterét is klónozhatjuk, hogy megőrizzük a forrás formázását. Egy belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanannak a mesterdiának a többszörös klónozását. A mesterdiák kézi klónozása sem nem lesz megakadályozva, sem regisztrálva.

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Hozzáad egy másolatot egy megadott elrendezésdiáról a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mesterdia az új elrendezéshez.

--------------------

1) Az új elrendezés a célprezentációban definiált mesterhez lesz kapcsolva. Így ez a PowerPointban a "Use Destination Theme" opcióval végzett másolás/beillesztés analógja. 2) Ennek a metódusnak az analógja a [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) metódus, amely a ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) tulajdonságon keresztül érhető el.

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Új elrendezésdát ad a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mesterdia az új elrendezéshez. |
| layoutType | byte | Az új elrendezés típusa. Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Egyéb elrendezéstípusok jelenleg nem támogatottak: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException kivételt dob. Ha null paramétert adunk meg, akkor a név automatikusan generálódik a megadott layoutType alapján (például "Title Slide" vagy "1_Title Slide", "2_.." stb.). |

--------------------

1) A SlideLayoutType.Custom értékhez tartozó layout hozzáadása nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak az analógja a [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) metódus, amely a ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) tulajdonságon keresztül érhető el.

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.