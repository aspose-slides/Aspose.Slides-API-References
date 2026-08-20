---
title: IDrawingGuide
second_title: Aspose.Slides لـ Java مرجع API
description: يمثل دليل رسم قابل للتعديل.
type: docs
url: /ar/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

يمثل دليل رسم قابل للتعديل.
## الطرق

| Method | Description |
| --- | --- |
| [getOrientation()](#getOrientation--) | إرجاع أو تعيين اتجاه دليل الرسم. |
| [setOrientation(byte value)](#setOrientation-byte-) | إرجاع أو تعيين اتجاه دليل الرسم. |
| [getPosition()](#getPosition--) | إرجاع أو تعيين موضع دليل الرسم بالنقاط من الزاوية العلوية اليسرى للشريحة. |
| [setPosition(float value)](#setPosition-float-) | إرجاع أو تعيين موضع دليل الرسم بالنقاط من الزاوية العلوية اليسرى للشريحة. |
| [getColor()](#getColor--) | إرجاع أو تعيين لون دليل الرسم. |
| [setColor(Color value)](#setColor-java.awt.Color-) | إرجاع أو تعيين لون دليل الرسم. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```

إرجاع أو تعيين اتجاه دليل الرسم. قراءة/كتابة [Orientation](../../com.aspose.slides/orientation).

**الإرجاع:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```

إرجاع أو تعيين اتجاه دليل الرسم. قراءة/كتابة [Orientation](../../com.aspose.slides/orientation).

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

إرجاع أو تعيين موضع دليل الرسم بالنقاط من الزاوية العلوية اليسرى للشريحة. قراءة/كتابة float.

--------------------

النطاق النموذجي للقيمة هو من الصفر إلى ارتفاع الشريحة للدليل الأفقي ومن الصفر إلى عرض الشريحة للدليل العمودي.

**الإرجاع:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

إرجاع أو تعيين موضع دليل الرسم بالنقاط من الزاوية العلوية اليسرى للشريحة. قراءة/كتابة float.

--------------------

النطاق النموذجي للقيمة هو من الصفر إلى ارتفاع الشريحة للدليل الأفقي ومن الصفر إلى عرض الشريحة للدليل العمودي.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

إرجاع أو تعيين لون دليل الرسم. قراءة/كتابة java.awt.Color.

**الإرجاع:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

إرجاع أو تعيين لون دليل الرسم. قراءة/كتابة java.awt.Color.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |