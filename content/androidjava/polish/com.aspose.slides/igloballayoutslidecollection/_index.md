---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje kolekcję wszystkich slajdów układu w prezentacji.
type: docs
url: /pl/com.aspose.slides/igloballayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Represents a collection of all layout slides in presentation. Extends ILayoutSlideCollection interface with methods for adding/cloning layout slides in context of uniting of the individual collections of master's layout slides.
## Metody

| Metoda | Opis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Dodaje kopię określonego slajdu układu do prezentacji. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Dodaje kopię określonego slajdu układu do prezentacji. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Dodaje nowy slajd układu do prezentacji. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Dodaje kopię określonego slajdu układu do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |

--------------------

Podczas klonowania układu pomiędzy różnymi prezentacjami, master układu może być również sklonowany, aby zachować formatowanie źródła. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu klonów tego samego slajdu master. Ręczne klonowanie slajdów master nie będzie ani zapobiegane, ani rejestrowane. |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Dodaje kopię określonego slajdu układu do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd master dla nowego układu. |

--------------------

Now układ zostanie powiązany z określonym masterem w docelowej prezentacji. Jest to więc odpowiednik kopiuj/wklej z opcją „Użyj motywu docelowego” w programie PowerPoint. |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Dodaje nowy slajd układu do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd master dla nowego układu. |
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Inne typy układów nie są obecnie obsługiwane: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa dla nowego układu. Jeśli podana nazwa jest już używana, zostanie wyrzucony ArgumentException. Jeśli przekazany parametr jest null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład "Title Slide" lub "1_Title Slide", "2_.." itp.). |

--------------------

1) Dodany układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych zastępczych pól ani kształtów. 2) Odpowiednikiem tej metody jest metoda [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) dostępna poprzez własność ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.