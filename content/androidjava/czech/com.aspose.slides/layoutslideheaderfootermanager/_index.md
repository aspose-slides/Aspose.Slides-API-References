---
title: LayoutSlideHeaderFooterManager
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje správce, který obsahuje chování zástupců zápatí snímku rozvržení, datum-čas, číslování stránek a všech podřízených zástupců.
type: docs
url: /cs/com.aspose.slides/layoutslideheaderfootermanager/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.BaseHeaderFooterManager](../../com.aspose.slides/baseheaderfootermanager), [com.aspose.slides.BaseSlideHeaderFooterManager](../../com.aspose.slides/baseslideheaderfootermanager)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
```
public final class LayoutSlideHeaderFooterManager extends BaseSlideHeaderFooterManager implements ILayoutSlideHeaderFooterManager
```

Reprezentuje správce, který obsahuje chování zápatí snímku rozvržení, zástupců pro datum-čas, číslování stránek a všech podřízených zástupců. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.
## Metody

| Metoda | Popis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mění viditelnost zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mění viditelnost zástupce číslování stránek snímku rozvržení a všech podřízených zástupců číslování stránek. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mění viditelnost zástupce datum-čas snímku rozvržení a všech podřízených zástupců datum-čas. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Nastavuje text do zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Nastavuje text do zástupce datum-čas snímku rozvržení a všech podřízených zástupců datum-čas. |
### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public final void setFooterAndChildFootersVisibility(boolean isVisible)
```

Mění viditelnost zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí zástupce zápatí, jinak je skryje. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public final void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Mění viditelnost zástupce číslování stránek snímku rozvržení a všech podřízených zástupců číslování stránek. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí zástupce číslování stránek, jinak je skryje. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public final void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Mění viditelnost zástupce datum-čas snímku rozvržení a všech podřízených zástupců datum-čas. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true - zobrazí zástupce datum-čas, jinak je skryje. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public final void setFooterAndChildFootersText(String text)
```

Nastavuje text do zástupce zápatí snímku rozvržení a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public final void setDateTimeAndChildDateTimesText(String text)
```

Nastavuje text do zástupce datum-čas snímku rozvržení a všech podřízených zástupců datum-čas. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozvržení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |