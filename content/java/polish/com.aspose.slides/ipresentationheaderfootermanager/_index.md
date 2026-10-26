---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides dla Java – dokumentacja API
description: Reprezentuje menedżera, który zarządza zachowaniem wszystkich elementów zastępczych stopki, daty i godziny oraz numeru strony w prezentacji.
type: docs
url: /pl/com.aspose.slides/ipresentationheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Reprezentuje menedżer, który zarządza zachowaniem wszystkich elementów zastępczych stopki, daty i godziny oraz numeru strony w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Zmienia widoczność wszystkich elementów zastępczych nagłówka, w tym szablonu notatek, slajdów notatek i szablonu materiałów. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Zmienia widoczność wszystkich elementów zastępczych stopki, w tym slajdów głównych, slajdów układu i slajdów. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Zmienia widoczność wszystkich elementów zastępczych numeru strony, w tym slajdów głównych, slajdów układu i slajdów. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Zmienia widoczność wszystkich elementów zastępczych daty i godziny, w tym slajdów głównych, slajdów układu i slajdów. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Ustawia tekst we wszystkich elementach zastępczych nagłówka, w tym szablonie notatek, slajdach notatek i szablonie materiałów. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Ustawia tekst we wszystkich elementach zastępczych stopki, w tym slajdach głównych, slajdach układu i slajdach. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Ustawia tekst we wszystkich elementach zastępczych daty i godziny, w tym slajdach głównych, slajdach układu i slajdach. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Zmienia widoczność elementów zastępczych stopki, daty i godziny oraz numeru strony dla wszystkich slajdów tytułowych i pierwszego slajdu układu. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich elementów zastępczych nagłówka, w tym szablonu notatek, slajdów notatek i szablonu materiałów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że elementy zastępcze nagłówka są widoczne, w przeciwnym razie - są ukryte. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich elementów zastępczych stopki, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że elementy zastępcze stopki są widoczne, w przeciwnym razie - są ukryte. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich elementów zastępczych numeru strony, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że elementy zastępcze numeru strony są widoczne, w przeciwnym razie - są ukryte. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich elementów zastępczych daty i godziny, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że elementy zastępcze daty i godziny są widoczne, w przeciwnym razie - są ukryte. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Ustawia tekst we wszystkich elementach zastępczych nagłówka, w tym szablonie notatek, slajdach notatek i szablonie materiałów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Ustawia tekst we wszystkich elementach zastępczych stopki, w tym slajdach głównych, slajdach układu i slajdach.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Ustawia tekst we wszystkich elementach zastępczych daty i godziny, w tym slajdach głównych, slajdach układu i slajdach.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Zmienia widoczność elementów zastępczych stopki, daty i godziny oraz numeru strony dla wszystkich slajdów tytułowych i pierwszego slajdu układu. Slajdy tytułowe – slajdy oparte na pierwszym slajdzie układu (niezależnie od typu tego pierwszego układu).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że elementy zastępcze są widoczne, w przeciwnym razie - są ukryte. |