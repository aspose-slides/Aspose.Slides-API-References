---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje kolekci všech snímků rozložení v prezentaci.
type: docs
url: /cs/com.aspose.slides/igloballayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Reprezentuje kolekci všech snímků rozložení v prezentaci. Rozšiřuje rozhraní ILayoutSlideCollection metodami pro přidávání/klonování snímků rozložení v kontextu sjednocování jednotlivých kolekcí hlavních snímků rozložení.

## Methods

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii zadaného snímku rozložení do prezentace. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Přidá kopii zadaného snímku rozložení do prezentace. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Přidá nový snímek rozložení do prezentace. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Přidá kopii zadaného snímku rozložení do prezentace.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

Při klonování rozložení mezi různými prezentacemi může být také klonován hlavní snímek rozložení, aby se zachovalo formátování zdroje. Interní registr je používán k automatickému sledování klonovaných hlav, aby se zabránilo vytvoření více klonů stejného hlavního snímku. Ruční klonování hlavních snímků není ani zabráněno, ani registrováno. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Přidá kopii zadaného snímku rozložení do prezentace.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek pro nové rozložení. |

--------------------

Nové rozložení bude propojeno s definovaným hlavním snímkem v cílové prezentaci. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Přidá nový snímek rozložení do prezentace.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek pro nové rozložení. |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozložení nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název pro nové rozložení. Pokud je předaný název již používán, bude vyhozena výjimka ArgumentException. Pokud je předán parametr null, bude název vygenerován automaticky vzhledem k předanému typu rozložení (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

--------------------

1) Přidané rozložení pro hodnotu SlideLayoutType.Custom z layoutType neobsahuje žádné zástupné symboly ani tvary. 2) Analogií této metody je metoda [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) přístupná pomocí ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) vlastnosti. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.