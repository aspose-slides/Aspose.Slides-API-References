---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides pro Android prostřednictvím referenční dokumentace Java API
description: Představuje správce, který drží chování zástupců zápatí, data-času, číslování stránek rozložení snímku a všech podřízených zástupců.
type: docs
url: /cs/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Představuje správce, který drží chování zápatí rozložení snímku, zástupců data-času, číslování stránek a všech podřízených zástupců. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozložení.

## Metody

| Metoda | Popis |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mění viditelnost zástupce zápatí rozložení snímku a všech podřízených zástupců zápatí. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mění viditelnost zástupce číslování stránek rozložení snímku a všech podřízených zástupců číslování stránek. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mění viditelnost zástupce data-času rozložení snímku a všech podřízených zástupců data-času. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Nastavuje text do zástupce zápatí rozložení snímku a všech podřízených zástupců zápatí. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Nastavuje text do zástupce data-času rozložení snímku a všech podřízených zástupců data-času. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Mění viditelnost zástupce zápatí rozložení snímku a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na hlavním snímku.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zápatí zástupci jsou viditelní, jinak jsou skrytí. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Mění viditelnost zástupce číslování stránek rozložení snímku a všech podřízených zástupců číslování stránek. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozložení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – čísla stránek jsou viditelná, jinak jsou skrytá. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Mění viditelnost zástupce data-času rozložení snímku a všech podřízených zástupců data-času. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozložení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| isVisible | boolean | true – zástupci data-času jsou viditelní, jinak jsou skrytí. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Nastavuje text do zástupce zápatí rozložení snímku a všech podřízených zástupců zápatí. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozložení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Nastavuje text do zástupce data-času rozložení snímku a všech podřízených zástupců data-času. Podřízené zástupce znamenají, že zástupci jsou obsaženi na závislých snímcích. Závislé snímky používají a jsou závislé na snímku rozložení.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k nastavení. |