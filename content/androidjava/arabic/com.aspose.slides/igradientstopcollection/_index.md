---
title: IGradientStopCollection
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل مجموعة من نقاط التدرج.
type: docs
url: /ar/com.aspose.slides/igradientstopcollection/
---
**جميع الواجهات المنفذة:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

يمثل مجموعة من نقاط التدرج.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | يعيد نقطة التدرج بحسب الفهرس. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | ينشئ نقطة التدرج الجديدة ويُدخلها في الفهرس المحدد داخل المجموعة. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويُدخلها في الفهرس المحدد داخل المجموعة. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | ينشئ نقطة التدرج الجديدة ويُدخلها في الفهرس المحدد داخل المجموعة. |
| [removeAt(int index)](#removeAt-int-) | يزيل نقطة التدرج في الفهرس المحدد. |
| [clear()](#clear--) | يزيل جميع نقاط التدرج من المجموعة. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```

يعيد نقطة التدرج بحسب الفهرس.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int |  |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.lang.Integer | لون نقطة التدرج الجديدة. |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويضيفها إلى نهاية المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |

**القيمة المرجعة:**
[IGradientStop](../../com.aspose.slides/igradientstop) - فهرس نقطة التدرج الجديدة في المجموعة.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```

ينشئ نقطة التدرج الجديدة ويُدخلها في الفهرس المحدد داخل المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدخال نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| color | java.lang.Integer | لون نقطة التدرج الجديدة. |
### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```

ينشئ نقطة التدرج الجديدة ويُدخلها في الفهرس المحدد داخل المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدخال نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| presetColor | int | لون نقطة التدرج الجديدة. |
### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```

ينشئ نقطة التدرج الجديدة ويُدخلها في الفهرس المحدد داخل المجموعة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | الفهرس في المجموعة حيث سيتم إدخال نقطة التدرج الجديدة. |
| position | float | موضع نقطة التدرج الجديدة. |
| schemeColor | int | لون نقطة التدرج الجديدة. |
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

يزيل نقطة التدرج في الفهرس المحدد.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| index | int | فهرس نقطة التدرج التي يجب حذفها. |
### clear() {#clear--}
```
public abstract void clear()
```

يزيل جميع نقاط التدرج من المجموعة.