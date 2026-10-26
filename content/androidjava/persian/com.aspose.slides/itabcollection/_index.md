---
title: ITabCollection
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک مجموعه از تب‌ها.
type: docs
url: /fa/com.aspose.slides/itabcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITabCollection extends IGenericCollection<ITab>
```

نمایانگر مجموعه‌ای از تب‌ها است.
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [add(double position, int align)](#add-double-int-) | Adds a Tab to the collection. |
| [add(ITab value)](#add-com.aspose.slides.ITab-) | Adds a Tab to the collection. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ITab get_Item(int index)
```

Gets the element at the specified index. فقط-خواندنی [ITab](../../com.aspose.slides/itab).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int |  |

**مقدار بازگشتی:**
[ITab](../../com.aspose.slides/itab)
### add(double position, int align) {#add-double-int-}
```
public abstract ITab add(double position, int align)
```

Adds a Tab to the collection.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| position | double | موقعیت Tab. |
| align | int | تراز Tab. |

**مقدار بازگشتی:**
[ITab](../../com.aspose.slides/itab) - Tab اضافه شده.
### add(ITab value) {#add-com.aspose.slides.ITab-}
```
public abstract int add(ITab value)
```

Adds a Tab to the collection.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [ITab](../../com.aspose.slides/itab) | شیء Tab که در انتهای مجموعه اضافه می‌شود. |

**مقدار بازگشتی:**
int - اندیسی که Tab در آن اضافه شد.
### clear() {#clear--}
```
public abstract void clear()
```

Removes all elements from the collection.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the element at the specified index of the collection.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنای عنصری که باید حذف شود. |