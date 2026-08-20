---
title: IBackdrop3DScene
second_title: Aspose.Slides for Java API Reference
description: يحدد سطحًا يتم تطبيق تأثيرات مثل التوهج والظل عليه بالنسبة للشكل الذي تُطبّق عليه.
type: docs
url: /ar/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

يحدد سطحًا يتم تطبيق تأثيرات، مثل التوهج والظل، عليه بالنسبة للشكل الذي تُطبّق عليه.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | إرجاع أو تعيين متجه عادي. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | إرجاع أو تعيين متجه عادي. |
| [getAnchorPoint()](#getAnchorPoint--) | إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. |
| [getUpVector()](#getUpVector--) | إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. |
| [setUpVector(float[] value)](#setUpVector-float---) | إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

إرجاع أو تعيين متجه عادي. لتكون أكثر دقة، يحدد هذا الخاصية متجهًا عموديًا على وجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**الإرجاع:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

إرجاع أو تعيين متجه عادي. لتكون أكثر دقة، يحدد هذا الخاصية متجهًا عموديًا على وجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت سطح الخلفية. نقطة ثلاثية الأبعاد ممثلة بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**الإرجاع:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة في الفضاء التي تثبت سطح الخلفية. نقطة ثلاثية الأبعاد ممثلة بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. لتكون أكثر دقة، يحدد هذا الخاصية متجهًا يمثل الاتجاه الأعلى بالنسبة لوجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**الإرجاع:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. لتكون أكثر دقة، يحدد هذا الخاصية متجهًا يمثل الاتجاه الأعلى بالنسبة لوجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم عائمة تحدد إحداثيات X وY وZ. قراءة/كتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |