---
title: InkBrush
second_title: Aspose.Slides के लिए Java API संदर्भ
description: एक inkBrush वस्तु का प्रतिनिधित्व करता है।
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

एक inkBrush वस्तु का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getColor()](#getColor--) | एक लाइन के लिए ब्रश रंग को प्राप्त करता है या सेट करता है। |
| [setColor(Color value)](#setColor-java.awt.Color-) | एक लाइन के लिए ब्रश रंग को प्राप्त करता है या सेट करता है। |
| [getSize()](#getSize--) | एक लाइन के लिए बिंदुओं में ब्रश आकार को प्राप्त करता है या सेट करता है। |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | एक लाइन के लिए बिंदुओं में ब्रश आकार को प्राप्त करता है या सेट करता है। |
| [getInkEffect()](#getInkEffect--) | इंक स्ट्रोक की दृश्य शैली को परिभाषित करने वाले इंक इफ़ेक्ट प्रकार को प्राप्त करता है (जैसे, Galaxy, Gold, Silver)। |

### getColor() {#getColor--}
```
public final Color getColor()
```


एक लाइन के लिए ब्रश रंग को प्राप्त करता है या सेट करता है।

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
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```


एक लाइन के लिए ब्रश रंग को प्राप्त करता है या सेट करता है।

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

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.Color |  |

### getSize() {#getSize--}
```
public final Dimension2D getSize()
```


एक लाइन के लिए बिंदुओं में ब्रश आकार को प्राप्त करता है या सेट करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public final void setSize(Dimension2D value)
```


एक लाइन के लिए बिंदुओं में ब्रश आकार को प्राप्त करता है या सेट करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>      IInkBrush brush = traces[0].getBrush();
>      Dimension2D brushSize = brush.getSize();
>      brush.setSize(new Dimension(5, 10));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**परामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |

### getInkEffect() {#getInkEffect--}
```
public final int getInkEffect()
```


इंक स्ट्रोक की दृश्य शैली को परिभाषित करने वाले इंक इफ़ेक्ट प्रकार को प्राप्त करता है (जैसे, Galaxy, Gold, Silver)। मान को ब्रश प्रॉपर्टी "inkEffects" से पार्स किया जाता है। यदि कोई मान्य प्रभाव निर्दिष्ट नहीं किया गया है, तो [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) लौटाया जाता है।

**वापसी:**
int