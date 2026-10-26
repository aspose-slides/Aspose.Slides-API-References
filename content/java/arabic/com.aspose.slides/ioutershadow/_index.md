---
title: IOuterShadow
second_title: مرجع API لـ Aspose.Slides للغة جافا
description: يمثل تأثير الظل الخارجي.
type: docs
url: /ar/com.aspose.slides/ioutershadow/
---
**All Implemented Interfaces:**  
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject  
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

يمثل تأثير الظل الخارجي.  
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | نصف قطر الضبابية، بالنقاط. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | نصف قطر الضبابية، بالنقاط. |
| [getDirection()](#getDirection--) | اتجاه الظل، بالدرجات. |
| [setDirection(float value)](#setDirection-float-) | اتجاه الظل، بالدرجات. |
| [getDistance()](#getDistance--) | مسافة الظل من الكائن، بالنقاط. |
| [setDistance(double value)](#setDistance-double-) | مسافة الظل من الكائن، بالنقاط. |
| [getShadowColor()](#getShadowColor--) | لون الظل. |
| [getRectangleAlign()](#getRectangleAlign--) | محاذاة المستطيل. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | محاذاة المستطيل. |
| [getSkewHorizontal()](#getSkewHorizontal--) | زاوية الانحراف الأفقي، بالدرجات. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | زاوية الانحراف الأفقي، بالدرجات. |
| [getSkewVertical()](#getSkewVertical--) | زاوية الانحراف الرأسي، بالدرجات. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | زاوية الانحراف الرأسي، بالدرجات. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | يحدد ما إذا كان الظل يدور مع الشكل. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | يحدد ما إذا كان الظل يدور مع الشكل. |
| [getScaleHorizontal()](#getScaleHorizontal--) | عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. |
| [getScaleVertical()](#getScaleVertical--) | عامل التحجيم الرأسي، كنسبة مئوية من الحجم الأصلي. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | عامل التحجيم الرأسي، كنسبة مئوية من الحجم الأصلي. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```

نصف قطر الضبابية، بالنقاط. القيمة الافتراضية - 0 نقطة. قراءة/كتابة double.

**الإرجاع:**  
double  

### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```

نصف قطر الضبابية، بالنقاط. القيمة الافتراضية - 0 نقطة. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```

اتجاه الظل، بالدرجات. القيمة الافتراضية - 0 � (من اليسار إلى اليمين). قراءة/كتابة float.

**الإرجاع:**  
float  

### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```

اتجاه الظل، بالدرجات. القيمة الافتراضية - 0 � (من اليسار إلى اليمين). قراءة/كتابة float.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```

مسافة الظل من الكائن، بالنقاط. القيمة الافتراضية - 0 نقطة. قراءة/كتابة double.

**الإرجاع:**  
double  

### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```

مسافة الظل من الكائن، بالنقاط. القيمة الافتراضية - 0 نقطة. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```

لون الظل. القيمة الافتراضية - أسود تلقائي (يعتمد على النمط). قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**  
[IColorFormat](../../com.aspose.slides/icolorformat)  

### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```

محاذاة المستطيل. القيمة الافتراضية - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). قراءة/كتابة [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**الإرجاع:**  
byte  

### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```

محاذاة المستطيل. القيمة الافتراضية - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). قراءة/كتابة [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```

زاوية الانحراف الأفقي، بالدرجات. القيمة الافتراضية - 0 �. قراءة/كتابة double.

**الإرجاع:**  
double  

### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```

زاوية الانحراف الأفقي، بالدرجات. القيمة الافتراضية - 0 �. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```

زاوية الانحراف الرأسي، بالدرجات. القيمة الافتراضية - 0 �. قراءة/كتابة double.

**الإرجاع:**  
double  

### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```

زاوية الانحراف الرأسي، بالدرجات. القيمة الافتراضية - 0 �. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```

يحدد ما إذا كان الظل يدور مع الشكل. القيمة الافتراضية - true. قراءة/كتابة boolean.

**الإرجاع:**  
boolean  

### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```

يحدد ما إذا كان الظل يدور مع الشكل. القيمة الافتراضية - true. قراءة/كتابة boolean.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```

عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. التحجيم السلبي يسبب انعكاس. القيمة الافتراضية - 100 %. قراءة/كتابة double.

**الإرجاع:**  
double  

### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```

عامل التحجيم الأفقي، كنسبة مئوية من الحجم الأصلي. التحجيم السلبي يسبب انعكاس. القيمة الافتراضية - 100 %. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```

عامل التحجيم الرأسي، كنسبة مئوية من الحجم الأصلي. التحجيم السلبي يسبب انعكاس. القيمة الافتراضية - 100 %. قراءة/كتابة double.

**الإرجاع:**  
double  

### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```

عامل التحجيم الرأسي، كنسبة مئوية من الحجم الأصلي. التحجيم السلبي يسبب انعكاس. القيمة الافتراضية - 100 %. قراءة/كتابة double.

**المعلمات:**  
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | double |  |