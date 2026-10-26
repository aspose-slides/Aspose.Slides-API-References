---
title: ISummaryZoomSectionCollection
second_title: Aspose.Slides एंड्रॉइड के लिए जावा एपीआई रेफ़रेंस
description: Summary Zoom Section ऑब्जेक्ट्स का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/isummaryzoomsectioncollection/
---
**सभी लागू इंटरफ़ेस:**
com.aspose.slides.IGenericCollection
```
public interface ISummaryZoomSectionCollection extends IGenericCollection<ISummaryZoomSection>
```

Summary Zoom Section ऑब्जेक्ट्स का एक संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | नया Summary Zoom Section ऑब्जेक्ट बनाता है और उसे संग्रह में जोड़ता है |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | दिए गए अनुभाग के लिए Summary Zoom Section तत्व लौटाता है। |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | संग्रह से Summary Zoom Section ऑब्जेक्ट हटाता है। |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | निर्दिष्ट SummaryZoomSection ऑब्जेक्ट का सूचकांक लौटाता है। |
| [clear()](#clear--) | संग्रह से सभी SummaryZoomSection ऑब्जेक्ट्स हटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public abstract ISummaryZoomSection get_Item(int index)
```

निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। केवल-पढ़ने योग्य [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection zoomSection = collection.get_Item(1);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection addSummaryZoomSection(ISection section)
```

नया Summary Zoom Section ऑब्जेक्ट बनाता है और उसे संग्रह में जोड़ता है

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection newZoomSection = collection.addSummaryZoomSection(pres.getSections().get_Item(3));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | नया Summary Zoom Section तत्व के लिए सेक्शन [ISection](../../com.aspose.slides/isection)

यदि इस अनुभाग के लिए संग्रह में पहले से कोई तत्व मौजूद है, तो मौजूदा तत्व वापस किया जाता है। |

**रिटर्न:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - जोड़ा गया [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) तत्व
### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public abstract ISummaryZoomSection getSummarySection(ISection section)
```

दिए गए अनुभाग के लिए Summary Zoom Section तत्व लौटाता है।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | खोजने के लिए सेक्शन [ISection](../../com.aspose.slides/isection) |

**रिटर्न:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) या null यदि संग्रह में अनुभाग के लिए तत्व नहीं है।

### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public abstract void removeSummaryZoomSection(ISection section)
```

संग्रह से Summary Zoom Section ऑब्जेक्ट हटाता है।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.removeSummaryZoomSection(pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | वह सेक्शन जिसके लिए Summary Zoom Section तत्व हटाना है [ISection](../../com.aspose.slides/isection)।

### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public abstract int indexOf(ISummaryZoomSection summaryZoomSection)
```

निर्दिष्ट SummaryZoomSection ऑब्जेक्ट का सूचकांक लौटाता है।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       ISummaryZoomSection selectedObject = collection.getSummarySection(pres.getSections().get_Item(2));
>       int idx = collection.indexOf(selectedObject);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | खोजने के लिए SummaryZoomSection ऑब्जेक्ट [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)।

**रिटर्न:**
int - SummaryZoomSection ऑब्जेक्ट का सूचकांक या -1 यदि SummaryZoomSection ऑब्जेक्ट इस संग्रह का नहीं है।

### clear() {#clear--}
```
public abstract void clear()
```

संग्रह से सभी SummaryZoomSection ऑब्जेक्ट्स हटाता है।

--------------------

> ```
> The example demonstrates getting Summary Zoom Section element by index:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>       ISummaryZoomFrame zoomFrame = (ISummaryZoomFrame)pres.getSlides().get_Item(1).getShapes().get_Item(0);
>       ISummaryZoomSectionCollection collection = zoomFrame.getSummaryZoomCollection();
>       collection.clear();
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```