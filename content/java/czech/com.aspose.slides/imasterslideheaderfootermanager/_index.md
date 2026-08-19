---
title: IMasterSlideHeaderFooterManager
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Představuje správce, který obsahuje chování zástupců patky hlavního snímku, data a času, číslování stránek a všech podřízených zástupců.
type: docs
url: /cs/com.aspose.slides/imasterslideheaderfootermanager/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface IMasterSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Reprezentuje správce, který obsahuje chování zástupců patky hlavního snímku, data a času, číslování stránek a všech podřízených zástupců. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích rozvržení a na závislých snímcích. Závislé snímky rozvržení a snímky používají a závisí na hlavním snímku.
## Metody

| Metoda | Popis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mění viditelnost zástupce patky hlavního snímku a všech podřízených zástupců patky. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mění viditelnost zástupce číslování stránek hlavního snímku a všech podřízených zástupců číslování stránek. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mění viditelnost zástupce data a času hlavního snímku a všech podřízených zástupců data a času. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Nastavuje text do zástupce patky hlavního snímku a všech podřízených zástupců patky. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Nastavuje text do zástupce data a času hlavního snímku a všech podřízených zástupců data a času. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Mění viditelnost zástupce patky hlavního snímku a všech podřízených zástupců patky. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích rozvržení a na závislých snímcích. Závislé snímky rozvržení a snímky používají a závisí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí zástupce patky, jinak je skryje. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Mění viditelnost zástupce číslování stránek hlavního snímku a všech podřízených zástupců číslování stránek. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích rozvržení a na závislých snímcích. Závislé snímky rozvržení a snímky používají a závisí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí zástupce číslování stránek, jinak je skryje. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Mění viditelnost zástupce data a času hlavního snímku a všech podřízených zástupců data a času. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích rozvržení a na závislých snímcích. Závislé snímky rozvržení a snímky používají a závisí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí zástupce data a času, jinak je skryje. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Nastavuje text do zástupce patky hlavního snímku a všech podřízených zástupců patky. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích rozvržení a na závislých snímcích. Závislé snímky rozvržení a snímky používají a závisí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Nastavuje text do zástupce data a času hlavního snímku a všech podřízených zástupců data a času. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích rozvržení a na závislých snímcích. Závislé snímky rozvržení a snímky používají a závisí na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |