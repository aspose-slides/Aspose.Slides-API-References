---
title: IBlurEffectiveData
second_title: Aspose.Slides لأندرويد عبر مرجع API لجافا
description: كائن غير قابل للتغيير يمثل تأثير الضبابية المطبق على الشكل بالكامل بما في ذلك التعبئة.
type: docs
url: /ar/com.aspose.slides/iblureffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

كائن غير قابل للتغيير يمثل تأثير الضبابية المطبق على الشكل بالكامل، بما في ذلك التعبئة. جميع قنوات اللون، بما فيها ألفا، تتأثر.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getRadius()](#getRadius--) | إرجاع أو تعيين نصف قطر الضبابية. |
| [getGrow()](#getGrow--) | يحدد ما إذا كان يجب توسيع حدود الكائن نتيجةً للضبابية. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


إرجاع أو تعيين نصف قطر الضبابية. للقراءة فقط double.

**الإرجاع:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


يحدد ما إذا كان يجب توسيع حدود الكائن نتيجةً للضبابية. True تشير إلى أن الحدود قد تم توسيعها بينما false تشير إلى العكس. للقراءة فقط boolean.

**الإرجاع:**
boolean