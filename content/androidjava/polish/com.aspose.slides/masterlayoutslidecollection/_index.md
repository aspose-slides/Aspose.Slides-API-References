---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides dla Androida poprzez referencję API Java
description: Reprezentuje zbiór wszystkich slajdów układu zdefiniowanego slajdu wzorca.
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

Reprezentuje zbiór wszystkich slajdów układu zdefiniowanego slajdu wzorca. Rozszerza klasę LayoutSlideCollection metodami dodawania/wstawiania/usuwania/klonowania/przemieszczania slajdów układu w kontekście poszczególnych kolekcji slajdów układu wzorca.
## Metody

| Metoda | Opis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Dodaje kopię określonego slajdu układu na koniec kolekcji. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Wstawia kopię określonego slajdu układu w określone miejsce kolekcji. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Dodaje nowy slajd układu na koniec kolekcji. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Wstawia nowy slajd układu w określone miejsce kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o określonym indeksie w kolekcji. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Przemieszcza slajd układu z kolekcji do określonego miejsca. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Dodaje kopię określonego slajdu układu na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania.

--------------------

1) Nowy układ będzie połączony z nadrzędnym slajdem wzorca w tej kolekcji slajdów układu. Jest to więc analogiczny proces do kopiuj/wklej z opcją „Use Destination Theme” w PowerPoint. 2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) dostępna przez właściwość ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Wstawia kopię określonego slajdu układu w określone miejsce kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania.

--------------------

Nowy układ będzie połączony z nadrzędnym slajdem wzorca w tej kolekcji slajdów układu. Jest to więc analogiczny proces do kopiuj/wklej z opcją „Use Destination Theme” w PowerPoint. |

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
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException. Jeśli parametr jest null, nazwa zostanie wygenerowana automatycznie na podstawie podanego typu układu (np. "Title Slide" lub "1_Title Slide", "2_..", itp.). |

--------------------

1) Dodany układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych miejsc wstawiania ani kształtów. 2) Odpowiednikiem tej metody jest metoda [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) dostępna przez właściwość ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Wstawia nowy slajd układu w określone miejsce kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks nowego slajdu. |
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException. Jeśli parametr jest null, nazwa zostanie wygenerowana automatycznie na podstawie podanego typu układu (np. "Title Slide" lub "1_Title Slide", "2_..", itp.). |

--------------------

Wstawiony układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych miejsc wstawiania ani kształtów. |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Wstawiony slajd.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa element o określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia.

--------------------

1) Aby uniknąć wyrzucenia PptxEditException, sprawdź wcześniej właściwość HasDependingSlides układu. 2) Można także użyć metody [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) aby uprościć kod. |
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```


Przemieszcza slajd układu z kolekcji do określonego miejsca.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Docelowy indeks. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do przeniesienia. |