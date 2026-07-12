---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides Androidra Java API hivatkozás
description: A prezentáció összes elrendezési diáját tartalmazó gyűjteményt képviseli.
type: docs
url: /hu/com.aspose.slides/igloballayoutslidecollection/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

A prezentáció összes elrendezési diáját tartalmazó gyűjteményt képviseli. Kibővíti az ILayoutSlideCollection interfészt olyan módszerekkel, amelyek lehetővé teszik elrendezési diák hozzáadását vagy klónozását a mester-diák egyedi gyűjteményeinek egyesítése során.
## Metódusok

| Módszer | Leírás |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | A megadott elrendezési dia egy másolatát adja hozzá a prezentációhoz. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | A megadott elrendezési dia egy másolatát adja hozzá a prezentációhoz. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Új elrendezési diát ad a prezentációhoz. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


A megadott elrendezési dia egy másolatát adja hozzá a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia.

--------------------

Különböző prezentációk között elrendezést klónozva az elrendezés mestere is klónozható, hogy megőrizze a forrás formázását. Egy belső nyilvántartás segítségével nyomon követik az automatikusan klónozott mestereket, így elkerülhető ugyanazon mesterdia több klónjának létrehozása. A mesterdiák manuális klónozása sem lesz megakadályozva, sem nyilvántartva. |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


A megadott elrendezési dia egy másolatát adja hozzá a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új elrendezés mesterdiája.

--------------------

Az új elrendezés a célprezentációban meghatározott mesterhez lesz kapcsolva. Így ez a PowerPoint „Use Destination Theme” opcióval történő másolás/beillesztés analógiája. |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Új elrendezési diát ad a prezentációhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Új elrendezés mesterdiája. |
| layoutType | byte | Az új elrendezés típusa. Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paramétert adunk meg, a név automatikusan a megadott layout type alapján generálódik (például „Title Slide” vagy „1\_Title Slide”, „2\_..” stb.). |

--------------------

1) Az SlideLayoutType.Custom értékű layoutType esetén hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a metódusnak az analógiája a [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) metódus, amely a ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) tulajdonsággal érhető el. |

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.