---
title: ColorOperationCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک مجموعه از عملیات تبدیل رنگ است.
type: docs
url: /fa/com.aspose.slides/coloroperationcollection/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
```
public final class ColorOperationCollection implements IColorOperationCollection
```

نمایشگر یک مجموعه از عملیات تبدیل رنگ.
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عملیات‌ها در یک مجموعه را برمی‌گرداند. |
| [get_Item(int index)](#get-Item-int-) | عملیات را در ایندکس مشخص برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | عملیات را در ایندکس مشخص برمی‌گرداند یا تنظیم می‌کند. |
| [add(int operation, float parameter)](#add-int-float-) | یک عملیات جدید را به انتهای مجموعه اضافه می‌کند. |
| [add(int operation)](#add-int-) | یک عملیات جدید را به انتهای مجموعه اضافه می‌کند. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | عملیات جدید را به یک مجموعه وارد می‌کند. |
| [insert(int position, int operation)](#insert-int-int-) | عملیات جدید را به یک مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عملیات رنگ را از یک مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام عملیات‌های رنگی را حذف می‌کند. |
| [iterator()](#iterator--) | یک شمارنده که از مجموعه عبور می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
| [deepClone()](#deepClone--) | یک کپی از مجموعه ColorOperationCollection ایجاد می‌کند. |
| [cloneT()](#cloneT--) | شیء فعلی را کلون می‌کند |

### size() {#size--}
```
public final int size()
```

تعداد عملیات‌ها در یک مجموعه را برمی‌گرداند. فقط خواندنی int.

**باز می‌گرداند:**
int

### get_Item(int index) {#get-Item-int-}
```
public final IColorOperation get_Item(int index)
```

عملیات را در ایندکس مشخص برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [ColorOperation](../../com.aspose.slides/coloroperation).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**باز می‌گرداند:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public final void set_Item(int index, IColorOperation value)
```

عملیات را در ایندکس مشخص برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [ColorOperation](../../com.aspose.slides/coloroperation).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public final IColorOperation add(int operation, float parameter)
```

یک عملیات جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operation | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

**باز می‌گرداند:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات اضافه‌شده.

### add(int operation) {#add-int-}
```
public final IColorOperation add(int operation)
```

یک عملیات جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operation | int | نوع عملیات. |

**باز می‌گرداند:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات اضافه‌شده.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public final IColorOperation insert(int position, int operation, float parameter)
```

عملیات جدید را به یک مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | int | شاخصی که عملیات در آن درج می‌شود. |
| operation | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

**باز می‌گرداند:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات درج‌شده.

### insert(int position, int operation) {#insert-int-int-}
```
public final IColorOperation insert(int position, int operation)
```

عملیات جدید را به یک مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | int | شاخصی که عملیات در آن درج می‌شود. |
| operation | int | نوع عملیات. |

**باز می‌گرداند:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات درج‌شده.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

عملیات رنگ را از یک مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص عملیات رنگ برای حذف. |

### clear() {#clear--}
```
public final void clear()
```

تمام عملیات‌های رنگی را حذف می‌کند.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iterator()
```

یک شمارنده که از مجموعه عبور می‌کند را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - یک IGenericEnumerator که می‌تواند برای عبور از مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IColorOperation> iteratorJava()
```

یک iterator جاوا برای کل مجموعه برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IColorOperation> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه هدف کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | شاخص شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است. فقط خواندنی boolean.

**باز می‌گرداند:**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را برمی‌گرداند. فقط خواندنی Object.

**باز می‌گرداند:**
java.lang.Object

### deepClone() {#deepClone--}
```
public final Object deepClone()
```

یک کپی از یک مجموعه ColorOperationCollection ایجاد می‌کند.

**باز می‌گرداند:**
java.lang.Object - یک java.lang.Object - مجموعه جدید [ColorOperationCollection](../../com.aspose.slides/coloroperationcollection).

### cloneT() {#cloneT--}
```
public final IColorOperationCollection cloneT()
```

شیء فعلی را کلون می‌کند

**باز می‌گرداند:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection) - کلون