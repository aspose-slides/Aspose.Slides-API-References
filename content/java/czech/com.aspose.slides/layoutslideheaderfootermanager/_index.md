---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides pro Java - referenční dokumentace API
description: Representuje správce, který obsahuje chování zástupců zápatí, data-času, čísla stránky a všech podřízených zástupců rozložení snímku.
type: docs
url: /cs/com.aspose.slides/layoutslideheaderfootermanager/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Všechny implementované rozhraní:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Reprezentuje správce, který obsahuje chování zástupce zápatí snímku rozvržení, zástupce data-času, zástupce čísla stránky a všech podřízených zástupců. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.
## Metody

| Metoda | Popis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Změní viditelnost zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Změní viditelnost zástupce čísla stránky snímku rozvržení a všech podřízených zástupců čísla stránky. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Změní viditelnost zástupce data-času snímku rozvržení a všech podřízených zástupců data-času. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Nastaví text do zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Nastaví text do zástupce data-času snímku rozvržení a všech podřízených zástupců data-času. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```


Změní viditelnost zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupce zápatí, jinak je skryje. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```


Změní viditelnost zástupce čísla stránky snímku rozvržení a všech podřízených zástupců čísla stránky. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupce čísla stránky, jinak je skryje. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```


Změní viditelnost zástupce data-času snímku rozvržení a všech podřízených zástupců data-času. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí zástupce data-času, jinak je skryje. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```


Nastaví text do zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```


Nastaví text do zástupce data-času snímku rozvržení a všech podřízených zástupců data-času. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |