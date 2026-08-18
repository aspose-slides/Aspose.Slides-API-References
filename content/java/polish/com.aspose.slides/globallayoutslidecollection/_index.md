---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides dla Java – odniesienie do API
description: Reprezentuje kolekcję wszystkich slajdów układu w prezentacji.
type: docs
url: /pl/com.aspose.slides/globallayoutslidecollection/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Reprezentuje kolekcję wszystkich slajdów układu w prezentacji. Rozszerza klasę LayoutSlideCollection metodami dodawania/klonowania slajdów układu w kontekście łączenia poszczególnych kolekcji slajdów układu mastera.

## Metody

| Metoda | Opis |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Dodaje kopię określonego slajdu układu do prezentacji. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Dodaje kopię określonego slajdu układu do prezentacji. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Dodaje nowy slajd układu do prezentacji. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Dodaje kopię określonego slajdu układu do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |

--------------------

Podczas klonowania układu pomiędzy różnymi prezentacjami, master układu może zostać również sklonowany, aby zachować formatowanie źródła. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu klonów tego samego slajdu master. Ręczne klonowanie slajdów master nie będzie ani zapobiegane, ani rejestrowane. |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Dodaje kopię określonego slajdu układu do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slajd do sklonowania. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd master dla nowego układu. |

--------------------

1) Nowy układ zostanie powiązany z określonym masterem w docelowej prezentacji. Jest to odpowiednik operacji kopiuj/wklej z opcją „Use Destination Theme” w programie PowerPoint. 2) Odpowiednikiem tej metody jest metoda [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) dostępna przez właściwość ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Dodaje nowy slajd układu do prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Slajd master dla nowego układu. |
| layoutType | byte | Typ układu dla nowego układu. Obsługiwane typy układów: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nazwa nowego układu. Jeśli podana nazwa jest już używana, zostanie zgłoszony ArgumentException. Jeśli przekazany zostanie parametr null, nazwa zostanie wygenerowana automatycznie w zależności od podanego typu układu (na przykład "Title Slide" lub "1_Title Slide", "2_.." itp.). |

--------------------

1) Dodany układ dla wartości SlideLayoutType.Custom typu layoutType nie zawiera żadnych pól zastępczych ani kształtów. 2) Odpowiednikiem tej metody jest metoda [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) dostępna przez właściwość ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)). |

**Zwraca:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Dodany slajd.