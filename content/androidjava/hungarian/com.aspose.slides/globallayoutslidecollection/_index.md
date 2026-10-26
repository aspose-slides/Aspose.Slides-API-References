---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides for Android Java API referencia
description: A prezentáció összes elrendezési dia gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/globallayoutslidecollection/
---
**Öröklődés:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Az összes megvalósított interfész:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Az összes elrendezési diát tartalmazó gyűjteményt képviseli a prezentációban. Kiterjeszti a LayoutSlideCollection osztályt, amely a mester elrendezések egyedi gyűjteményeinek egyesítésének kontextusában adhat hozzá/klónozhat elrendezési diákot.
## Módszerek

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Adds a new layout slide to the presentation. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Adds a copy of a specified layout slide to the presentation.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | A klónozandó dia.

--------------------

Amikor egy elrendezést különböző prezentációk között klónozunk, a mester is klónozható, hogy megőrizze a forrás formázását. Belső regisztert használnak a automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia többszöri klónozását. A mesterdia kézi klónozása sem nem lesz megakadályozva, sem nem kerül regisztrációra. |

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Hozzáadott dia.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Adds a copy of a specified layout slide to the presentation.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | A klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mester dia az új elrendezéshez.

--------------------

1) Az új elrendezés a célprezentációban meghatározott mesterről kap linket. Így ez a PowerPoint „Use Destination Theme” opcióval történő másolás/beillesztés analógja. 2) Ennek a metódusnak az analógja a [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) metódus, amely a ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) tulajdonsággal érhető el. |

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Hozzáadott dia.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Adds a new layout slide to the presentation.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Mester dia az új elrendezéshez. |
| layoutType | byte | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Name for a new layout. If passed name is already in use the ArgumentException will be thrown. If null parameter is passed then name genarated atomatically in regards to passed layout type (for example "Title Slide" or "1\_Title Slide", "2\_..", etc.).

--------------------

1) A SlideLayoutType.Custom értékű layoutType esetén a hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak az analógja a [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) metódus, amely a ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) tulajdonsággal érhető el. |

**Visszatér:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Hozzáadott dia.