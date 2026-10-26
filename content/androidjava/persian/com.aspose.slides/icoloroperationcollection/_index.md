---
title: IColorOperationCollection
second_title: Aspose.Slides برای Android با استفاده از مرجع API جاوا
description: نماینده‌ای از مجموعه عملیات تبدیل رنگ.
type: docs
url: /fa/com.aspose.slides/icoloroperationcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:** 
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

نماینده‌ای از مجموعه عملیات تبدیل رنگ.

## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عملیات در اندیس مشخص‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | عملیات در اندیس مشخص‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [add(int operation, float parameter)](#add-int-float-) | یک عملیات جدید به انتهای مجموعه اضافه می‌کند. |
| [add(int operation)](#add-int-) | یک عملیات جدید به انتهای مجموعه اضافه می‌کند. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | عملیات جدید را به مجموعه وارد می‌کند. |
| [insert(int position, int operation)](#insert-int-int-) | عملیات جدید را به مجموعه وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | عملیات رنگ را از یک مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام عملیات‌های رنگ را حذف می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```

عملیات را در اندیس مشخص‌شده برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IColorOperation](../../com.aspose.slides/icoloroperation).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**بازگرداندن:**
[IColorOperation](../../com.aspose.slides/icoloroperation)

### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```

عملیات را در اندیس مشخص‌شده برمی‌گرداند یا تنظیم می‌کند. خواندن/نوشتن [IColorOperation](../../com.aspose.slides/icoloroperation).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```

یک عملیات جدید به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

**بازگرداندن:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات اضافه‌شده.

### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```

یک عملیات جدید به انتهای مجموعه اضافه می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | نوع عملیات. |

**بازگرداندن:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات اضافه‌شده.

### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```

عملیات جدید را به مجموعه وارد می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | اندیس که عملیات در آن وارد می‌شود. |
| operation | int | نوع عملیات. |
| parameter | float | پارامتر عملیات. |

**بازگرداندن:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات وارد‌شده.

### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```

عملیات جدید را به مجموعه وارد می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | اندیس که عملیات در آن وارد می‌شود. |
| operation | int | نوع عملیات. |

**بازگرداندن:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - عملیات وارد‌شده.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

عملیات رنگ را از یک مجموعه حذف می‌کند.

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس عملیات رنگ برای حذف. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام عملیات‌های رنگ را حذف می‌کند.