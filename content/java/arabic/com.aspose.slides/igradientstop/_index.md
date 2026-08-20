---
title: IGradientStop
second_title: Aspose.Slides for Java مرجع API
description: يمثل تنسيق تدرج.
type: docs
url: /ar/com.aspose.slides/igradientstop/
---```
public interface IGradientStop
```

يمثل تنسيق تدرج.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getPosition()](#getPosition--) | إرجاع أو تعيين موضع (0..1) لنقطة إيقاف التدرج. |
| [setPosition(float value)](#setPosition-float-) | إرجاع أو تعيين موضع (0..1) لنقطة إيقاف التدرج. |
| [getColor()](#getColor--) | إرجاع لون نقطة إيقاف التدرج. |
### getPosition() {#getPosition--}
```
public abstract float getPosition()
```

إرجاع أو تعيين موضع (0..1) لنقطة إيقاف التدرج. قراءة/كتابة float.

**الإرجاع:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```

إرجاع أو تعيين موضع (0..1) لنقطة إيقاف التدرج. قراءة/كتابة float.

**المعلمات:**
| المتغير | النوع | الوصف |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

إرجاع لون نقطة إيقاف التدرج. قراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**الإرجاع:**
[IColorFormat](../../com.aspose.slides/icolorformat)