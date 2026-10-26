---
title: IFontFallBackRulesCollection
second_title: مرجع API جاوا برای Aspose.Slides برای اندروید
description: نماینده‌ی مجموعه‌ای از قوانین FontFallBack که توسط کاربر تعریف می‌شود
type: docs
url: /fa/com.aspose.slides/ifontfallbackrulescollection/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

نماینده‌ی مجموعه‌ای از قوانین FontFallBack که توسط کاربر تعریف می‌شود
## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | قانون را در ایندکس مشخص شده دریافت می‌کند. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | یک قانون FallBack جدید به انتهای مجموعه اضافه می‌کند. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | اولین رخداد یک قانون FallBack خاص را از مجموعه حذف می‌کند. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

قانون را در ایندکس مشخص شده دریافت می‌کند. فقط خواندنی [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //دریافت مجموعه قوانین خالی یا از پیش مقداردهی شده از FontsManager
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

**بازگشت:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

یک قانون FallBack جدید به انتهای مجموعه اضافه می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //دریافت مجموعه قوانین خالی یا پیش‌مقداردهی شده از FontsManager
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
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | قانون مشخص‌شده برای اضافه‌کردن |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```

اولین رخداد یک قانون FallBack خاص را از مجموعه حذف می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //دریافت مجموعه قوانین خالی یا پیش‌مقداردهی شده از FontsManager
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
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | قانونی که باید از مجموعه حذف شود. |