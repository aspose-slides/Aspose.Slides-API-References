---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides dla Androida, odniesienie API Java
description: Reprezentuje menedżera, który zarządza zachowaniem placeholderów stopki slajdu głównego, daty i godziny, numeru strony oraz wszystkich child placeholderów.
type: docs
url: /pl/com.aspose.slides/imasterslideheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Reprezentuje menedżera, który zarządza zachowaniem stopki slajdu głównego, placeholderów daty i godziny, numeru strony oraz wszystkich child placeholderów. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego.

## Metody

| Metoda | Opis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Zmienia widoczność placeholdera stopki slajdu głównego oraz wszystkich child placeholderów stopki. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Zmienia widoczność placeholdera numeru strony slajdu głównego oraz wszystkich child placeholderów numeru strony. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Zmienia widoczność placeholdera daty i godziny slajdu głównego oraz wszystkich child placeholderów daty i godziny. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Ustawia tekst w placeholderze stopki slajdu głównego oraz we wszystkich child placeholderach stopki. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Ustawia tekst w placeholderze daty i godziny slajdu głównego oraz we wszystkich child placeholderach daty i godziny. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Zmienia widoczność placeholdera stopki slajdu głównego oraz wszystkich child placeholderów stopki. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że placeholdery stopki są widoczne, w przeciwnym razie - ukrywa je. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Zmienia widoczność placeholdera numeru strony slajdu głównego oraz wszystkich child placeholderów numeru strony. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że placeholdery numeru strony są widoczne, w przeciwnym razie - ukrywa je. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Zmienia widoczność placeholdera daty i godziny slajdu głównego oraz wszystkich child placeholderów daty i godziny. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że placeholdery daty i godziny są widoczne, w przeciwnym razie - ukrywa je. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Ustawia tekst w placeholderze stopki slajdu głównego oraz we wszystkich child placeholderach stopki. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Ustawia tekst w placeholderze daty i godziny slajdu głównego oraz we wszystkich child placeholderach daty i godziny. Child placeholdery oznaczają placeholdery zawarte w zależnych slajdach układu i zależnych slajdach. Zależne slajdy układu i slajdy używają i zależą od slajdu głównego.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |