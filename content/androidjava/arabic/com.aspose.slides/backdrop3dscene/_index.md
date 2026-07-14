---
title: Backdrop3DScene
second_title: Aspose.Slides لـ Android عبر مرجع API لجافا
description: يعرّف مستوى يتم فيه تطبيق التأثيرات مثل التوهج والظل بالنسبة إلى الشكل الذي تُطبق عليه.
type: docs
url: /ar/com.aspose.slides/backdrop3dscene/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**  
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)  
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

يعرّف مستوى يتم فيه تطبيق التأثيرات مثل التوهج والظل بالنسبة إلى الشكل الذي تُطبق عليه.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | إرجاع أو تعيين متجه عمودي. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | إرجاع أو تعيين متجه عمودي. |
| [getAnchorPoint()](#getAnchorPoint--) | إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. |
| [getUpVector()](#getUpVector--) | إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. |
| [setUpVector(float[] value)](#setUpVector-float---) | إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط (long).

**الإرجاع:**  
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

إرجاع أو تعيين متجه عمودي. لتكون أكثر دقة، تُعرّف هذه الخاصية متجهًا عموديًا على وجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تُحدّد إحداثيات X وY وZ. قابل للقراءة والكتابة float[].

**الإرجاع:**  
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

إرجاع أو تعيين متجه عمودي. لتكون أكثر دقة، تُعرّف هذه الخاصية متجهًا عموديًا على وجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تُحدّد إحداثيات X وY وZ. قابل للقراءة والكتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة التي تُثبت مستوى الخلفية في الفضاء. النقطة ممثلة بمصفوفة من 3 قيم float تُحدّد إحداثيات X وY وZ. قابل للقراءة والكتابة float[].

**الإرجاع:**  
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

إرجاع أو تعيين نقطة في الفضاء ثلاثي الأبعاد. هذه النقطة هي النقطة التي تُثبت مستوى الخلفية في الفضاء. النقطة ممثلة بمصفوفة من 3 قيم float تُحدّد إحداثيات X وY وZ. قابل للقراءة والكتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. لتكون أكثر دقة، تُعرّف هذه الخاصية متجهًا يمثل الاتجاه الأعلى بالنسبة لوجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تُحدّد إحداثيات X وY وZ. قابل للقراءة والكتابة float[].

**الإرجاع:**  
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

إرجاع أو تعيين متجه يمثل الاتجاه الأعلى. لتكون أكثر دقة، تُعرّف هذه الخاصية متجهًا يمثل الاتجاه الأعلى بالنسبة لوجه سطح الخلفية. المتجه ممثل بمصفوفة من 3 قيم float تُحدّد إحداثيات X وY وZ. قابل للقراءة والكتابة float[].

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float[] |  |