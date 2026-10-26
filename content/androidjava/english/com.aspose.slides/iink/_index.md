---
title: IInk
second_title: Aspose.Slides for Android via Java API Reference
description: Represents an ink object on a slide.
type: docs
url: /com.aspose.slides/iink/
---
**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

Represents an ink object on a slide.
## Methods

| Method | Description |
| --- | --- |
| [getTraces()](#getTraces--) | Gets all traces containing in the IInk element [IInkTrace](../../com.aspose.slides/iinktrace). |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
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
