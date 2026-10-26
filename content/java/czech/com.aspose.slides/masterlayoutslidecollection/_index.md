---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides pro Java API Reference
description: Představuje kolekci všech rozložení snímků definovaného hlavního snímku.
type: docs
url: /cs/com.aspose.slides/masterlayoutslidecollection/
---
**Inheritance:**  
Dědičnost:
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**All Implemented Interfaces:**  
Všechna implementovaná rozhraní:
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Represents a collections of all layout slides of defined master slide. Extends LayoutSlideCollection **class** with methods for adding/inserting/removing/cloning/reordering layout slides in context of the individual collections of master's layout slides.

## Metody

| Method | Description |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Přidá kopii určeného rozložení snímku na konec kolekce. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Vloží kopii určeného rozložení snímku na zadanou pozici v kolekci. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Přidá nové rozložení snímku na konec kolekce. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Vloží nové rozložení snímku na zadanou pozici v kolekci. |
| [removeAt(int index)](#removeAt-int-) | Odstraní prvek na zadaném indexu v kolekci. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Přesune rozložení snímku z kolekce na zadanou pozici. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Přidá kopii určeného rozložení snímku na konec kolekce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

1) Nové rozložení bude propojeno s nadřazeným hlavním snímkem této kolekce rozložení snímků. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) přístupná pomocí vlastnosti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) property.

**Návratová hodnota:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Vloží kopii určeného rozložení snímku na zadanou pozici v kolekci.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index nového snímku. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek ke klonování. |

--------------------

Nové rozložení bude propojeno s nadřazeným hlavním snímkem této kolekce rozložení snímků. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu.

**Návratová hodnota:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Vložený snímek.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Přidá nové rozložení snímku na konec kolekce.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozložení nejsou momentálně podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název pro nové rozložení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název automaticky vygenerován podle předaného typu rozložení (například „Title Slide“ nebo „1_Title Slide“, „2_…“, atd.). |

--------------------

1) Přidané rozložení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádná zástupná místa a žádné tvary. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) přístupná pomocí vlastnosti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) property.

**Návratová hodnota:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Přidaný snímek.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Vloží nové rozložení snímku na zadanou pozici v kolekci.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index nového snímku. |
| layoutType | byte | Typ rozložení pro nové rozložení. Podporované typy rozložení: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Ostatní typy rozložení nejsou momentálně podporovány: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Název pro nové rozložení. Pokud je předaný název již používán, bude vyvolána výjimka ArgumentException. Pokud je předán parametr null, bude název automaticky vygenerován podle předaného typu rozložení (například „Title Slide“ nebo „1_Title Slide“, „2_…“, atd.). |

--------------------

Vložené rozložení pro hodnotu SlideLayoutType.Custom typu layoutType neobsahuje žádná zástupná místa a žádné tvary.

**Návratová hodnota:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Vložený snímek.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Odstraní prvek na zadaném indexu v kolekci.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index (číselně od nuly) prvku k odstranění. |

--------------------

1) Aby se předešlo vyvolání výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozložení. 2) Můžete také použít metodu [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) pro zjednodušení kódu.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Přesune rozložení snímku z kolekce na zadanou pozici.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Cílový index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Snímek k přesunu. |