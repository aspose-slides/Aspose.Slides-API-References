---
title: IGradientStopCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایش‌دهندهٔ یک مجموعه از توقف‌های گرادیان.
type: docs
url: /fa/com.aspose.slides/igradientstopcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

نمایش‌دهندهٔ یک مجموعه از توقف‌های گرادیان.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | توقف‌گرادیان را بر اساس ایندکس برمی‌گرداند. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | توقف‌گرادیان جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | توقف‌گرادیان جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | توقف‌گرادیان جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | توقف‌گرادیان جدید را ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اضافه می‌کند. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | توقف‌گرادیان جدید را ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اضافه می‌کند. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | توقف‌گرادیان جدید را ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اضافه می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک توقف‌گرادیان را در اندیس مشخص‌شده حذف می‌کند. |
| [clear()](#clear--) | همهٔ توقف‌گرادیان‌ها را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

توقف‌گرادیان را بر اساس ایندکس برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گردد:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

توقف‌گرادیان جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت توقف‌گرادیان جدید. |
| color | java.lang.Integer | رنگ توقف‌گرادیان جدید. |

**بازمی‌گردد:**
[IGradientStop](../../com.aspose.slides/igradientstop) - اندیس توقف‌گرادیان جدید در مجموعه.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

توقف‌گرادیان جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت توقف‌گرادیان جدید. |
| presetColor | int | رنگ توقف‌گرادیان جدید. |

**بازمی‌گردد:**
[IGradientStop](../../com.aspose.slides/igradientstop) - اندیس توقف‌گرادیان جدید در مجموعه.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

توقف‌گرادیان جدید را ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت توقف‌گرادیان جدید. |
| schemeColor | int | رنگ توقف‌گرادیان جدید. |

**بازمی‌گردد:**
[IGradientStop](../../com.aspose.slides/igradientstop) - اندیس توقف‌گرادیان جدید در مجموعه.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

توقف‌گرادیان جدید را ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس در مجموعه که توقف‌گرادیان جدید در آن درج خواهد شد. |
| position | float | موقعیت توقف‌گرادیان جدید. |
| color | java.lang.Integer | رنگ توقف‌گرادیان جدید. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

توقف‌گرادیان جدید را ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس در مجموعه که توقف‌گرادیان جدید در آن درج خواهد شد. |
| position | float | موقعیت توقف‌گرادیان جدید. |
| presetColor | int | رنگ توقف‌گرادیان جدید. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

توقف‌گرادیان جدید را ایجاد می‌کند و در اندیس مشخص‌شده به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس در مجموعه که توقف‌گرادیان جدید در آن درج خواهد شد. |
| position | float | موقعیت توقف‌گرادیان جدید. |
| schemeColor | int | رنگ توقف‌گرادیان جدید. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک توقف‌گرادیان را در اندیس مشخص‌شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس توقف‌گرادیانی که باید حذف شود. |

### clear() {#clear--}
```
public abstract void clear()
```

همهٔ توقف‌گرادیان‌ها را از مجموعه حذف می‌کند.