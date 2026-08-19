---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides pro Java – reference API
description: Představuje kolekci všech rozvržených snímků definovaného hlavního snímku.
type: docs
url: /cs/com.aspose.slides/imasterlayoutslidecollection/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Představuje kolekci všech rozvržených snímků definovaného hlavního snímku. Rozšiřuje rozhraní ILayoutSlideCollection metodami pro přidávání/vkládání/odstraňování/klonování rozvržených snímků v kontextu jednotlivých kolekcí rozvržených snímků hlavního snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii určeného rozvrženého snímku na konec kolekce. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Vloží kopii určeného rozvrženého snímku na zadanou pozici v kolekci. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Přidá nový rozvržený snímek na konec kolekce. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Vloží nový rozvržený snímek na zadanou pozici v kolekci. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Přesune rozvržený snímek z kolekce na zadanou pozici. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Přidá kopii určeného rozvrženého snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

1) Nový rozvržený snímek bude propojen s nadřazeným hlavním snímkem pro tuto kolekci rozvržených snímků. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) přístupná přes vlastnost [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Vloží kopii určeného rozvrženého snímku na zadanou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

Nový rozvržený snímek bude propojen s nadřazeným hlavním snímkem pro tuto kolekci rozvržených snímků. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu.

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Vložený snímek.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Přidá nový rozvržený snímek na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| layoutType | byte | Typ rozvržení pro nový rozvržený snímek. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozvržení nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název nového rozvržení. Pokud je zadaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je parametr null, bude název vygenerován automaticky podle zadaného typu rozvržení (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

--------------------

1) Přidané rozvržení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné znaky ani tvary. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) přístupná přes vlastnost [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Vloží nový rozvržený snímek na zadanou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| layoutType | byte | Typ rozvržení pro nový rozvržený snímek. Podporované typy rozvržení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozvržení nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název nového rozvržení. Pokud je zadaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je parametr null, bude název vygenerován automaticky podle zadaného typu rozvržení (například "Title Slide" nebo "1_Title Slide", "2_..", atd.). |

--------------------

Vložené rozvržení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné znaky ani tvary.

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Vložený snímek.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |

--------------------

1) Aby se předešlo vyvolání výjimky PptxEditException, předem zkontrolujte vlastnost HasDependingSlides rozvržení. 2) Můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pro zjednodušení kódu.
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Přesune rozvržený snímek z kolekce na zadanou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek k přesunutí. |