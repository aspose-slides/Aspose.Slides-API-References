---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides pro Java API Referenci
description: Reprezentuje kolekci všech rozvržení snímků v prezentaci.
type: docs
url: /cs/com.aspose.slides/igloballayoutslidecollection/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Representuje kolekci všech rozvržení snímků v prezentaci. Rozšiřuje rozhraní ILayoutSlideCollection metodami pro přidávání/klonování rozvržení snímků v kontextu sjednocení jednotlivých kolekcí hlavních rozvržení snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii určeného rozvržení snímku do prezentace. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Přidá kopii určeného rozvržení snímku do prezentace. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Přidá nový snímek rozvržení do prezentace. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Přidá kopii určeného rozvržení snímku do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

Při klonování rozvržení mezi různými prezentacemi může být klonován také hlavní rozvržení, aby se zachovalo formátování zdroje. Interní registr se používá k sledování automaticky klonovaných hlavních rozvržení, aby se zabránilo vytvoření více kopií stejného hlavního snímku. Ruční klonování hlavních snímků nebude ani zabráněno, ani registrováno. |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Přidá kopii určeného rozvržení snímku do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek pro nové rozvržení. |

--------------------

Nové rozvržení bude spojeno s definovaným hlavním snímkem v cílové prezentaci. Takže se jedná o ekvivalent kopírování/vkládání s volbou "Use Destination Theme" v PowerPointu. |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Přidá nový snímek rozvržení do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek pro nové rozvržení. |
| layoutType | byte | Typ rozvržení pro nové rozvržení. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Další typy rozvržení nyní nejsou podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název pro nové rozvržení. Pokud je předávaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název vygenerován automaticky podle zadaného typu rozvržení (například "Title Slide" nebo "1_Title Slide", "2_.." atd.). |

--------------------

1) Přidané rozvržení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné znaky ani tvary. 2) Ekvivalent této metody je metoda [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) přístupná přes vlastnost ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Vrací:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.