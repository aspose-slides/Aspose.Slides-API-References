---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides Java API referencia
description: Egy gyűjteményt képvisel, amely a prezentáció összes elrendezési diáját tartalmazza.
type: docs
url: /hu/com.aspose.slides/igloballayoutslidecollection/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Egy gyűjteményt képvisel, amely a prezentáció összes elrendezési diáját tartalmazza. Kiterjeszti az ILayoutSlideCollection interfészt olyan módszerekkel, amelyek elrendezési diák hozzáadására/klónozására szolgálnak a mester elrendezési diák egyedi gyűjteményeinek egyesítése kontextusában.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Hozzáad egy megadott elrendezési dia másolatát a prezentációhoz. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Hozzáad egy megadott elrendezési dia másolatát a prezentációhoz. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Új elrendezési diát ad hozzá a prezentációhoz. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Hozzáad egy megadott elrendezési dia másolatát a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | A klónozandó dia. |
|  |  |  |
--------------------

Különböző prezentációk között elrendezés klónozása esetén az elrendezés mesterét is klónozhatjuk a forrás formázásának megőrzése érdekében. Belső nyilvántartás használatos az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozza ugyanazon mester dia többszörös klónjainak létrehozását. A mester diákat manuálisan klónozni sem tiltott, sem nem kerül nyilvántartásba. |
**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Hozzáad egy megadott elrendezési dia másolatát a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | A klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Az új elrendezéshez tartozó mester dia. |
|  |  |  |
--------------------

Az új elrendezés a célprezentációban meghatározott mesterrel lesz összekapcsolva. Ez tehát a PowerPointban a “Use Destination Theme” opcióval történő másolás/beillesztés analógiája. |
**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Új elrendezési diát ad hozzá a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Az új elrendezéshez tartozó mester dia. |
| layoutType | byte | Az új elrendezés típusát. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. A többi elrendezési típus jelenleg nem támogatott: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException kivételt dob. Ha null paramétert adnak meg, akkor a név automatikusan generálódik a megadott layout type alapján (például "Title Slide" vagy "1\_Title Slide", "2\_..", stb.). |
|  |  |  |
--------------------

1) A SlideLayoutType.Custom értékhez hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak az analógiája a [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) metódus, amely a ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) tulajdonnal érhető el. |
**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.