---
title: IInk
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/iink/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IInk extends IGraphicalObject
```

एक स्लाइड पर इंक ऑब्जेक्ट का प्रतिनिधित्व करता है।

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTraces()](#getTraces--) | IInk तत्व [IInkTrace](../../com.aspose.slides/iinktrace) में मौजूद सभी ट्रेस प्राप्त करता है। |
### getTraces() {#getTraces--}
```
public abstract IInkTrace[] getTraces()
```

IInk तत्व [IInkTrace](../../com.aspose.slides/iinktrace) में मौजूद सभी ट्रेस प्राप्त करता है। केवल-पढ़ने योग्य।

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

**वापसी:**
com.aspose.slides.IInkTrace[]