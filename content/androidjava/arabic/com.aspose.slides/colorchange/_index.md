---
title: ColorChange
second_title: Aspose.Slides للAndroid عبر مرجع API لجافا
description: يمثل تأثير تغيير اللون.
type: docs
url: /ar/com.aspose.slides/colorchange/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**All Implemented Interfaces:**  
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect  
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

يمثّل تأثير تغيير اللون. يتم استبدال كائنات FromColor بكائنات ToColor.
## Methods

| Method | Description |
| --- | --- |
| [getFromColor()](#getFromColor--) | اللون الذي سيتم استبداله. |
| [getToColor()](#getToColor--) | اللون الذي سيستبدل. |
| [getEffective()](#getEffective--) | يحصل على بيانات تأثير تغيير اللون الفعّالة مع تطبيق الوراثة. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | يحدد ما إذا كان [ColorChange](../../com.aspose.slides/colorchange) المحدد يساوي [ColorChange](../../com.aspose.slides/colorchange) الحالي. |
| [hashCode()](#hashCode--) | يعمل كدالة تجزئة لنوع معين. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

اللون الذي سيتم استبداله. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

اللون الذي سيستبدل. للقراءة فقط [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

يحصل على بيانات تأثير تغيير اللون الفعّالة مع تطبيق الوراثة.

**Returns:**  
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - A [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
### getVersion() {#getVersion--}
```
public long getVersion()
```

الإصدار. طويل للقراءة فقط.

**Returns:**  
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

يحدد ما إذا كان [ColorChange](../../com.aspose.slides/colorchange) المحدد يساوي [ColorChange](../../com.aspose.slides/colorchange) الحالي.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | الـ [ColorChange](../../com.aspose.slides/colorchange) للمقارنة. |

**Returns:**  
boolean - true إذا كانت الكائنات متساوية؛ otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

يعمل كدالة تجزئة لنوع معين.

**Returns:**  
int - رمز تجزئة للكائن الحالي.