---
title: ISummaryZoomSection
second_title: Aspose.Slides for Java API संदर्भ
description: Summary Zoom फ्रेम में Summary Zoom सेक्शन ऑब्जेक्ट का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/isummaryzoomsection/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe)
```
public interface ISummaryZoomSection extends ISectionZoomFrame
```

Summary Zoom फ्रेम में Summary Zoom सेक्शन ऑब्जेक्ट का प्रतिनिधित्व करता है।
## विधियां

| मेथड | विवरण |
| --- | --- |
| [getTitle()](#getTitle--) | Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है। |
| [setTitle(String value)](#setTitle-java.lang.String-) | Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है। |
| [getDescription()](#getDescription--) | Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है। |
| [setDescription(String value)](#setDescription-java.lang.String-) | Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है। |
### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है।

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

Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट शीर्षक लौटाता है।

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

Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है।

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

Summary Zoom सेक्शन ऑब्जेक्ट का टेक्स्ट विवरण लौटाता है।

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