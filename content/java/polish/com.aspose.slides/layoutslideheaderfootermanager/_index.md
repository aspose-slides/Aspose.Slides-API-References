---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje menedżera, który kontroluje zachowanie stopki slajdu układu, znaków zastępczych daty-czasu, numeru strony oraz wszystkich podrzędnych znaków zastępczych.
type: docs
url: /pl/com.aspose.slides/layoutslideheaderfootermanager/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Reprezentuje menedżera, który zarządza zachowaniem stopki slajdu układu, znaku daty-czasu, numeru strony oraz wszystkich podrzędnych znaków zastępczych. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.
## Metody

| Metoda | Opis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Zmienia widoczność znaku zastępczego stopki slajdu układu i wszystkich podrzędnych znaków zastępczych stopki. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu głównego. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Zmienia widoczność znaku zastępczego numeru strony slajdu układu i wszystkich podrzędnych znaków zastępczych numeru strony. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Zmienia widoczność znaku zastępczego daty-czasu slajdu układu i wszystkich podrzędnych znaków zastępczych daty-czasu. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ustawia tekst w znaku zastępczym stopki slajdu układu i wszystkich podrzędnych znakach zastępczych stopki. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ustawia tekst w znaku zastępczym daty-czasu slajdu układu i wszystkich podrzędnych znakach zastępczych daty-czasu. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Zmienia widoczność znaku zastępczego stopki slajdu układu i wszystkich podrzędnych znaków zastępczych stopki. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu głównego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że znaki stopki są widoczne, w przeciwnym razie - ukrywa je. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Zmienia widoczność znaku zastępczego numeru strony slajdu układu i wszystkich podrzędnych znaków zastępczych numeru strony. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że znaki numeru strony są widoczne, w przeciwnym razie - ukrywa je. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Zmienia widoczność znaku zastępczego daty-czasu slajdu układu i wszystkich podrzędnych znaków zastępczych daty-czasu. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że znaki daty-czasu są widoczne, w przeciwnym razie - ukrywa je. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Ustawia tekst w znaku zastępczym stopki slajdu układu i wszystkich podrzędnych znakach zastępczych stopki. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Ustawia tekst w znaku zastępczym daty-czasu slajdu układu i wszystkich podrzędnych znakach zastępczych daty-czasu. Podrzędne znaki zastępcze oznaczają, że znaki są zawarte w zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |