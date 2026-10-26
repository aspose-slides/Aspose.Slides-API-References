---
title: InkBrush
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक inkBrush ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/inkbrush/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IInkBrush](../../com.aspose.slides/iinkbrush)
```
public class InkBrush implements IInkBrush
```

एक inkBrush ऑब्जेक्ट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getColor()](#getColor--) | लाइन के लिए ब्रश रंग प्राप्त करता है या सेट करता है। |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | लाइन के लिए ब्रश रंग प्राप्त करता है या सेट करता है। |
| [getSize()](#getSize--) | लाइन के बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है। |
| [setSize(SizeF value)](#setSize-com.aspose.slides.android.SizeF-) | लाइन के बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है। |
| [getInkEffect()](#getInkEffect--) | इंक इफ़ेक्ट प्रकार (जैसे Galaxy, Gold, Silver) प्राप्त करता है जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। |
### getColor() {#getColor--}
```
public final Integer getColor()
```


लाइन के लिए ब्रश रंग प्राप्त करता है या सेट करता है।

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

**वापसी:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```


लाइन के लिए ब्रश रंग प्राप्त करता है या सेट करता है।

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
public final SizeF getSize()
```


लाइन के बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है।

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

**वापसी:**
[SizeF](../../com.aspose.slides.android/sizef)
### setSize(SizeF value) {#setSize-com.aspose.slides.android.SizeF-}
```
public final void setSize(SizeF value)
```


लाइन के बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है।

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
public final int getInkEffect()
```


इंक इफ़ेक्ट प्रकार (जैसे Galaxy, Gold, Silver) प्राप्त करता है जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। मान ब्रश प्रॉपर्टी "inkEffects" से पार्स किया जाता है। यदि कोई मान्यता प्राप्त प्रभाव निर्दिष्ट नहीं किया गया है, तो [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) वापस किया जाता है।

**वापसी:**
int