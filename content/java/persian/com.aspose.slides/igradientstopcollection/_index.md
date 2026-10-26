---
title: IGradientStopCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: یک مجموعه از توقف‌های گرادیان را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/igradientstopcollection/
---
**همه واسط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

یک مجموعه از توقف‌گرادیان را توصیف می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | توقف‌گرادیان را بر اساس شاخص باز می‌گرداند. |
| [add(float position, Color color)](#add-float-java.awt.Color-) | یک توقف‌گرادیان جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | یک توقف‌گرادیان جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | یک توقف‌گرادیان جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید. |
| [insert(int index, float position, Color color)](#insert-int-float-java.awt.Color-) | یک توقف‌گرادیان جدید ایجاد می‌کند و در شاخص مشخص شده به مجموعه وارد می‌کند. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | یک توقف‌گرادیان جدید ایجاد می‌کند و در شاخص مشخص شده به مجموعه وارد می‌کند. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | یک توقف‌گرادیان جدید ایجاد می‌کند و در شاخص مشخص شده به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک توقف‌گرادیان را در شاخص مشخص شده حذف می‌کند. |
| [clear()](#clear--) | تمام توقف‌گرادیان‌ها را از یک مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

توقف‌گرادیان را بر اساس شاخص باز می‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Color color) {#add-float-java.awt.Color-}
```
public abstract IGradientStop add(float position, Color color)
```

یک توقف‌گرادیان جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت توقف‌گرادیان جدید. |
| color | java.awt.Color | رنگ توقف‌گرادیان جدید. |

**بازگشت:**
[IGradientStop](../../com.aspose.slides/igradientstop) - اندیس توقف‌گرادیان جدید در مجموعه.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

یک توقف‌گرادیان جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت توقف‌گرادیان جدید. |
| presetColor | int | رنگ توقف‌گرادیان جدید. |

**بازگشت:**
[IGradientStop](../../com.aspose.slides/igradientstop) - اندیس توقف‌گرادیان جدید در مجموعه.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

یک توقف‌گرادیان جدید ایجاد می‌کند و به انتهای مجموعه اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | float | موقعیت توقف‌گرادیان جدید. |
| schemeColor | int | رنگ توقف‌گرادیان جدید. |

**بازگشت:**
[IGradientStop](../../com.aspose.slides/igradientstop) - اندیس توقف‌گرادیان جدید در مجموعه.
### insert(int index, float position, Color color) {#insert-int-float-java.awt.Color-}
```
public abstract void insert(int index, float position, Color color)
```

یک توقف‌گرادیان جدید ایجاد می‌کند و در شاخص مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص در مجموعه‌ای که توقف‌گرادیان جدید در آن وارد می‌شود. |
| position | float | موقعیت توقف‌گرادیان جدید. |
| color | java.awt.Color | رنگ توقف‌گرادیان جدید. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

یک توقف‌گرادیان جدید ایجاد می‌کند و در شاخص مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص در مجموعه‌ای که توقف‌گرادیان جدید در آن وارد می‌شود. |
| position | float | موقعیت توقف‌گرادیان جدید. |
| presetColor | int | رنگ توقف‌گرادیان جدید. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

یک توقف‌گرادیان جدید ایجاد می‌کند و در شاخص مشخص شده به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص در مجموعه‌ای که توقف‌گرادیان جدید در آن وارد می‌شود. |
| position | float | موقعیت توقف‌گرادیان جدید. |
| schemeColor | int | رنگ توقف‌گرادیان جدید. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک توقف‌گرادیان را در شاخص مشخص شده حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص یک توقف‌گرادیان که باید حذف شود. |
### clear() {#clear--}
```
public abstract void clear()
```

تمام توقف‌گرادیان‌ها را از یک مجموعه حذف می‌کند.