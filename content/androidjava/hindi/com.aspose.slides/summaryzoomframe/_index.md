---
title: SummaryZoomFrame
second_title: Aspose.Slides for Android के माध्यम से Java API संदर्भ
description: एक स्लाइड में Summary Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/summaryzoomframe/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe)
```
public class SummaryZoomFrame extends GraphicalObject implements ISummaryZoomFrame
```

एक स्लाइड में Summary Zoom ऑब्जेक्ट का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getLayout()](#getLayout--) | Summary Zoom Sections का layout फ्रेम में प्राप्त करता है। |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) को Summary Zoom Frame ऑब्जेक्ट के लिए प्राप्त करता है। |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


Summary Zoom Sections का layout फ्रेम में प्राप्त करता है। डिफ़ॉल्ट मूल्य GridLayout है।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      int layout = zoomFrame.getLayout();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न मान:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) को Summary Zoom Frame ऑब्जेक्ट के लिए प्राप्त करता है।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>      ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न मान:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)