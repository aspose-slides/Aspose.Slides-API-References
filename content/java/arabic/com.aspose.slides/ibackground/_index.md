---
title: IBackground
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة جافا
description: يمثل خلفية شريحة.
type: docs
url: /ar/com.aspose.slides/ibackground/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), [com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IBackground extends ISlideComponent, IFillParamSource
```

يمثل خلفية شريحة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | إرجاع نوع تعبئة الخلفية. |
| [setType(byte value)](#setType-byte-) | إرجاع نوع تعبئة الخلفية. |
| [getFillFormat()](#getFillFormat--) | إرجاع FillFormat لتعبئة BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | إرجاع EffectFormat لتعبئة BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | إرجاع ColorFormat لتعبئة BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | إرجاع الفهرس لتعبئة BackgroundType.Themed في مجموعة سمة الخلفية. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | إرجاع الفهرس لتعبئة BackgroundType.Themed في مجموعة سمة الخلفية. |
| [getEffective()](#getEffective--) | الحصول على بيانات الخلفية الفعالة مع تطبيق الوراثة. |
### getType() {#getType--}
```
public abstract byte getType()
```


إرجاع نوع تعبئة الخلفية. قراءة/كتابة [BackgroundType](../../com.aspose.slides/backgroundtype).

**الإرجاع:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


إرجاع نوع تعبئة الخلفية. قراءة/كتابة [BackgroundType](../../com.aspose.slides/backgroundtype).

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


إرجاع FillFormat لتعبئة BackgroundType.OwnBackground. قراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```


إرجاع EffectFormat لتعبئة BackgroundType.OwnBackground. قراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```


إرجاع ColorFormat لتعبئة BackgroundType.Themed. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```


إرجاع الفهرس لتعبئة BackgroundType.Themed في مجموعة سمة الخلفية. 0 يعني لا تعبئة. 1..999 - الفهرس. قراءة/كتابة int.

**الإرجاع:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```


إرجاع الفهرس لتعبئة BackgroundType.Themed في مجموعة سمة الخلفية. 0 يعني لا تعبئة. 1..999 - الفهرس. قراءة/كتابة int.

**المعاملات:**
| معامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```


الحصول على بيانات الخلفية الفعالة مع تطبيق الوراثة.

**الإرجاع:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).