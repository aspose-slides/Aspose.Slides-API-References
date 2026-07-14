---
title: ISummaryZoomFrame
second_title: Aspose.Slides Android के लिए Java API संदर्भ के माध्यम से
description: एक स्लाइड में Summary Zoom फ्रेम का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isummaryzoomframe/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISummaryZoomFrame extends IGraphicalObject
```

एक स्लाइड में Summary Zoom फ्रेम का प्रतिनिधित्व करता है।
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [getLayout()](#getLayout--) | फ़्रेम में Summary Zoom सेक्शन का लेआउट प्राप्त करता है। |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) को Summary Zoom Frame ऑब्जेक्ट के लिए प्राप्त करता है। |
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

फ़्रेम में Summary Zoom सेक्शन का लेआउट प्राप्त करता है। डिफ़ॉल्ट मान GridLayout है।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**  
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public abstract ISummaryZoomSectionCollection getSummaryZoomCollection()
```

[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) को Summary Zoom Frame ऑब्जेक्ट के लिए प्राप्त करता है।

--------------------

> ```
> उदाहरण दर्शाता है कि कैसे इंडेक्स से Summary Zoom Section तत्व प्राप्त किया जाए:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**वापसी:**  
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)