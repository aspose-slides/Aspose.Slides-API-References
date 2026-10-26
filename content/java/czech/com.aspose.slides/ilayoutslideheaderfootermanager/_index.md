---
title: ILayoutSlideHeaderFooterManager
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje manažera, který obsahuje chování placeholderů zápatí snímku rozvržení, data-času, číslování stránek a všech dětských placeholderů.
type: docs
url: /cs/com.aspose.slides/ilayoutslideheaderfootermanager/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlideHeaderFooterManager](../../com.aspose.slides/ibaseslideheaderfootermanager)
```
public interface ILayoutSlideHeaderFooterManager extends IBaseSlideHeaderFooterManager
```

Reprezentuje správce, který obsahuje chování zápatí rozvržení snímku, placeholderu data-času, placeholderu čísla stránky a všech dětských placeholderů. Dětské placeholdery znamenají, že placeholdery jsou obsaženy na závislých snímcích. Závislé snímky používají a jsou závislé na rozvržení snímku.

## Methods

| Method | Description |
| --- | --- |
| [setFooterAndChildFootersVisibility(boolean isVisible)](#setFooterAndChildFootersVisibility-boolean-) | Mění viditelnost placeholderu zápatí rozvržení snímku a všech dětských placeholderů zápatí. |
| [setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)](#setSlideNumberAndChildSlideNumbersVisibility-boolean-) | Mění viditelnost placeholderu čísla stránky rozvržení snímku a všech dětských placeholderů číslování stránek. |
| [setDateTimeAndChildDateTimesVisibility(boolean isVisible)](#setDateTimeAndChildDateTimesVisibility-boolean-) | Mění viditelnost placeholderu data-času rozvržení snímku a všech dětských placeholderů data-času. |
| [setFooterAndChildFootersText(String text)](#setFooterAndChildFootersText-java.lang.String-) | Nastaví text do placeholderu zápatí rozvržení snímku a všech dětských placeholderů zápatí. |
| [setDateTimeAndChildDateTimesText(String text)](#setDateTimeAndChildDateTimesText-java.lang.String-) | Nastaví text do placeholderu data-času rozvržení snímku a všech dětských placeholderů data-času. |

### setFooterAndChildFootersVisibility(boolean isVisible) {#setFooterAndChildFootersVisibility-boolean-}
```
public abstract void setFooterAndChildFootersVisibility(boolean isVisible)
```

Mění viditelnost placeholderu zápatí rozvržení snímku a všech dětských placeholderů zápatí. Dětské placeholdery znamenají, že placeholdery jsou obsaženy na závislých snímcích. Závislé snímky používají a jsou závislé na master slide.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí placeholdery zápatí, jinak je skryje. |

### setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible) {#setSlideNumberAndChildSlideNumbersVisibility-boolean-}
```
public abstract void setSlideNumberAndChildSlideNumbersVisibility(boolean isVisible)
```

Mění viditelnost placeholderu čísla stránky rozvržení snímku a všech dětských placeholderů číslování stránek. Dětské placeholdery znamenají, že placeholdery jsou obsaženy na závislých snímcích. Závislé snímky používají a jsou závislé na rozvržení snímku.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí placeholdery číslování stránek, jinak je skryje. |

### setDateTimeAndChildDateTimesVisibility(boolean isVisible) {#setDateTimeAndChildDateTimesVisibility-boolean-}
```
public abstract void setDateTimeAndChildDateTimesVisibility(boolean isVisible)
```

Mění viditelnost placeholderu data-času rozvržení snímku a všech dětských placeholderů data-času. Dětské placeholdery znamenají, že placeholdery jsou obsaženy na závislých snímcích. Závislé snímky používají a jsou závislé na rozvržení snímku.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| isVisible | boolean | true – zobrazí placeholdery data-času, jinak je skryje. |

### setFooterAndChildFootersText(String text) {#setFooterAndChildFootersText-java.lang.String-}
```
public abstract void setFooterAndChildFootersText(String text)
```

Nastaví text do placeholderu zápatí rozvržení snímku a všech dětských placeholderů zápatí. Dětské placeholdery znamenají, že placeholdery jsou obsaženy na závislých snímcích. Závislé snímky používají a jsou závislé na rozvržení snímku.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |

### setDateTimeAndChildDateTimesText(String text) {#setDateTimeAndChildDateTimesText-java.lang.String-}
```
public abstract void setDateTimeAndChildDateTimesText(String text)
```

Nastaví text do placeholderu data-času rozvržení snímku a všech dětských placeholderů data-času. Dětské placeholdery znamenají, že placeholdery jsou obsaženy na závislých snímcích. Závislé snímky používají a jsou závislé na rozvržení snímku.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Text, který se má nastavit. |