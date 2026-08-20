---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides for Java API संदर्भ
description: Summary Zoom Section वस्तुओं का एक संग्रह दर्शाता है।
type: docs
url: /hi/com.aspose.slides/summaryzoomsectioncollection/
---
**विरासत:**
java.lang.Object, com.aspose.slides.DomObject

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISummaryZoomSectionCollection](../../com.aspose.slides/isummaryzoomsectioncollection)
```
public final class SummaryZoomSectionCollection extends DomObject<SummaryZoomFrame> implements ISummaryZoomSectionCollection
```

Summary Zoom Section वस्तुओं का एक संग्रह दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट सूचकांक पर तत्व प्राप्त करता है। |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | नया Summary Zoom Section वस्तु बनाता है और उसे संग्रह में जोड़ता है। |
| [size()](#size--) | संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | निर्दिष्ट SummaryZoomSection वस्तु का सूचकांक लौटाता है। |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | संग्रह से Summary Zoom Section वस्तु को हटाता है। |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | दिए गए सेक्शन के लिए Summary Zoom Section तत्व लौटाता है। |
| [clear()](#clear--) | संग्रह से सभी SummaryZoomSection वस्तुओं को हटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरे संग्रह को निर्दिष्ट सरणी में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समन्वित (थ्रेड-सुरक्षित) है या नहीं। |
| [getSyncRoot()](#getSyncRoot--) | एक समन्वयन मूल लौटाता है। |
| [iterator()](#iterator--) | एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए एक java इटरटर लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
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

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**रिटर्न्स:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

नया Summary Zoom Section वस्तु बनाता है और उसे संग्रह में जोड़ता है।

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

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | नए Summary Zoom Section तत्व के लिए सेक्शन [ISection](../../com.aspose.slides/isection) |

यदि इस सेक्शन के लिए तत्व पहले से संग्रह में मौजूद है, तो मौजूदा तत्व लौटाया जाता है।

**रिटर्न्स:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - जोड़े गए [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) तत्व
### size() {#size--}
```
public final int size()
```

संग्रह में वास्तविक रूप से मौजूद तत्वों की संख्या प्राप्त करता है। केवल-पढ़ने योग्य int।

**रिटर्न्स:**
int
### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

निर्दिष्ट SummaryZoomSection वस्तु का सूचकांक लौटाता है।

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

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | SummaryZoomSection वस्तु को खोजने के लिए [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)। |

**रिटर्न्स:**
int - SummaryZoomSection वस्तु का सूचकांक या -1 यदि SummaryZoomSection वस्तु इस संग्रह से नहीं है।
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
```

संग्रह से Summary Zoom Section वस्तु को हटाता है।

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

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | उस सेक्शन के लिए जिसके लिए Summary Zoom Section तत्व हटाया जाना है [ISection](../../com.aspose.slides/isection)। |

### getSummarySection(ISection section) {#getSummarySection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection getSummarySection(ISection section)
```

दिए गए सेक्शन के लिए Summary Zoom Section तत्व लौटाता है।

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

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | खोजने के लिए सेक्शन [ISection](../../com.aspose.slides/isection) |

**रिटर्न्स:**
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) - [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) या null यदि संग्रह में उस सेक्शन के लिए तत्व नहीं है।
### clear() {#clear--}
```
public final void clear()
```

संग्रह से सभी SummaryZoomSection वस्तुओं को हटाता है।

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

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

पूरे संग्रह को निर्दिष्ट सरणी में कॉपी करता है।

**परामितर:**
| परामितर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्षित सरणी |
| index | int | लक्षित सरणी में सूचकांक। |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

एक मान लौटाता है जो दर्शाता है कि संग्रह तक पहुँच समन्वित (थ्रेड-सुरक्षित) है या नहीं। केवल-पढ़ने योग्य boolean।

**रिटर्न्स:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

एक समन्वयन मूल लौटाता है। केवल-पढ़ने योग्य Object।

**रिटर्न्स:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

एक एन्यूमरेटर लौटाता है जो संग्रह के माध्यम से इटरिट करता है।

**रिटर्न्स:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - एक IGenericEnumerator जो संग्रह के माध्यम से इटरिट करने के लिए उपयोग किया जा सकता है।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

पूरे संग्रह के लिए एक java इटरटर लौटाता है।

**रिटर्न्स:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - पूरे संग्रह के लिए एक java.util.Iterator।