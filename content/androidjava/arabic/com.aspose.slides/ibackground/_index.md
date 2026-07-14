---
title: IBackground
second_title: Aspose.Slides لنظام Android عبر مرجع API Java
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
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [getType()](#getType--) | ترجع نوع تعبئة الخلفية. |
| [setType(byte value)](#setType-byte-) | ترجع نوع تعبئة الخلفية. |
| [getFillFormat()](#getFillFormat--) | ترجع FillFormat لتعبئة BackgroundType.OwnBackground. |
| [getEffectFormat()](#getEffectFormat--) | ترجع EffectFormat لتعبئة BackgroundType.OwnBackground. |
| [getStyleColor()](#getStyleColor--) | ترجع ColorFormat لتعبئة BackgroundType.Themed. |
| [getStyleIndex()](#getStyleIndex--) | ترجع فهرس تعبئة BackgroundType.Themed في مجموعة سمات الخلفية. |
| [setStyleIndex(int value)](#setStyleIndex-int-) | ترجع فهرس تعبئة BackgroundType.Themed في مجموعة سمات الخلفية. |
| [getEffective()](#getEffective--) | يحصل على بيانات الخلفية الفعالة مع تطبيق الوراثة. |
### getType() {#getType--}
```
public abstract byte getType()
```

ترجع نوع تعبئة الخلفية. قراءة/كتابة [BackgroundType](../../com.aspose.slides/backgroundtype).

**الإرجاع:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

ترجع نوع تعبئة الخلفية. قراءة/كتابة [BackgroundType](../../com.aspose.slides/backgroundtype).

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

ترجع FillFormat لتعبئة BackgroundType.OwnBackground. للقراءة فقط [IFillFormat](../../com.aspose.slides/ifillformat).

**الإرجاع:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getEffectFormat() {#getEffectFormat--}
```
public abstract IEffectFormat getEffectFormat()
```

ترجع EffectFormat لتعبئة BackgroundType.OwnBackground. للقراءة فقط [IEffectFormat](../../com.aspose.slides/ieffectformat).

**الإرجاع:**
[IEffectFormat](../../com.aspose.slides/ieffectformat)
### getStyleColor() {#getStyleColor--}
```
public abstract IColorFormat getStyleColor()
```

ترجع ColorFormat لتعبئة BackgroundType.Themed. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getStyleIndex() {#getStyleIndex--}
```
public abstract int getStyleIndex()
```

ترجع فهرس تعبئة BackgroundType.Themed في مجموعة سمات الخلفية. 0 يعني لا تعبئة. 1..999 - فهرس. قراءة/كتابة int.

**الإرجاع:**
int
### setStyleIndex(int value) {#setStyleIndex-int-}
```
public abstract void setStyleIndex(int value)
```

ترجع فهرس تعبئة BackgroundType.Themed في مجموعة سمات الخلفية. 0 يعني لا تعبئة. 1..999 - فهرس. قراءة/كتابة int.

**المُعاملات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IBackgroundEffectiveData getEffective()
```

يحصل على بيانات الخلفية الفعالة مع تطبيق الوراثة.

**الإرجاع:**
[IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata) - A [IBackgroundEffectiveData](../../com.aspose.slides/ibackgroundeffectivedata).