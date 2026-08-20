---
title: IBlurEffectiveData
second_title: Aspose.Slides لواجهة برمجة تطبيقات Java
description: كائن ثابت يمثل تأثير الضبابية المُطبق على الشكل بأكمله بما في ذلك التعبئة.
type: docs
url: /ar/com.aspose.slides/iblureffectivedata/
---
**جميع الواجهات المطبقة:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

كائن ثابت يمثل تأثير الضبابية المُطبق على الشكل بأكمله، بما في ذلك التعبئة. تتأثر جميع قنوات اللون، بما في ذلك ألفا.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | إرجاع أو تعيين نصف قطر الضبابية. |
| [getGrow()](#getGrow--) | تحديد ما إذا كان يجب توسيع حدود الكائن نتيجةً للضبابية. |

### getRadius() {#getRadius--}
```
public abstract double getRadius()
```

إرجاع أو تعيين نصف قطر الضبابية. قراءة فقط double.

**الإرجاع:**
double

### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```

تحديد ما إذا كان يجب توسيع حدود الكائن نتيجةً للضبابية. القيمة True تشير إلى أن الحدود قد نمت بينما القيمة false تشير إلى عدم ذلك. قراءة فقط boolean.

**الإرجاع:**
boolean