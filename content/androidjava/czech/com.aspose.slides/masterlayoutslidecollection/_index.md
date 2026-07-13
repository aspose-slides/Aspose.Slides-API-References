---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides pro Android prostřednictvím referenčního Java API
description: Představuje kolekci všech rozložení snímků definovaného hlavního snímku.
type: docs
url: /cs/com.aspose.slides/masterlayoutslidecollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Představuje kolekci všech rozložení snímků definovaného hlavního snímku. Rozšiřuje třídu LayoutSlideCollection metodami pro přidávání/vkládání/odstraňování/klonování/přeskupování rozložení snímků v kontextu jednotlivých kolekcí rozložení hlavního snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii určeného rozložení snímku na konec kolekce. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Vloží kopii určeného rozložení snímku na určenou pozici v kolekci. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Přidá nové rozložení snímku na konec kolekce. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Vloží nové rozložení snímku na určenou pozici v kolekci. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na určeném indexu v kolekci. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Přesune rozložení snímku z kolekce na určenou pozici. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Přidá kopii určeného rozložení snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

1) Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci rozložení snímků. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) přístupná přes vlastnost ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). 

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Vloží kopii určeného rozložení snímku na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci rozložení snímků. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. 

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Vložený snímek.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Přidá nové rozložení snímku na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozložení nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název nového rozložení. Pokud je předaný název již použit, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název generován automaticky na základě předaného typu rozložení (například „Title Slide“ nebo „1\_Title Slide“, „2\_..“ atd.). |

--------------------

1) Přidané rozložení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné symboly ani tvary. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) přístupná přes vlastnost ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). 

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Vloží nové rozložení snímku na určenou pozici v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Index nového snímku. |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozložení nejsou v současnosti podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název nového rozložení. Pokud je předaný název již použit, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název generován automaticky na základě předaného typu rozložení (například „Title Slide“ nebo „1\_Title Slide“, „2\_..“ atd.). |

--------------------

Vložené rozložení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádné zástupné symboly ani tvary. 

**Návratová hodnota:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Vložený snímek.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na určeném indexu v kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Nulový index prvku, který má být odstraněn. |

--------------------

1) Aby se předešlo vyvolání výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozložení. 2) Můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pro zjednodušení kódu. 

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Přesune rozložení snímku z kolekce na určenou pozici.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| index | int | Cílový index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek k přesunutí. |