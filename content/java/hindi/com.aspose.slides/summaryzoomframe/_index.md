---
title: SummaryZoomFrame
second_title: Aspose.Slides के लिए जावा API संदर्भ
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
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getLayout()](#getLayout--) | फ़्रेम में Summary Zoom सेक्शन्स का लेआउट प्राप्त करता है। |
| [getSummaryZoomCollection()](#getSummaryZoomCollection--) | Summary Zoom Frame ऑब्जेक्ट के लिए [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) प्राप्त करता है। |
### getLayout() {#getLayout--}
```
public final int getLayout()
```


फ़्रेम में Summary Zoom सेक्शन्स का लेआउट प्राप्त करता है। डिफ़ॉल्ट मान GridLayout है।

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

**रिटर्न:**
int
### getSummaryZoomCollection() {#getSummaryZoomCollection--}
```
public final ISummaryZoomSectionCollection getSummaryZoomCollection()
```


Summary Zoom Frame ऑब्जेक्ट के लिए [ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection) प्राप्त करता है।

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

**रिटर्न:**
[ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)