---
title: Ink
second_title: Aspose.Slides for Java API Reference
description: Represents an ink object on a slide.
type: docs
url: /com.aspose.slides/ink/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**All Implemented Interfaces:**
[com.aspose.slides.IInk](../../com.aspose.slides/iink)
```
public class Ink extends GraphicalObject implements IInk
```

Represents an ink object on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getTraces()](#getTraces--) | Gets all traces containing in the IInk element [IInkTrace](../../com.aspose.slides/iinktrace). |
| [getInkEffectImages()](#getInkEffectImages--) | Gets the collection of custom images used to simulate visual effects for ink brushes. |
### getTraces() {#getTraces--}
```
public final IInkTrace[] getTraces()
```


Gets all traces containing in the IInk element [IInkTrace](../../com.aspose.slides/iinktrace). Read-only.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IInk ink = (IInk)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IInkTrace[] traces = ink.getTraces();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Returns:**
com.aspose.slides.IInkTrace[]
### getInkEffectImages() {#getInkEffectImages--}
```
public static System.Collections.Generic.IGenericDictionary<Integer,IImage> getInkEffectImages()
```


Gets the collection of custom images used to simulate visual effects for ink brushes. These images are used when rendering ink with specific [InkEffectType](../../com.aspose.slides/inkeffecttype) values, such as Galaxy, Rainbow, etc. By providing your own images, you can control how each ink effect appears.

--------------------

> ```
> IImage image = Images.fromFile("image.png");
>  ink.getInkEffectImages().addItem(InkEffectType.Galaxy, image);
> ```

--------------------

This property allows replacing the default ink effect textures with user-defined ones, which is particularly useful when default assets are restricted by licensing or unavailable at runtime. Each entry in the dictionary must associate an [InkEffectType](../../com.aspose.slides/inkeffecttype) value with a corresponding [IImage](../../com.aspose.slides/iimage) object (e.g., Bitmap, or an Aspose image interface).

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericDictionary<java.lang.Integer,com.aspose.slides.IImage>
