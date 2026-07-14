---
title: FontFallBackRulesCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من قواعد FontFallBack المعرفة من قبل المستخدم
type: docs
url: /ar/com.aspose.slides/fontfallbackrulescollection/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFontFallBackRulesCollection](../../com.aspose.slides/ifontfallbackrulescollection)
```
public class FontFallBackRulesCollection implements IFontFallBackRulesCollection
```

يمثل مجموعة من قواعد FontFallBack، يُعرّفها المستخدم
## المنشئون

| المنشئ | الوصف |
| --- | --- |
| [FontFallBackRulesCollection()](#FontFallBackRulesCollection--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [size()](#size--) | يُحصل على عدد القواعد الموجودة فعلياً في المجموعة. |
| [add(IFontFallBackRule sourceRule)](#add-com.aspose.slides.IFontFallBackRule-) | إضافة قاعدة FallBack محددة إلى نهاية المجموعة. |
| [remove(IFontFallBackRule targetRule)](#remove-com.aspose.slides.IFontFallBackRule-) | إزالة أول ظهور لقاعدة FallBack معينة من المجموعة. |
| [get_Item(int index)](#get-Item-int-) | يُحصل على القاعدة في الفهرس المحدد. |
| [iterator()](#iterator--) | إرجاع كائن مُعدِّ للعدّ (enumerator) الذي يتنقّل عبر المجموعة. |
| [iteratorJava()](#iteratorJava--) | إرجاع مُكرّر java للمجموعة بأكملها. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة. |
| [isSynchronized()](#isSynchronized--) | إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (آمن للمتعدد الخيوط). |
| [getSyncRoot()](#getSyncRoot--) | إرجاع جذر المُزامنة. |
### FontFallBackRulesCollection() {#FontFallBackRulesCollection--}
```
public FontFallBackRulesCollection()
```

### size() {#size--}
```
public final int size()
```

يُحصل على عدد القواعد الموجودة فعلياً في المجموعة. int للقراءة فقط.

**الإرجاع:**
int
### add(IFontFallBackRule sourceRule) {#add-com.aspose.slides.IFontFallBackRule-}
```
public final void add(IFontFallBackRule sourceRule)
```

إضافة قاعدة FallBack محددة إلى نهاية المجموعة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //الحصول على مجموعة القواعد الفارغة أو المُهيأة مسبقاً من FontsManager
>      IFontFallBackRulesCollection rulesList = pres.getFontsManager().getFontFallBackRulesCollection();
>      //إضافة قاعدة جديدة إلى المجموعة
>      rulesList.add(new FontFallBackRule(0x400,0x4FF, "Times New Roman"));
>  }
>  finally {
>      if (pres != null) pres.dispose();
>  }
>  ```


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| sourceRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | القاعدة المحددة للإضافة |

### remove(IFontFallBackRule targetRule) {#remove-com.aspose.slides.IFontFallBackRule-}
```
public final void remove(IFontFallBackRule targetRule)
```

إزالة أول ظهور لقاعدة FallBack معينة من المجموعة.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //الحصول على مجموعة القواعد الفارغة أو المُهيأة مسبقاً من FontsManager
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| targetRule | [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule) | القاعدة التي سيتم إزالتها من المجموعة. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontFallBackRule get_Item(int index)
```

يُحصل على القاعدة في الفهرس المحدد. للقراءة فقط [IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule).

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      //الحصول على مجموعة القواعد الفارغة أو المُهيأة مسبقاً من FontsManager
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


**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**الإرجاع:**
[IFontFallBackRule](../../com.aspose.slides/ifontfallbackrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iterator()
```

إرجاع كائن مُعدِّ للعدّ (enumerator) الذي يتنقّل عبر المجموعة.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontFallBackRule> iteratorJava()
```

إرجاع مُكرّر java للمجموعة بأكملها.

**الإرجاع:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontFallBackRule> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

نسخ جميع العناصر من المجموعة إلى المصفوفة المحددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | المصفوفة الهدف. |
| index | int | الفهرس الابتدائي في المصفوفة الهدف. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

إرجاع قيمة تشير إلى ما إذا كان الوصول إلى المجموعة متزامناً (آمن للمتعدد الخيوط). boolean للقراءة فقط.

**الإرجاع:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

إرجاع جذر المُزامنة. Object للقراءة فقط.

**الإرجاع:**
java.lang.Object