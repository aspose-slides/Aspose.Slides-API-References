---
title: FontFallBackRulesCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: مجموعه‌ای از قوانین FontFallBack که توسط کاربر تعریف شده است را نشان می‌دهد
type: docs
url: /fa/com.aspose.slides/fontfallbackrulescollection/
---
**ارث‌بری:**
java.lang.Object

**تمام واسط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

نمایانگر مجموعه‌ای از قوانین FontFallBack است که توسط کاربر تعریف شده است
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [size()](#size--) | تعداد قوانین واقعاً موجود در مجموعه را برمی‌گرداند. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | یک قانون FallBack مشخص را به انتهای مجموعه اضافه می‌کند. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | اولین رخداد یک قانون FallBack خاص را از مجموعه حذف می‌کند. |
| [get_Item(int index)](#get-Item-int-) | قانون موجود در اندیس مشخص را برمی‌گرداند. |
| [iterator()](#iterator--) | یک enumerator که از میان مجموعه پیمایش می‌کند را برمی‌گرداند. |
| [iteratorJava()](#iteratorJava--) | یک iterator جاوا برای کل مجموعه را برمی‌گرداند. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | تمام المان‌های مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند. |
| [isSynchronized()](#isSynchronized--) | مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت نخ). |
| [getSyncRoot()](#getSyncRoot--) | ریشهٔ همگام‌سازی را برمی‌گرداند. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```


### size() {#size--}
```
public final int size()
```


تعداد قوانین واقعاً موجود در مجموعه را برمی‌گرداند. int فقط-خواندنی.

**باز می‌گرداند:**
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
>      //دریافت مجموعه قوانین خالی یا از پیش مقداردهی‌شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //اضافه کردن قانون جدید به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | قانون مشخص برای اضافه کردن |

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
>      //دریافت مجموعه قوانین خالی یا از پیش مقداردهی‌شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //اضافه کردن چندین قانون به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //دریافت شیء اولین قانون در مجموعه
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
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | قانونی که از مجموعه باید حذف شود. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```


قانون موجود در اندیس مشخص را برمی‌گرداند. [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) فقط-خواندنی.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //دریافت مجموعه قوانین خالی یا پیش‌مقداردهی‌شده از FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //اضافه کردن چندین قانون به مجموعه
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //دریافت شیء اولین قانون در مجموعه
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

**باز می‌گرداند:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```


یک enumerator که از میان مجموعه پیمایش می‌کند را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - یک IGenericEnumerator که می‌تواند برای پیمایش مجموعه استفاده شود.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```


یک iterator جاوا برای کل مجموعه را برمی‌گرداند.

**باز می‌گرداند:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - یک java.util.Iterator برای کل مجموعه.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


تمام المان‌های مجموعه را به آرایهٔ مشخص‌شده کپی می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | آرایه هدف. |
| index | int | اندیس شروع در آرایه هدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


مقداری را برمی‌گرداند که نشان می‌دهد دسترسی به مجموعه همگام‌سازی شده است (امنیت نخ). boolean فقط-خواندنی.

**باز می‌گرداند:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


ریشهٔ همگام‌سازی را برمی‌گرداند. Object فقط-خواندنی.

**باز می‌گرداند:**
java.lang.Object