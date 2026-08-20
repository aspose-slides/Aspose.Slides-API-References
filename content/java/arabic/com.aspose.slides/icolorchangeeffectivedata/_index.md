---
title: IColorChangeEffectiveData
second_title: مرجع واجهة برمجة تطبيقات Aspose.Slides للغة Java
description: كائن غير قابل للتعديل يمثل تأثير تغيير اللون.
type: docs
url: /ar/com.aspose.slides/icolorchangeeffectivedata/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IColorChangeEffectiveData extends IEffectEffectiveData
```

كائن غير قابل للتعديل يمثل تأثير تغيير اللون. يتم استبدال كائنات FromColor بكائنات ToColor.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFromColor()](#getFromColor--) | اللون الذي سيتم استبداله. |
| [getToColor()](#getToColor--) | اللون الذي سيستبدل. |
| [getUseAlpha()](#getUseAlpha--) | تُرجع قيمة منطقية تحدد ما إذا كان يجب استخدام مكون ألفا. |
### getFromColor() {#getFromColor--}
```
public abstract Color getFromColor()
```


اللون الذي سيتم استبداله. للقراءة فقط java.awt.Color.

**الإرجاع:**  
java.awt.Color
### getToColor() {#getToColor--}
```
public abstract Color getToColor()
```


اللون الذي سيستبدل. للقراءة فقط java.awt.Color.

**الإرجاع:**  
java.awt.Color
### getUseAlpha() {#getUseAlpha--}
```
public abstract boolean getUseAlpha()
```


تُرجع قيمة منطقية تحدد ما إذا كان يجب استخدام مكون ألفا. للقراءة فقط boolean.

**الإرجاع:**  
boolean