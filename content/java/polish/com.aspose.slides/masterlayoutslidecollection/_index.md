---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje kolekcję wszystkich slajdów układu zdefiniowanego slajdu master.
type: docs
url: /pl/com.aspose.slides/masterlayoutslidecollection/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Reprezentuje kolekcję wszystkich slajdów układu zdefiniowanego slajdu master. Rozszerza klasę LayoutSlideCollection metodami do dodawania/wstawiania/usuwania/klonowania/przemieszczania slajdów układu w kontekście poszczególnych kolekcji slajdów układu mastera.
## Metody

| Metoda | Opis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Dodaje kopię określonego slajdu układu na koniec kolekcji. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Wstawia kopię określonego slajdu układu na określone miejsce w kolekcji. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Dodaje nowy slajd układu na koniec kolekcji. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Wstawia nowy slajd układu na określone miejsce w kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie w kolekcji. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Przemieszcza slajd układu z kolekcji na określone miejsce. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Dodaje kopię określonego slajdu układu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |

--------------------

1) Nowy układ będzie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu. Jest to odpowiednik operacji kopiuj/wklej z opcją „Use Destination Theme” w programie PowerPoint.
2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) dostępna przez właściwość ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Wstawia kopię określonego slajdu układu na określone miejsce w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |

--------------------

Nowy układ będzie powiązany z nadrzędnym slajdem master dla tej kolekcji slajdów układu. Jest to odpowiednik operacji kopiuj/wklej z opcją „Use Destination Theme” w programie PowerPoint. |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Wstawiony slajd.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```


Dodaje nowy slajd układu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException. Jeśli przekazany jest parametr null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład "Title Slide" lub "1\_Title Slide", "2\_..", itd.). |

--------------------

1) Dodany układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych pól zastępczych ani kształtów.
2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) dostępna przez właściwość ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Wstawia nowy slajd układu na określone miejsce w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException. Jeśli przekazany jest parametr null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład "Title Slide" lub "1\_Title Slide", "2\_..", itd.). |

--------------------

Wstawiony układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych pól zastępczych ani kształtów. |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Wstawiony slajd.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa element o podanym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze elementu do usunięcia. |

--------------------

1) Aby uniknąć rzucenia PptxEditException, przedtem sprawdź właściwość HasDependingSlides układu.
2) Możesz także użyć metody [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) aby uprościć kod. |
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```


Przemieszcza slajd układu z kolekcji na określone miejsce.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks docelowy. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do przeniesienia. |