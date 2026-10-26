---
title: IFontFallBackRulesCollection
second_title: Aspose.Slides لـ Android عبر مرجع Java API
description: يمثل مجموعة من قواعد FontFallBack المعرفة من قبل المستخدم
type: docs
url: /ar/com.aspose.slides/ifontfallbackrulescollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IFontFallBackRulesCollection extends IGenericCollection<IFontFallBackRule>
```

يمثل مجموعة من قواعد FontFallBack معرفة من قبل المستخدم
## الطرق

| طريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يقوم بجلب القاعدة عند الفهرس المحدد. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | يضيف قاعدة FallBack جديدة إلى نهاية المجموعة. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | يزيل أول ظهور لقاعدة FallBack معينة من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IFontFallBackRule get_Item(int index)
```

يقوم بجلب القاعدة عند الفهرس المحدد. للقراءة فقط [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //الحصول على مجموعة القواعد الفارغة أو المهيأة مسبقًا من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //إضافة عدة قواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //استرجاع كائن القاعدة الأولى في المجموعة
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public abstract void add(IFontFallBackRule sourceRule)
```

يضيف قاعدة FallBack جديدة إلى نهاية المجموعة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //الحصول على مجموعة القواعد الفارغة أو المهيأة مسبقًا من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //إضافة قاعدة جديدة إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | القاعدة المحددة للإضافة |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public abstract void remove(IFontFallBackRule targetRule)
```

يزيل أول ظهور لقاعدة FallBack معينة من المجموعة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //الحصول على مجموعة القواعد الفارغة أو المهيأة مسبقًا من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //إضافة عدة قواعد إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>      rulesList.add(new FontFallBackRule(0x3040, 0x309F, "MS Mincho"));
>      //استرجاع كائن القاعدة الأولى في المجموعة
>      IFontFallBackRule firstRule = rulesList.get_Item(0);
>      //إزالة 
>      rulesList.remove(firstRule);
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | القاعدة التي يجب إزالتها من المجموعة. |