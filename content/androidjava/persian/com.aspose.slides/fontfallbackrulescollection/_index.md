---
title: FontFallBackRulesCollection
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر مجموعه‌ای از قواعد FontFallBack که توسط کاربر تعریف شده است
type: docs
url: /fa/com.aspose.slides/fontfallbackrulescollection/
---
**ارث‌بری:**  
java.lang.Object

**همه رابط‌های پیاده‌سازی شده:**  
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)  
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

نمایانگر یک مجموعه از قواعد FontFallBack که توسط کاربر تعریف شده است

## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |

## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد قواعدی که در واقع در مجموعه موجود هستند را برمی‌گرداند. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | یک قانون FallBack مشخص را به انتهای مجموعه اضافه می‌کند. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | اولین رخداد یک قانون FallBack خاص را از مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | قانون موجود در اندیس مشخص شده را برمی‌گرداند. |
| [iterator()](#iterator--) | یک شمارنده را برمی‌گرداند که از طریق مجموعه تکرار می‌کند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | یک مقدار که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است را برمی‌گرداند. |
| [getSyncRoot()](#getSyncRoot--) | یک ریشهٔ همگام‌سازی را برمی‌گرداند. |

### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```

### size() {#size--}
```
public final int size()
```

تعداد قواعدی که در واقع در مجموعه موجود هستند را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**  
int

### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```

یک قانون FallBack مشخص را به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //دریافت مجموعه قواعد خالی یا از پیش مقداردهی شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //افزودن قاعدهٔ جدید به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | قانون مشخص برای افزودن |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```

اولین رخداد یک قانون FallBack خاص را از مجموعه حذف می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //دریافت مجموعه قواعد خالی یا از پیش مقداردهی شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //افزودن چند قاعده به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //دریافت شیء اولین قاعده در مجموعه
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //حذف
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | قانون برای حذف از مجموعه. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```

قانون موجود در اندیس مشخص شده را برمی‌گرداند. فقط-خواندنی [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //دریافت مجموعه قواعد خالی یا از پیش مقداردهی شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //افزودن چند قاعده به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //دریافت شیء اولین قاعده در مجموعه
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```

یک شمارنده را برمی‌گرداند که از طریق مجموعه تکرار می‌کند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - یک IGenericEnumerator که می‌تواند برای تکرار در مجموعه استفاده شود.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```

یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**بازگشت:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - یک java.util.Iterator برای کل مجموعه.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

تمام عناصر را از مجموعه به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایهٔ هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

یک مقدار که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده (thread-safe) است را برمی‌گرداند. فقط-خواندنی boolean.

**بازگشت:**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

یک ریشهٔ همگام‌سازی را برمی‌گرداند. فقط-خواندنی Object.

**بازگشت:**  
java.lang.Object