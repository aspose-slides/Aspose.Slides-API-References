---
title: ISummaryZoomSection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: एक Summary Zoom फ्रेम में Summary Zoom Section वस्तु का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isummaryzoomsection/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

एक Summary Zoom फ्रेम में Summary Zoom Section वस्तु का प्रतिनिधित्व करता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom Section वस्तु का पाठ शीर्षक लौटाता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom Section वस्तु का पाठ शीर्षक लौटाता है। |
| [getDescription()](#getDescription--) | Summary Zoom Section वस्तु का पाठ विवरण लौटाता है। |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom Section वस्तु का पाठ विवरण लौटाता है। |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```


Summary Zoom Section वस्तु का पाठ शीर्षक लौटाता है।

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
public abstract void setTitle(String value)
```


Summary Zoom Section वस्तु का पाठ शीर्षक लौटाता है।

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setTitle("Title");
>  ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |

### getDescription() {#getDescription--}
```
public abstract String getDescription()
```


Summary Zoom Section वस्तु का पाठ विवरण लौटाता है।

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
public abstract void setDescription(String value)
```


Summary Zoom Section वस्तु का पाठ विवरण लौटाता है।

--------------------

> ```
> Example:
>  
>  ISummaryZoomSection zoomSection = zoomFrame.getSummaryZoomCollection().get_Item(1);
>  zoomSection.setDescription("Description");
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |