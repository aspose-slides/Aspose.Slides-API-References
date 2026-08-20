---
title: IInkBrush
second_title: Aspose.Slides for Java API Reference
description: Represents trace brush.
type: docs
url: /hi/com.aspose.slides/iinkbrush/
---```
public interface IInkBrush
```

Represents trace brush.
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getColor()](#getColor--) | एक रेखा के लिए ब्रश रंग प्राप्त करता है या सेट करता है। |
| [setColor(Color value)](#setColor-java.awt.Color-) | एक रेखा के लिए ब्रश रंग प्राप्त करता है या सेट करता है। |
| [getSize()](#getSize--) | एक रेखा के लिए बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है। |
| [setSize(Dimension2D value)](#setSize-java.awt.geom.Dimension2D-) | एक रेखा के लिए बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है। |
| [getInkEffect()](#getInkEffect--) | इंक इफ़ेक्ट प्रकार (उदाहरण: Galaxy, Gold, Silver) प्राप्त करता है, जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। |
### getColor() {#getColor--}
```
public abstract Color getColor()
```


एक रेखा के लिए ब्रश रंग प्राप्त करता है या सेट करता है।

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
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


एक रेखा के लिए ब्रश रंग प्राप्त करता है या सेट करता है।

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
| value | java.awt.Color |  |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```


एक रेखा के लिए बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है।

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

**रिटर्न:** 
java.awt.geom.Dimension2D
### setSize(Dimension2D value) {#setSize-java.awt.geom.Dimension2D-}
```
public abstract void setSize(Dimension2D value)
```


एक रेखा के लिए बिंदुओं में ब्रश आकार प्राप्त करता है या सेट करता है।

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

**पैरामीटर:** 
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.awt.geom.Dimension2D |  |
### getInkEffect() {#getInkEffect--}
```
public abstract int getInkEffect()
```


इंक इफ़ेक्ट प्रकार (उदाहरण: Galaxy, Gold, Silver) प्राप्त करता है, जो इंक स्ट्रोक की दृश्य शैली को परिभाषित करता है। मान "inkEffects" ब्रश प्रॉपर्टी से पार्स किया जाता है। यदि कोई मान्यता प्राप्त प्रभाव निर्दिष्ट नहीं है, [InkEffectType.NotDefined](../../com.aspose.slides/inkeffecttype\#NotDefined) लौटाया जाता है।

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