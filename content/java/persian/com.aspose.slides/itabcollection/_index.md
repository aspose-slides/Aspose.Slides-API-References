---
title: ITabCollection
second_title: Aspose.Slides برای مرجع API جاوا
description: نماینده یک مجموعه از تب‌ها.
type: docs
url: /fa/com.aspose.slides/itabcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

نمایش‌دهنده مجموعه‌ای از تب‌ها.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری را که در اندیس مشخص شده قرار دارد، دریافت می‌کند. |
| [add(double position, int align)](#add-double-int-) | یک Tab را به مجموعه اضافه می‌کند. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | یک Tab را به مجموعه اضافه می‌کند. |
| [clear()](#clear--) | تمام عناصر را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عنصری را که در اندیس مشخص شده از مجموعه قرار دارد، حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

عنصری را که در اندیس مشخص شده قرار دارد، دریافت می‌کند. فقط-خواندنی [ITab](../../com.aspose.slides/itab).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

یک Tab را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | double | موقعیت Tab. |
| align | int | تراز Tab. |

**بازگشت:**
[ITab](../../com.aspose.slides/itab) - Tab اضافه شده.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

یک Tab را به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | شیء Tab که در انتهای مجموعه اضافه می‌شود. |

**بازگشت:**
int - شاخصی که Tab در آن اضافه شده است.
### clear() {#clear--}
```
public abstract void clear()
```

تمام عناصر را از مجموعه حذف می‌کند.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عنصری را که در اندیس مشخص شده از مجموعه قرار دارد، حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-پایه عنصری که باید حذف شود. |