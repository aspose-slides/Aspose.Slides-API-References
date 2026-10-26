---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje menedżera, który zarządza zachowaniem miejsc wstawianych dla stopki, daty i godziny, numeru strony oraz wszystkich podrzędnych miejsc w slajdzie układu.
type: docs
url: /pl/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Reprezentuje menedżera, który zarządza zachowaniem miejsca na stopkę slajdu układu, daty i godziny, numeru strony oraz wszystkich podrzędnych miejsc. Podrzędne miejsca oznaczają miejsca zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

## Metody

| Metoda | Opis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Zmienia widoczność miejsca na stopkę slajdu układu i wszystkich podrzędnych miejsc na stopkę. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Zmienia widoczność miejsca na numer strony slajdu układu i wszystkich podrzędnych miejsc na numer strony. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Zmienia widoczność miejsca na datę i godzinę slajdu układu oraz wszystkich podrzędnych miejsc na datę i godzinę. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ustawia tekst w miejscu na stopkę slajdu układu i we wszystkich podrzędnych miejscach na stopkę. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ustawia tekst w miejscu na datę i godzinę slajdu układu i we wszystkich podrzędnych miejscach na datę i godzinę. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Zmienia widoczność miejsca na stopkę slajdu układu i wszystkich podrzędnych miejsc na stopkę. Podrzędne miejsca oznaczają miejsca zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu podstawowego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true – sprawia, że miejsca na stopkę są widoczne, w przeciwnym razie je ukrywa. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Zmienia widoczność miejsca na numer strony slajdu układu i wszystkich podrzędnych miejsc na numer strony. Podrzędne miejsca oznaczają miejsca zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true – sprawia, że miejsca na numer strony są widoczne, w przeciwnym razie je ukrywa. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Zmienia widoczność miejsca na datę i godzinę slajdu układu oraz wszystkich podrzędnych miejsc na datę i godzinę. Podrzędne miejsca oznaczają miejsca zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true – sprawia, że miejsca na datę i godzinę są widoczne, w przeciwnym razie je ukrywa. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ustawia tekst w miejscu na stopkę slajdu układu i we wszystkich podrzędnych miejscach na stopkę. Podrzędne miejsca oznaczają miejsca zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ustawia tekst w miejscu na datę i godzinę slajdu układu oraz we wszystkich podrzędnych miejscach na datę i godzinę. Podrzędne miejsca oznaczają miejsca zawarte na zależnych slajdach. Zależne slajdy używają i zależą od slajdu układu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |