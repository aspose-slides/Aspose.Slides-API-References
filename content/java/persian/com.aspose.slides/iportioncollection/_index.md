---
title: IPortionCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر مجموعه‌ای از بخش‌ها است.
type: docs
url: /fa/com.aspose.slides/iportioncollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

نمایانگر مجموعه‌ای از بخش‌ها است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص شده دریافت می‌کند. |
| [getCount()](#getCount--) | تعداد واقعی عناصر موجود در مجموعه را دریافت می‌کند. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | یک Portion را به انتهای مجموعه اضافه می‌کند. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | شاخص یک portion خاص را در مجموعه تعیین می‌کند. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | یک Portion را در اندیس مشخص شده در مجموعه درج می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | تعیین می‌کند که آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصر را در اندیس مشخص شده از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

عنصر را در اندیس مشخص شده دریافت می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

تعداد واقعی عناصر موجود در مجموعه را دریافت می‌کند. int فقط-خواندنی.

**بازگشت:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

یک Portion را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion برای افزودن به انتهای مجموعه. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

شاخص یک portion خاص را در مجموعه تعیین می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | portion را برای یافتن در مجموعه. |

**بازگشت:**
int - اگر آیتم در مجموعه یافت شد، شاخص آن؛ در غیر این صورت -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

یک Portion را در اندیس مشخص شده در مجموعه درج می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا که Portion باید در آن درج شود. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion برای درج. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

تعیین می‌کند که آیا [IGenericCollection](../../com.aspose.slides/igenericcollection) شامل مقدار خاصی است یا نه.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیء برای یافتن در [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**
boolean - اگر آیتم در [IGenericCollection](../../com.aspose.slides/igenericcollection) یافت شد، true؛ در غیر این صورت، false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

اولین رخداد یک شیء خاص را از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | شیء برای حذف از [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**بازگشت:**
boolean - اگر آیتم با موفقیت از [IGenericCollection](../../com.aspose.slides/igenericcollection) حذف شد، true؛ در غیر این صورت، false. این متد همچنین false برمی‌گرداند اگر آیتم در [IGenericCollection](../../com.aspose.slides/igenericcollection) اصلی یافت نشود.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصر را در اندیس مشخص شده از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر مبنا برای حذف عنصر. |