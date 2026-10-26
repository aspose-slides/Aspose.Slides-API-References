---
title: IPresentationHeaderFooterManager
second_title: Reference API Aspose.Slides pro Java
description: Představuje manažera, který spravuje chování všech zástupných znaků zápatí, data a času a číslování stránek v prezentaci.
type: docs
url: /cs/com.aspose.slides/ipresentationheaderfootermanager/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Představuje manažer, který spravuje chování všech zástupných znaků zápatí, data a času a číslování stránek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Changes all header placeholders visibility, including notes master, notes slides and handout master. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Changes all footer placeholders visibility, including master slides, layout slides and slides. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Changes all page number placeholders visibility, including master slides, layout slides and slides. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Changes all date-time placeholders visibility, including master slides, layout slides and slides. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Sets text to all header placeholders, including notes master, notes slides and handout master. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Sets text to all footer placeholders, including master slides, layout slides and slides. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Sets text to all date-time placeholders, including master slides, layout slides and slides. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Changes the footer, date-time and page number placeholders visibility for all title slides and for first layout slide. |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných znaků záhlaví, včetně masteru poznámek, snímků s poznámkami a masteru podkladových materiálů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zviditelní zástupné znaky záhlaví, jinak je skryje. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných znaků zápatí, včetně master snímků, šablonových snímků a snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zviditelní zástupné znaky zápatí, jinak je skryje. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných znaků číslování stránek, včetně master snímků, šablonových snímků a snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zviditelní zástupné znaky číslování stránek, jinak je skryje. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných znaků data a času, včetně master snímků, šablonových snímků a snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zviditelní zástupné znaky data a času, jinak je skryje. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Nastavuje text pro všechny zástupné znaky záhlaví, včetně masteru poznámek, snímků s poznámkami a masteru podkladových materiálů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Nastavuje text pro všechny zástupné znaky zápatí, včetně master snímků, šablonových snímků a snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Nastavuje text pro všechny zástupné znaky data a času, včetně master snímků, šablonových snímků a snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Mění viditelnost zástupných znaků zápatí, data a času a číslování stránek pro všechny titulní snímky a pro první šablonu. Titulní snímky – snímky založené na první šabloně (bez ohledu na typ této první šablony).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zviditelní zástupné znaky, jinak je skryje. |