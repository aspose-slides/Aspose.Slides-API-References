---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides dla Androida - odniesienie do API Java
description: Reprezentuje menedżera, który zarządza zachowaniem wszystkich pól zastępczych stopki, daty i godziny oraz numeru strony w prezentacji.
type: docs
url: /pl/com.aspose.slides/ipresentationheaderfootermanager/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Reprezentuje menedżera, który zarządza zachowaniem wszystkich pól zastępczych stopki, daty i godziny oraz numeru strony w prezentacji.

## Metody

| Metoda | Opis |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Zmienia widoczność wszystkich pól zastępczych nagłówka, w tym szablonu notatek, slajdów notatek i szablonu wersji papierowej. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Zmienia widoczność wszystkich pól zastępczych stopki, w tym slajdów głównych, slajdów układu i slajdów. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Zmienia widoczność wszystkich pól zastępczych numeru strony, w tym slajdów głównych, slajdów układu i slajdów. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Zmienia widoczność wszystkich pól zastępczych daty i godziny, w tym slajdów głównych, slajdów układu i slajdów. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Ustawia tekst we wszystkich polach zastępczych nagłówka, w tym szablonu notatek, slajdów notatek i szablonu wersji papierowej. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Ustawia tekst we wszystkich polach zastępczych stopki, w tym slajdów głównych, slajdów układu i slajdów. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Ustawia tekst we wszystkich polach zastępczych daty i godziny, w tym slajdów głównych, slajdów układu i slajdów. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Zmienia widoczność pól zastępczych stopki, daty i godziny oraz numeru strony dla wszystkich slajdów tytułowych i pierwszego slajdu układu. |

### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich pól zastępczych nagłówka, w tym szablonu notatek, slajdów notatek i szablonu wersji papierowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze nagłówka są widoczne, w przeciwnym razie - ukrywa je. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich pól zastępczych stopki, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze stopki są widoczne, w przeciwnym razie - ukrywa je. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich pól zastępczych numeru strony, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze numeru strony są widoczne, w przeciwnym razie - ukrywa je. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Zmienia widoczność wszystkich pól zastępczych daty i godziny, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze daty i godziny są widoczne, w przeciwnym razie - ukrywa je. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Ustawia tekst we wszystkich polach zastępczych nagłówka, w tym szablonu notatek, slajdów notatek i szablonu wersji papierowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Ustawia tekst we wszystkich polach zastępczych stopki, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Ustawia tekst we wszystkich polach zastępczych daty i godziny, w tym slajdów głównych, slajdów układu i slajdów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do ustawienia. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Zmienia widoczność pól zastępczych stopki, daty i godziny oraz numeru strony dla wszystkich slajdów tytułowych i pierwszego slajdu układu. Slajdy tytułowe - slajdy oparte na pierwszym slajdzie układu (bez względu na typ tego pierwszego układu).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| isVisible | boolean | true - powoduje, że pola zastępcze są widoczne, w przeciwnym razie - ukrywa je. |