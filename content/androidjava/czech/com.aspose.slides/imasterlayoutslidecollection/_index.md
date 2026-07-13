---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje kolekci všech rozložení snímků definovaného hlavního snímku.
type: docs
url: /cs/com.aspose.slides/imasterlayoutslidecollection/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Representuje kolekci všech rozložení snímků definovaného hlavního snímku. Rozšiřuje rozhraní ILayoutSlideCollection metodami pro přidávání/vkládání/odstraňování/klonování rozložení snímků v kontextu jednotlivých kolekcí rozložení hlavního snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii zadaného rozložení snímku na konec kolekce. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Vloží kopii zadaného rozložení snímku na určenou pozici v kolekci. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Přidá nové rozložení snímku na konec kolekce. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Vloží nové rozložení snímku na určenou pozici v kolekci. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Přesune rozložení snímku v kolekci na určenou pozici. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Přidá kopii zadaného rozložení snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování.

--------------------

1) Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci rozložení snímků. Jedná se o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) přístupná přes vlastnost [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides). |

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Přidaný snímek.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Vloží kopii zadaného rozložení snímku na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování.

--------------------

Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci rozložení snímků. Jedná se o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. |

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Vložený snímek.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```


Přidá nové rozložení snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název nového rozložení. Pokud je zadaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je parametr null, bude název automaticky vygenerován podle zadaného typu rozložení (např. „Title Slide“ nebo „1_Title Slide“, „2_…“ apod.). |

--------------------

1) Přidané rozložení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné znaky ani tvary. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) přístupná přes vlastnost [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides). |

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Přidaný snímek.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Vloží nové rozložení snímku na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název nového rozložení. Pokud je zadaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je parametr null, bude název automaticky vygenerován podle zadaného typu rozložení (např. „Title Slide“ nebo „1_Title Slide“, „2_…“ apod.). |

--------------------

Vložené rozložení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné znaky ani tvary. |

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) – Vložený snímek.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn.

--------------------

1) Pro zamezení vyhození výjimky PptxEditException zkontrolujte předem vlastnost HasDependingSlides rozložení. 2) K zjednodušení kódu můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove). |

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```


Přesune rozložení snímku v kolekci na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek k přesunu. |
