---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides dla Java – odniesienie do API
description: Reprezentuje menedżera, który zarządza zachowaniem pól zastępczych stopki slajdu układu, daty i czasu, numeru strony oraz wszystkich pól zastępczych potomnych.
type: docs
url: /pl/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Reprezentuje menedżera, który zarządza zachowaniem pól zastępczych stopki slajdu układu, daty i czasu oraz numeru strony oraz wszystkich pól zastępczych potomnych. Pola zastępcze potomne oznaczają, że pola zastępcze są zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.
## Metody

| Metoda | Opis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Zmienia widoczność pola zastępczego stopki slajdu układu i wszystkich pól zastępczych stopki potomnych. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Zmienia widoczność pola zastępczego numeru strony slajdu układu i wszystkich pól zastępczych numeru strony potomnych. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Zmienia widoczność pola zastępczego daty i czasu slajdu układu i wszystkich pól zastępczych daty i czasu potomnych. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ustawia tekst w polu zastępczym stopki slajdu układu i we wszystkich polach zastępczych stopki potomnych. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ustawia tekst w polu zastępczym daty i czasu slajdu układu i we wszystkich polach zastępczych daty i czasu potomnych. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Zmienia widoczność pola zastępczego stopki slajdu układu i wszystkich pól zastępczych stopki potomnych. Pola zastępcze potomne oznaczają, że pola zastępcze są zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu głównego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze stopki są widoczne, w przeciwnym razie - ukrywa je. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Zmienia widoczność pola zastępczego numeru strony slajdu układu i wszystkich pól zastępczych numeru strony potomnych. Pola zastępcze potomne oznaczają, że pola zastępcze są zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze numeru strony są widoczne, w przeciwnym razie - ukrywa je. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Zmienia widoczność pola zastępczego daty i czasu slajdu układu i wszystkich pól zastępczych daty i czasu potomnych. Pola zastępcze potomne oznaczają, że pola zastępcze są zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze daty i czasu są widoczne, w przeciwnym razie - ukrywa je. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ustawia tekst w polu zastępczym stopki slajdu układu i we wszystkich polach zastępczych stopki potomnych. Pola zastępcze potomne oznaczają, że pola zastępcze są zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ustawia tekst w polu zastępczym daty i czasu slajdu układu i we wszystkich polach zastępczych daty i czasu potomnych. Pola zastępcze potomne oznaczają, że pola zastępcze są zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |