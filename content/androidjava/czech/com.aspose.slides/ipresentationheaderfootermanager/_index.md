---
title: IPresentationHeaderFooterManager
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje správce, který obsahuje chování všech zástupných symbolů zápatí, data-času a číslování stránek v prezentaci.
type: docs
url: /cs/com.aspose.slides/ipresentationheaderfootermanager/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseHeaderFooterManager](../../com.aspose.slides/ibaseheaderfootermanager)
```
public interface IPresentationHeaderFooterManager extends IBaseHeaderFooterManager
```

Reprezentuje správce, který obsahuje chování všech zástupných symbolů zápatí, data-času a číslování stránek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [setAllHeadersVisibility(boolean isVisible)](#setAllHeadersVisibility-boolean-) | Mění viditelnost všech zástupných symbolů záhlaví, včetně masteru poznámek, snímků s poznámkami a masteru podkladů. |
| [setAllFootersVisibility(boolean isVisible)](#setAllFootersVisibility-boolean-) | Mění viditelnost všech zástupných symbolů zápatí, včetně hlavních snímků, rozložení snímků a samotných snímků. |
| [setAllSlideNumbersVisibility(boolean isVisible)](#setAllSlideNumbersVisibility-boolean-) | Mění viditelnost všech zástupných symbolů číslování stránek, včetně hlavních snímků, rozložení snímků a samotných snímků. |
| [setAllDateTimesVisibility(boolean isVisible)](#setAllDateTimesVisibility-boolean-) | Mění viditelnost všech zástupných symbolů data-času, včetně hlavních snímků, rozložení snímků a samotných snímků. |
| [setAllHeadersText(String text)](#setAllHeadersText-java.lang.String-) | Nastavuje text do všech zástupných symbolů záhlaví, včetně masteru poznámek, snímků s poznámkami a masteru podkladů. |
| [setAllFootersText(String text)](#setAllFootersText-java.lang.String-) | Nastavuje text do všech zástupných symbolů zápatí, včetně hlavních snímků, rozložení snímků a samotných snímků. |
| [setAllDateTimesText(String text)](#setAllDateTimesText-java.lang.String-) | Nastavuje text do všech zástupných symbolů data-času, včetně hlavních snímků, rozložení snímků a samotných snímků. |
| [setVisibilityOnAllTitleSlides(boolean isVisible)](#setVisibilityOnAllTitleSlides-boolean-) | Mění viditelnost zástupných symbolů zápatí, data-času a číslování stránek pro všechny titulní snímky a pro první rozložení snímku. Titulní snímky \\u2013 snímky založené na prvním rozložení snímku (bez ohledu na typ tohoto prvního rozložení). |
### setAllHeadersVisibility(boolean isVisible) {#setAllHeadersVisibility-boolean-}
```
public abstract void setAllHeadersVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných symbolů záhlaví, včetně masteru poznámek, snímků s poznámkami a masteru podkladů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupné symboly záhlaví, jinak je skryje. |

### setAllFootersVisibility(boolean isVisible) {#setAllFootersVisibility-boolean-}
```
public abstract void setAllFootersVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných symbolů zápatí, včetně hlavních snímků, rozložení snímků a samotných snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupné symboly zápatí, jinak je skryje. |

### setAllSlideNumbersVisibility(boolean isVisible) {#setAllSlideNumbersVisibility-boolean-}
```
public abstract void setAllSlideNumbersVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných symbolů číslování stránek, včetně hlavních snímků, rozložení snímků a samotných snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupné symboly číslování stránek, jinak je skryje. |

### setAllDateTimesVisibility(boolean isVisible) {#setAllDateTimesVisibility-boolean-}
```
public abstract void setAllDateTimesVisibility(boolean isVisible)
```

Mění viditelnost všech zástupných symbolů data-času, včetně hlavních snímků, rozložení snímků a samotných snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupné symboly data-času, jinak je skryje. |

### setAllHeadersText(String text) {#setAllHeadersText-java.lang.String-}
```
public abstract void setAllHeadersText(String text)
```

Nastavuje text do všech zástupných symbolů záhlaví, včetně masteru poznámek, snímků s poznámkami a masteru podkladů.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setAllFootersText(String text) {#setAllFootersText-java.lang.String-}
```
public abstract void setAllFootersText(String text)
```

Nastavuje text do všech zástupných symbolů zápatí, včetně hlavních snímků, rozložení snímků a samotných snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setAllDateTimesText(String text) {#setAllDateTimesText-java.lang.String-}
```
public abstract void setAllDateTimesText(String text)
```

Nastavuje text do všech zástupných symbolů data-času, včetně hlavních snímků, rozložení snímků a samotných snímků.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setVisibilityOnAllTitleSlides(boolean isVisible) {#setVisibilityOnAllTitleSlides-boolean-}
```
public abstract void setVisibilityOnAllTitleSlides(boolean isVisible)
```

Mění viditelnost zástupných symbolů zápatí, data-času a číslování stránek pro všechny titulní snímky a pro první rozložení snímku. Titulní snímky \\u2013 snímky založené na prvním rozložení snímku (bez ohledu na typ tohoto prvního rozložení).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupné symboly, jinak je skryje. |