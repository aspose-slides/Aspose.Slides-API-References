---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides dla Java – odniesienie do API
description: Reprezentuje kolekcję wszystkich slajdów układu zdefiniowanego slajdu-matki.
type: docs
url: /pl/com.aspose.slides/imasterlayoutslidecollection/
---
**Wszystkie implementowane interfejsy:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Reprezentuje kolekcję wszystkich slajdów układu zdefiniowanego slajdu-matki. Rozszerza interfejs ILayoutSlideCollection o metody służące do dodawania/wstawiania/usuwania/klonowania slajdów układu w kontekście poszczególnych kolekcji slajdów układu matki.

## Metody

| Metoda | Opis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Dodaje kopię określonego slajdu układu na koniec kolekcji. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Wstawia kopię określonego slajdu układu na określoną pozycję w kolekcji. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Dodaje nowy slajd układu na koniec kolekcji. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Wstawia nowy slajd układu na określoną pozycję w kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o określonym indeksie w kolekcji. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Przenosi slajd układu z kolekcji na określoną pozycję. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Dodaje kopię określonego slajdu układu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |

--------------------

1) Nowy układ zostanie powiązany z nadrzędnym slajdem-matką tej kolekcji slajdów układu. Jest to więc odpowiednik operacji kopiuj/wklej z opcją „Use Destination Theme” w programie PowerPoint. 2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) dostępna przez właściwość [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Wstawia kopię określonego slajdu układu na określoną pozycję w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |

--------------------

Nowy układ zostanie powiązany z nadrzędnym slajdem-matką tej kolekcji slajdów układu. Jest to więc odpowiednik operacji kopiuj/wklej z opcją „Use Destination Theme” w programie PowerPoint.

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Wstawiony slajd.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Dodaje nowy slajd układu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie rzucony wyjątek ArgumentException. Jeśli przekazany parametr jest null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (np. „Title Slide” lub „1_Title Slide”, „2_..” itp.). |

--------------------

1) Dodany układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych pól zastępczych ani kształtów. 2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) dostępna przez właściwość [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Wstawia nowy slajd układu na określoną pozycję w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie rzucony wyjątek ArgumentException. Jeśli przekazany parametr jest null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (np. „Title Slide” lub „1_Title Slide”, „2_..” itp.). |

--------------------

Wstawiony układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych pól zastępczych ani kształtów.

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Wstawiony slajd.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element o określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Zero-indeksowy indeks elementu do usunięcia. |

--------------------

1) Aby uniknąć zgłoszenia PptxEditException, sprawdź wcześniej właściwość HasDependingSlides układu. 2) Można również użyć metody [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove), aby uprościć kod.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Przenosi slajd układu z kolekcji na określoną pozycję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do przeniesienia. |