---
title: IBackdrop3DScene
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يعرّف مستوى تُطبق عليه التأثيرات مثل التوهج والظل بالنسبة للشكل الذي تُطبق عليه.
type: docs
url: /ar/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

يعرّف مستوى تُطبق عليه التأثيرات، مثل التوهج والظل، بالنسبة للشكل الذي تُطبق عليه.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | إرجاع أو تعيين متجه عادي. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | إرجاع أو تعيين متجه عادي. |
| [getAnchorPoint()](#getAnchorPoint--) | إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. |
| [getUpVector()](#getUpVector--) | إرجاع أو تعيين متجه يمثل الاتجاه العلوي. |
| [setUpVector(float[] value)](#setUpVector-float---) | إرجاع أو تعيين متجه يمثل الاتجاه العلوي. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

إرجاع أو تعيين متجه عادي. لتكون أكثر دقة، يحدد هذا السمة متجهًا عموديًا على وجه مستوى الخلفية. المتجه ممثَّل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**القيمة المرجعة:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

إرجاع أو تعيين متجه عادي. لتكون أكثر دقة، يحدد هذا السمة متجهًا عموديًا على وجه مستوى الخلفية. المتجه ممثَّل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت مستوى الخلفية. نقطة ثلاثية الأبعاد ممثَّلة بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**القيمة المرجعة:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت مستوى الخلفية. نقطة ثلاثية الأبعاد ممثَّلة بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

إرجاع أو تعيين متجه يمثل الاتجاه العلوي. لتكون أكثر دقة، يحدد هذا السمة متجهًا يمثل الاتجاه العلوي بالنسبة لوجه مستوى الخلفية. المتجه ممثَّل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**القيمة المرجعة:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

إرجاع أو تعيين متجه يمثل الاتجاه العلوي. لتكون أكثر دقة، يحدد هذا السمة متجهًا يمثل الاتجاه العلوي بالنسبة لوجه مستوى الخلفية. المتجه ممثَّل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |