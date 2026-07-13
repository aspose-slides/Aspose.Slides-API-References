---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides pro Android přes Java API Reference
description: Reprezentuje správce, který obsahuje chování zástupců zápatí hlavního snímku, data a času, číslování stránek a všech podřízených zástupců.
type: docs
url: /cs/com.aspose.slides/imasterslideheaderfootermanager/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Representuje manažera, který obsahuje chování zápatí hlavního snímku, zástupců data-času, číslování stránek a všech podřízených zástupců. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku.
## Metody

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mění viditelnost zástupce zápatí hlavního snímku a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mění viditelnost zástupce číslování stránek hlavního snímku a všech podřízených zástupců číslování stránek. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mění viditelnost zástupce data a času hlavního snímku a všech podřízených zástupců data a času. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Nastavuje text do zástupce zápatí hlavního snímku a všech podřízených zástupců zápatí. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Nastavuje text do zástupce data a času hlavního snímku a všech podřízených zástupců data a času. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```


Mění viditelnost zástupce zápatí hlavního snímku a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zápatí je viditelné, jinak je skryté. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Mění viditelnost zástupce číslování stránek hlavního snímku a všech podřízených zástupců číslování stránek. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - číslo stránky je viditelné, jinak je skryté. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Mění viditelnost zástupce data a času hlavního snímku a všech podřízených zástupců data a času. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - data a čas jsou viditelné, jinak jsou skryté. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```


Nastavuje text do zástupce zápatí hlavního snímku a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```


Nastavuje text do zástupce data a času hlavního snímku a všech podřízených zástupců data a času. Podřízené zástupce znamenají, že jsou obsaženy na závislých snímcích rozvržení a závislých snímcích. Závislé snímky rozvržení a snímky používají a závisejí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |