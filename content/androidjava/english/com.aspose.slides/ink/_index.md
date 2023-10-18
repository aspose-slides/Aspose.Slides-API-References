---
title: Ink
second_title: Aspose.Slides for Android via Java API Reference
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
