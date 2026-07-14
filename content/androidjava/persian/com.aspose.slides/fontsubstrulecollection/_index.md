---
title: FontSubstRuleCollection
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر مجموعه‌ای از جایگزینی فونت‌ها.
type: docs
url: /fa/com.aspose.slides/fontsubstrulecollection/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

نمایانگر مجموعه‌ای از جایگزینی فونت‌ها است.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعا در مجموعه وجود دارند را برمی‌گرداند. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | قانون جایگزینی فونت جدید را به مجموعه اضافه می‌کند |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در اندیس مشخص‌شده را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای تمام مجموعه برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصری را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | یک مقدار را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت‌پذیر). |
| [getSyncRoot()](#getSyncRoot--) | ریشه همگام‌سازی را برمی‌گرداند. |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```


### size() {#size--}
```
public final int size()
```


تعداد عناصری که واقعا در مجموعه وجود دارند را برمی‌گرداند. int فقط خواندنی.

**بازگشت:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```


قانون جایگزینی فونت جدید را به مجموعه اضافه می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```


اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | قانون جایگزینی فونت برای حذف از مجموعه. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```


عنصر موجود در اندیس مشخص‌شده را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```


یک شمارنده را برمی‌گرداند که از طریق مجموعه پیمایش می‌کند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```


یک iterator جاوا برای تمام مجموعه برمی‌گرداند.

**بازگشت:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تمام عناصری را از مجموعه به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


یک مقدار را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت‌پذیر). boolean فقط خواندنی.

**بازگشت:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشه همگام‌سازی را برمی‌گرداند. Object فقط خواندنی.

**بازگشت:**
java.lang.Object