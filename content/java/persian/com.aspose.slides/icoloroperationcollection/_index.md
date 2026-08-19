---
title: IColorOperationCollection
second_title: Aspose.Slides برای Java مرجع API
description: نمایانگر یک مجموعه از عملیات تبدیل رنگ است.
type: docs
url: /fa/com.aspose.slides/icoloroperationcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

نمایانگر مجموعه‌ای از عملیات تبدیل رنگ است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عملیات را در ایندکس مشخص بازمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | عملیات را در ایندکس مشخص بازمی‌گرداند یا تنظیم می‌کند. |
| [add(int operation, float parameter)](#add-int-float-) | یک عملیات جدید را به انتهای مجموعه اضافه می‌کند. |
| [add(int operation)](#add-int-) | یک عملیات جدید را به انتهای مجموعه اضافه می‌کند. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | عملیات جدید را به مجموعه وارد می‌کند. |
| [insert(int position, int operation)](#insert-int-int-) | عملیات جدید را به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عملیات رنگ را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام عملیات‌های رنگی را حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

عملیات را در ایندکس مشخص بازمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [IColorOperation](../../com.aspose.slides/icoloroperation).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

عملیات را در ایندکس مشخص بازمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [IColorOperation](../../com.aspose.slides/icoloroperation).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

یک عملیات جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operation | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

**بازگشت:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات اضافه‌شده.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

یک عملیات جدید را به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| operation | int | نوع عملیات. |

**بازگشت:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات اضافه‌شده.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

عملیات جدید را به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | int | ایندکسی که عملیات در آن وارد می‌شود. |
| operation | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

**بازگشت:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات وارد شده.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

عملیات جدید را به مجموعه وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| position | int | ایندکسی که عملیات در آن وارد می‌شود. |
| operation | int | نوع عملیات. |

**بازگشت:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات وارد شده.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عملیات رنگ را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس عملیات رنگی برای حذف. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عملیات‌های رنگی را حذف می‌کند.