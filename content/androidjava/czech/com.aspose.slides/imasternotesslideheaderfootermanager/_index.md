---
title: IMasterNotesSlideHeaderFooterManager
second_title: Aspose.Slides pro Android pomocí Java API
description: Reprezentuje správce, který obsahuje chování zarážek zápatí, datum-čas, číslování stránek hlavního snímku poznámek a všech podřízených zarážek.
type: docs
url: /cs/com.aspose.slides/imasternotesslideheaderfootermanager/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseHandoutNotesSlideHeaderFooterManag](../../com.aspose.slides/ibasehandoutnotesslideheaderfootermanag)
```
public interface IMasterNotesSlideHeaderFooterManager extends IBaseHandoutNotesSlideHeaderFooterManag
```

Reprezentuje správce, který obsahuje chování zápatí, datum-čas a číslování stránek v hlavním snímku poznámek a všech podřízených zarážek. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.
## Metody

| Metoda | Popis |
| --- | --- |
| [setHeaderAndChildHeadersVisibility(boolean isVisible)](#setHeaderAndChildHeadersVisibility-boolean-) | Mění viditelnost zarážky záhlaví hlavního snímku poznámek a všech podřízených zarážek záhlaví. |
| [setHeaderAndChildHeadersText(String text)](#setHeaderAndChildHeadersText-java.lang.String-) | Nastavuje text do zarážky záhlaví hlavního snímku poznámek a všech podřízených zarážek záhlaví. |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mění viditelnost zarážky zápatí hlavního snímku poznámek a všech podřízených zarážek zápatí. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mění viditelnost zarážky číslování stránek hlavního snímku poznámek a všech podřízených zarážek číslování stránek. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mění viditelnost zarážky datum-čas hlavního snímku poznámek a všech podřízených zarážek datum-čas. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Nastavuje text do zarážky zápatí hlavního snímku poznámek a všech podřízených zarážek zápatí. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Nastavuje text do zarážky datum-čas hlavního snímku poznámek a všech podřízených zarážek datum-čas. |
### setHeaderAndChildHeadersVisibility(boolean isVisible) {#setHeaderAndChildHeadersVisibility-boolean-}
```
public abstract void setHeaderAndChildHeadersVisibility(boolean isVisible)
```


Mění viditelnost zarážky záhlaví hlavního snímku poznámek a všech podřízených zarážek záhlaví. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí záhlaví zarážky, jinak je skryje. |

### setHeaderAndChildHeadersText(String text) {#setHeaderAndChildHeadersText-java.lang.String-}
```
public abstract void setHeaderAndChildHeadersText(String text)
```


Nastavuje text do zarážky záhlaví hlavního snímku poznámek a všech podřízených zarážek záhlaví. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Mění viditelnost zarážky zápatí hlavního snímku poznámek a všech podřízených zarážek zápatí. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí zápatí zarážky, jinak ji skryje. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Mění viditelnost zarážky číslování stránek hlavního snímku poznámek a všech podřízených zarážek číslování stránek. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí číslování stránek, jinak jej skryje. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Mění viditelnost zarážky datum-čas hlavního snímku poznámek a všech podřízených zarážek datum-čas. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí datum-čas zarážky, jinak ji skryje. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Nastavuje text do zarážky zápatí hlavního snímku poznámek a všech podřízených zarážek zápatí. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Nastavuje text do zarážky datum-čas hlavního snímku poznámek a všech podřízených zarážek datum-čas. Podřízené zarážky znamenají, že zarážky jsou obsaženy v závislých snímcích poznámek. Závislé snímky poznámek používají a závisejí na hlavním snímku poznámek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |