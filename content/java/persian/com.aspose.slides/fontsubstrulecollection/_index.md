---
title: FontSubstRuleCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایش‌گر مجموعه‌ای از جایگزینی قلم‌ها.
type: docs
url: /fa/com.aspose.slides/fontsubstrulecollection/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)  
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

نمایش‌گر مجموعه‌ای از جایگزینی قلم‌ها.
## Constructors

| سازنده | شرح |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |

## Methods

| متد | شرح |
| --- | --- |
| [size()](#size--) | تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | قانون جایگزینی قلم جدید را به مجموعه اضافه می‌کند |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | عنصر موجود در ایندکس مشخص‌شده را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده که از طریق مجموعه پیمایش می‌کند را بازمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه بازمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقدار نشان‌دهنده این که دسترسی به مجموعه همگام‌سازی شده است (امنیت‌پذیر) را بازمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را بازمی‌گرداند. |

### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

تعداد عناصری که واقعاً در مجموعه موجود هستند را برمی‌گرداند. فقط‌خواندنی int.

**بازمی‌گرداند:**  
int

### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```

قانون جایگزینی قلم جدید را به مجموعه اضافه می‌کند

**پارامترها:**  
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```

اولین رخداد یک شیء خاص را از مجموعه حذف می‌کند.

**پارامترها:**  
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | قانون جایگزینی قلم برای حذف از مجموعه. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

عنصر موجود در ایندکس مشخص‌شده را برمی‌گرداند.

**پارامترها:**  
| پارامتر | نوع | شرح |
| --- | --- | --- |
| index | int |  |

**بازمی‌گرداند:**  
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```

یک شمارنده که از طریق مجموعه پیمایش می‌کند را بازمی‌گرداند.

**بازمی‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

یک iterator جاوا برای کل مجموعه بازمی‌گرداند.

**بازمی‌گرداند:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایه مشخص‌شده کپی می‌کند.

**پارامترها:**  
| پارامتر | نوع | شرح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | ایندکس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

مقداری را برمی‌گرداند که نشان می‌دهد آیا دسترسی به مجموعه همگام‌سازی شده است (امنیت‌پذیر). فقط‌خواندنی boolean.

**بازمی‌گرداند:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

ریشهٔ همگام‌سازی را بازمی‌گرداند. فقط‌خواندنی Object.

**بازمی‌گرداند:**  
java.lang.Object