---
title: FillOverlay
second_title: مرجع API لـ Aspose.Slides للفئة Java
description: يمثل تأثير Fill Overlay.
type: docs
url: /ar/com.aspose.slides/filloverlay/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

يمثل تأثير Fill Overlay. يمكن استخدام Fill Overlay لتحديد تعبئة إضافية لكائن ودمج التعبئتين معًا.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Fill format. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير Fill Overlay الفعّال مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يتحدد ما إذا كان [FillOverlay](../../com.aspose.slides/filloverlay) المحدد مساويًا للـ [FillOverlay](../../com.aspose.slides/filloverlay) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Fill format. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. قراءة/كتابة [FillBlendMode](../../com.aspose.slides/fillblendmode).

**الإرجاع:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. قراءة/كتابة [FillBlendMode](../../com.aspose.slides/fillblendmode).

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

يحصل على بيانات تأثير Fill Overlay الفعّال مع تطبيق الوراثة.

**الإرجاع:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. للقراءة فقط long.

**الإرجاع:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يتحدد ما إذا كان [FillOverlay](../../com.aspose.slides/filloverlay) المحدد مساويًا للـ [FillOverlay](../../com.aspose.slides/filloverlay) الحالي.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| obj | java.lang.Object | [FillOverlay](../../com.aspose.slides/filloverlay) للمقارنة. |

**الإرجاع:**
boolean - true إذا كانت الكائنات متساوية؛ وإلا false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**الإرجاع:**
int - رمز تجزئة للكائن الحالي.