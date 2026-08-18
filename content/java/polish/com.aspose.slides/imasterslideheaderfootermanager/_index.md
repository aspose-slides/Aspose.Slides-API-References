---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje menedżera, który zarządza zachowaniem placeholderów stopki slajdu głównego, daty i godziny, numeru strony oraz wszystkich podległych placeholderów.
type: docs
url: /pl/com.aspose.slides/imasterslideheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Reprezentuje menedżera, który zarządza zachowaniem placeholderów stopki slajdu głównego, daty i godziny, numeru strony oraz wszystkich podrzędnych placeholderów. Podrzędne placeholdery oznaczają, że placeholdery znajdują się na zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy korzystają z slajdu głównego i są od niego zależne.
## Metody

| Metoda | Opis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Zmienia widoczność placeholdera stopki slajdu głównego oraz wszystkich podrzędnych placeholderów stopki. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Zmienia widoczność placeholdera numeru strony slajdu głównego oraz wszystkich podrzędnych placeholderów numeru strony. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Zmienia widoczność placeholdera daty i godziny slajdu głównego oraz wszystkich podrzędnych placeholderów daty i godziny. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ustawia tekst w placeholderze stopki slajdu głównego oraz we wszystkich podrzędnych placeholderach stopki. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ustawia tekst w placeholderze daty i godziny slajdu głównego oraz we wszystkich podrzędnych placeholderach daty i godziny. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Zmienia widoczność placeholdera stopki slajdu głównego oraz wszystkich podrzędnych placeholderów stopki. Podrzędne placeholdery oznaczają, że placeholdery znajdują się na zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy korzystają z slajdu głównego i są od niego zależne.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true – powoduje, że placeholdery stopki są widoczne, w przeciwnym razie – je ukrywa. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Zmienia widoczność placeholdera numeru strony slajdu głównego oraz wszystkich podrzędnych placeholderów numeru strony. Podrzędne placeholdery oznaczają, że placeholdery znajdują się na zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy korzystają z slajdu głównego i są od niego zależne.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true – powoduje, że placeholdery numeru strony są widoczne, w przeciwnym razie – je ukrywa. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Zmienia widoczność placeholdera daty i godziny slajdu głównego oraz wszystkich podrzędnych placeholderów daty i godziny. Podrzędne placeholdery oznaczają, że placeholdery znajdują się na zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy korzystają z slajdu głównego i są od niego zależne.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true – powoduje, że placeholdery daty i godziny są widoczne, w przeciwnym razie – je ukrywa. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ustawia tekst w placeholderze stopki slajdu głównego oraz we wszystkich podrzędnych placeholderach stopki. Podrzędne placeholdery oznaczają, że placeholdery znajdują się na zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy korzystają z slajdu głównego i są od niego zależne.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ustawia tekst w placeholderze daty i godziny slajdu głównego oraz we wszystkich podrzędnych placeholderach daty i godziny. Podrzędne placeholdery oznaczają, że placeholdery znajdują się na zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy korzystają z slajdu głównego i są od niego zależne.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |