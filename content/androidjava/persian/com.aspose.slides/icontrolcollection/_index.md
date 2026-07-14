---
title: IControlCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک مجموعه از کنترل‌های ActiveX.
type: docs
url: /fa/com.aspose.slides/icontrolcollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

یک مجموعه از کنترل‌های ActiveX.
## متدها

| متد | توضیح |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | یک کنترل ActiveX را از مجموعه حذف می‌کند. |
| [removeAt(int index)](#removeAt-int-) | یک کنترل ActiveX که در موقعیت مشخصی ذخیره شده است را از مجموعه حذف می‌کند. |
| [clear()](#clear--) | تمام کنترل‌ها را از مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | یک کنترل را در موقعیت مشخص برمی‌گرداند. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | یک کنترل جدید ایجاد کرده و به مجموعه اضافه می‌کند. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```

یک کنترل ActiveX را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | یک کنترل برای حذف. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

یک کنترل ActiveX که در موقعیت مشخصی ذخیره شده است را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | نمایهٔ یک کنترل برای حذف. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام کنترل‌ها را از مجموعه حذف می‌کند.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```

یک کنترل را در موقعیت مشخص برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | نمایهٔ یک کنترل. |

**بازگشت:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```

یک کنترل جدید ایجاد کرده و به مجموعه اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| controlType | int | نوع کنترل برای افزودن. |
| x | float | مختصات X برای طرف چپ قاب شکل. |
| y | float | مختصات Y برای طرف بالای قاب شکل. |
| width | float | عرض قاب شکل. |
| height | float | ارتفاع قاب شکل. |

**بازگشت:**
[IControl](../../com.aspose.slides/icontrol) - کنترل ایجاد شده [IControl](../../com.aspose.slides/icontrol).