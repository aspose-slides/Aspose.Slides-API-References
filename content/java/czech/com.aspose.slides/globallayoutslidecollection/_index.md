---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje kolekci všech rozložení snímků v prezentaci.
type: docs
url: /cs/com.aspose.slides/globallayoutslidecollection/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Representuje kolekci všech rozložení snímků v prezentaci. Rozšiřuje třídu LayoutSlideCollection metodami pro přidávání/klonování rozložení snímků v kontextu sjednocování jednotlivých kolekcí rozložení hlavních snímků.
## Metody

| Metoda | Popis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii určeného rozložení snímku do prezentace. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Přidá kopii určeného rozložení snímku do prezentace. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Přidá nové rozložení snímku do prezentace. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Přidá kopii určeného rozložení snímku do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

Při klonování rozložení mezi různými prezentacemi může být také klonován master rozložení, aby byl zachován formát zdroje. Vnitřní registr se používá k sledování automaticky klonovaných masterů, aby se zabránilo vytvoření více kopií stejného master snímku. Manuální klonování master snímků nebude ani zabráněno, ani registrováno.

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Přidá kopii určeného rozložení snímku do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master snímek pro nové rozložení. |

--------------------

1) Nové rozložení bude propojeno s definovaným masterem v cílové prezentaci. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. 2) Ekvivalent této metody je metoda [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) přístupná přes vlastnost ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Přidá nové rozložení snímku do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master snímek pro nové rozložení. |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název pro nové rozložení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, pak bude název automaticky vygenerován s ohledem na předaný typ rozložení (například „Title Slide“ nebo „1\_Title Slide“, „2\_..“ atd.). |

--------------------

1) Přidané rozložení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné výrazy ani tvary. 2) Ekvivalent této metody je metoda [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) přístupná přes vlastnost ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.