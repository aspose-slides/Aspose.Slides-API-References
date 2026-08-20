---
title: Backdrop3DScene
second_title: مرجع API لأسبوز سلايدز للجاڤا
description: يعرّف سطحًا تُطبق عليه التأثيرات مثل التوهج والظل بالنسبة للشكل الذي تُطبق عليه.
type: docs
url: /ar/com.aspose.slides/backdrop3dscene/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

يعرّف سطحًا تُطبق عليه التأثيرات، مثل التوهج والظل، بالنسبة للشكل الذي تُطبق عليه.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | يعيد أو يضبط متجهًا طبيعيًا. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | يعيد أو يضبط متجهًا طبيعيًا. |
| [getAnchorPoint()](#getAnchorPoint--) | يعيد أو يضبط نقطة في الفضاء ثلاثي الأبعاد. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | يعيد أو يضبط نقطة في الفضاء ثلاثي الأبعاد. |
| [getUpVector()](#getUpVector--) | يعيد أو يضبط متجهًا يمثل الاتجاه الأعلى. |
| [setUpVector(float[] value)](#setUpVector-float---) | يعيد أو يضبط متجهًا يمثل الاتجاه الأعلى. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**القيمة المرجعة:**
long

### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

يعيد أو يضبط متجهًا طبيعيًا. لتكون أكثر دقة، يحدد هذا السمة متجهًا عموديًا على سطح طائرة الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**القيمة المرجعة:**
float[]

### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

يعيد أو يضبط متجهًا طبيعيًا. لتكون أكثر دقة، يحدد هذا السمة متجهًا عموديًا على سطح طائرة الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

يعيد أو يضبط نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت طائرة الخلفية. النقطة ثلاثية الأبعاد ممثلة بمصفوفة من 3 قيم float تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**القيمة المرجعة:**
float[]

### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

يعيد أو يضبط نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت طplane الخلفية. النقطة ثلاثية الأبعاد ممثلة بمصفوفة من 3 قيم float تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

يعيد أو يضبط متجهًا يمثل الاتجاه الأعلى. لتكون أكثر دقة، يحدد هذا السمة متجهًا يمثل الاتجاه الأعلى بالنسبة لسطح طplane الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**القيمة المرجعة:**
float[]

### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

يعيد أو يضبط متجهًا يمثل الاتجاه الأعلى. لتكون أكثر دقة، يحدد هذا السمة متجهًا يمثل الاتجاه الأعلى بالنسبة لسطح طplane الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |