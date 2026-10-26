---
title: SummaryZoomSection
second_title: Android के लिए Aspose.Slides, Java API रेफ़रेंस के माध्यम से
description: Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/summaryzoomsection/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject), [com.aspose.slides.ZoomObject](../../com.aspose.slides/zoomobject), [com.aspose.slides.SectionZoomFrame](../../com.aspose.slides/sectionzoomframe)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
```
public class SummaryZoomSection extends SectionZoomFrame implements ISummaryZoomSection
```

Summary Zoom फ्रेम में Summary Zoom Section ऑब्जेक्ट का प्रतिनिधित्व करता है।

## विधियां

| विधि | विवरण |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Section ऑब्जेक्ट के टेक्स्ट शीर्षक को लौटाता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Section ऑब्जेक्ट के टेक्स्ट शीर्षक को लौटाता है। |
| [getDescription()](#getDescription--) | Summary Zoom Section ऑब्जेक्ट के टेक्स्ट विवरण को लौटाता है। |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Section ऑब्जेक्ट के टेक्स्ट विवरण को लौटाता है। |

### getTitle() {#getTitle--}
```
public final String getTitle()
```

Summary Zoom Section ऑब्जेक्ट के टेक्स्ट शीर्षक को लौटाता है।

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**रिटर्न:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```

Summary Zoom Section ऑब्जेक्ट के टेक्स्ट शीर्षक को लौटाता है।

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public final String getDescription()
```

Summary Zoom Section ऑब्जेक्ट के टेक्स्ट विवरण को लौटाता है।

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**रिटर्न:**
java.lang.String

### setDescription(String value) {#setDescription-java.lang.String-}
```
public final void setDescription(String value)
```

Summary Zoom Section ऑब्जेक्ट के टेक्स्ट विवरण को लौटाता है।

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |