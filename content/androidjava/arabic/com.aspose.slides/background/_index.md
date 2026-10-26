---
title: Background
second_title: Aspose.Slides لأندرويد عبر مرجع API جافا
description: يمثل خلفية شريحة.
type: docs
url: /ar/com.aspose.slides/background/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**جميع الواجهات المُطبقة:**  
[com.aspose.slides.IBackground](../../com.aspose.slides/ibackground), com.aspose.slides.IDOMObject  
```
public final class Background extends PVIObject implements IBackground, IDOMObject
```

يمثل خلفية الشريحة.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | إرجاع نوع تعبئة الخلفية. |
| [setType(byte value)](#setType-byte-) | إرجاع نوع تعبئة الخلفية. |
| [getFillFormat()](#getFillFormat--) | إرجاع كائن FillFormat لتعبئة BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | إرجاع كائن EffectFormat لتعبئة BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | إرجاع كائن ColorFormat لتعبئة BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | إرجاع فهرس تعبئة BackgroundType.Themed في مجموعة سمة الخلفية. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | إرجاع فهرس تعبئة BackgroundType.Themed في مجموعة سمة الخلفية. |
| [getEffective()](#getEffective--) | الحصول على بيانات الخلفية الفعّالة مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | إرجاع الشريحة الأصلية لشكل. |
| [getPresentation()](#getPresentation--) | إرجاع العرض التقديمي الأصلي لشريحة. |

### getType() {#getType--}
```
public final byte getType()
```

إرجاع نوع تعبئة الخلفية. قراءة/كتابة [BackgroundType](../../com.aspose.slides/backgroundtype).

**الإرجاع:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

إرجاع نوع تعبئة الخلفية. قراءة/كتابة [BackgroundType](../../com.aspose.slides/backgroundtype).

**المعلمات:**
| المعاملة | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

إرجاع كائن FillFormat لتعبئة BackgroundType.OwnBackground. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getEffectFormat() {#getEffectFormat--}
```
public final IEffectFormat getEffectFormat()
```

إرجاع كائن EffectFormat لتعبئة BackgroundType.OwnBackground. قراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)

### getStyleColor() {#getStyleColor--}
```
public final IColorFormat getStyleColor()
```

إرجاع كائن ColorFormat لتعبئة BackgroundType.Themed. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getStyleIndex() {#getStyleIndex--}
```
public final int getStyleIndex()
```

إرجاع فهرس تعبئة BackgroundType.Themed في مجموعة سمة الخلفية. 0 يعني لا تعبئة. 1..999 - فهرس. قراءة/كتابة int.

**الإرجاع:**
int

### setStyleIndex(int value) {#setStyleIndex-int-}
```
public final void setStyleIndex(int value)
```

إرجاع فهرس تعبئة BackgroundType.Themed في مجموعة سمة الخلفية. 0 يعني لا تعبئة. 1..999 - فهرس. قراءة/كتابة int.

**المعلمات:**
| المعاملة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IBackgroundEffectiveData getEffective()
```

الحصول على بيانات الخلفية الفعّالة مع تطبيق الوراثة.

--------------------

> ```
> This example demonstrates getting effective background properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IBackgroundEffectiveData effectiveBackground = pres.getSlides().get_Item(0).getBackground().getEffective();
>  	System.out.println("Background fill type: " + effectiveBackground.getFillFormat().getFillType());
>  	System.out.println("Any effects applied: " + !effectiveBackground.getEffectFormat().isNoEffects());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**الإرجاع:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. قراءة فقط long.

**الإرجاع:**
long

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

إرجاع كائن Parent_Immediate. قراءة فقط IDOMObject.

**الإرجاع:**
com.aspose.slides.IDOMObject

### getSlide() {#getSlide--}
```
public final BaseSlide getSlide()
```

إرجاع الشريحة الأصلية لشكل. قراءة فقط [IBaseSlide](../../com.aspose.slides/ibaseslide).

**الإرجاع:**
[BaseSlide](../../com.aspose.slides/baseslide)

### getPresentation() {#getPresentation--}
```
public final Presentation getPresentation()
```

إرجاع العرض التقديمي الأصلي لشريحة. قراءة فقط [IPresentation](../../com.aspose.slides/ipresentation).

**الإرجاع:**
[Presentation](../../com.aspose.slides/presentation)