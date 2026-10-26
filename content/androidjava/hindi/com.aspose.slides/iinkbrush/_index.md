---
title: IInkBrush
second_title: Aspose.Slides for Android via Java API Reference
description: ट्रेस ब्रश का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

ट्रेस ब्रश का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColor()](#getColor--) | रेखा के लिए ब्रश का रंग प्राप्त करता है या सेट करता है। |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | रेखा के लिए ब्रश का रंग प्राप्त करता है या सेट करता है। |
| [getSize()](#getSize--) | रेखा के लिए ब्रश का आकार पॉइंट में प्राप्त करता है या सेट करता है। |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | रेखा के लिए ब्रश का आकार पॉइंट में प्राप्त करता है या सेट करता है। |
| [getInkEffect()](#getInkEffect--) | इंक इफ़ेक्ट प्रकार प्राप्त करता है (उदा., Galaxy, Gold, Silver) जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```


रेखा के लिए ब्रश का रंग प्राप्त करता है या सेट करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


रेखा के लिए ब्रश का रंग प्राप्त करता है या सेट करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Color brushColor = brush.getColor();
>      brush.setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getSize() {#getSize--}
```
public abstract SizeF getSize()
```


रेखा के लिए ब्रश का आकार पॉइंट में प्राप्त करता है या सेट करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public abstract void setSize(SizeF value)
```


रेखा के लिए ब्रश का आकार पॉइंट में प्राप्त करता है या सेट करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      SizeF brushSize = brush.getSize();
>      brush.setSize(new com.aspose.slides.android.Size(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.slides.android/sizef) |  |

### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


इंक इफ़ेक्ट प्रकार प्राप्त करता है (उदा., Galaxy, Gold, Silver) जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। मान ब्रश प्रॉपर्टी "inkEffects" से पार्स किया जाता है। यदि कोई मान्य इफ़ेक्ट निर्दिष्ट नहीं है, तो [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) लौटाया जाता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      Ink ink = (Ink) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkBrush brush = ink.getTraces()[0].getBrush();
>      System.out.println("InkEffects = " + brush.getInkEffect());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
int