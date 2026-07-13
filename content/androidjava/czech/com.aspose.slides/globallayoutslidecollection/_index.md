---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Představuje kolekci všech snímků rozvržení v prezentaci.
type: docs
url: /cs/com.aspose.slides/globallayoutslidecollection/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Všechny implementované rozhraní:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Představuje kolekci všech snímků rozvržení v prezentaci. Rozšiřuje třídu LayoutSlideCollection metodami pro přidávání/klonování snímků rozvržení v kontextu sjednocování jednotlivých kolekcí snímků rozvržení mistra.
## Metody

| Metoda | Popis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii určeného snímku rozvržení do prezentace. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Přidá kopii určeného snímku rozvržení do prezentace. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Přidá nový snímek rozvržení do prezentace. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Přidá kopii určeného snímku rozvržení do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování.

--------------------

Při klonování rozvržení mezi různými prezentacemi může být také klonován hlavní snímek rozvržení, aby byl zachován formát zdroje. Interní registr se používá k sledování automaticky klonovaných hlavních snímků, aby se zabránilo vytvoření více kopií stejného hlavního snímku. Ruční klonování hlavních snímků nebude ani zabráněno, ani zaznamenáno. 

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Přidá kopii určeného snímku rozvržení do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek pro nové rozvržení.

--------------------

1) Nové rozvržení bude propojeno s definovaným hlavním snímkem v cílové prezentaci. Jedná se tedy o analogii kopírování/vkládání s možností „Use Destination Theme“ v PowerPointu. 2) Analogií této metody je metoda [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) přístupná přes vlastnost ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). 

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Přidá nový snímek rozvržení do prezentace.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Hlavní snímek pro nové rozvržení. |
| layoutType | byte | Typ rozvržení pro nové rozvržení. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozvržení nejsou nyní podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název pro nové rozvržení. Pokud je předaný název již používán, bude vyhozena výjimka ArgumentException. Pokud je předán parametr null, bude název vygenerován automaticky podle zadaného typu rozvržení (například „Title Slide“ nebo „1_Title Slide“, „2_..“ atd.). |

--------------------

1) Přidané rozvržení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné znaky ani tvary. 2) Analogií této metody je metoda [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) přístupná přes vlastnost ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). 

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.