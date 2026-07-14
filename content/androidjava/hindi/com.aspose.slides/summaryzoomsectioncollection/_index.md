---
title: SummaryZoomSectionCollection
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: Summary Zoom Section ऑब्जेक्ट्स का संग्रह दर्शाता है।
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

Summary Zoom Section ऑब्जेक्ट्स का संग्रह दर्शाता है।
## विधियां

| विधि | विवरण |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। |
| [addSummaryZoomSection(ISection section)](#addSummaryZoomSection-com.aspose.slides.ISection-) | नया Summary Zoom Section ऑब्जेक्ट बनाता है और संग्रह में जोड़ता है। |
| [size()](#size--) | वास्तव में संग्रह में मौजूद तत्वों की संख्या प्राप्त करता है। |
| [indexOf(ISummaryZoomSection summaryZoomSection)](#indexOf-com.aspose.slides.ISummaryZoomSection-) | निर्दिष्ट SummaryZoomSection ऑब्जेक्ट का अनुक्रमांक लौटाता है। |
| [removeSummaryZoomSection(ISection section)](#removeSummaryZoomSection-com.aspose.slides.ISection-) | संग्रह से Summary Zoom Section ऑब्जेक्ट हटाता है। |
| [getSummarySection(ISection section)](#getSummarySection-com.aspose.slides.ISection-) | दिए गए सेक्शन के लिए Summary Zoom Section तत्व लौटाता है। |
| [clear()](#clear--) | संग्रह से सभी SummaryZoomSection ऑब्जेक्ट हटाता है। |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है। |
| [isSynchronized()](#isSynchronized--) | संकेत करता है कि क्या संग्रह तक पहुंच समकालित (थ्रेड-सुरक्षित) है, इसका मान लौटाता है। |
| [getSyncRoot()](#getSyncRoot--) | समक्रमण मूल (synchronization root) लौटाता है। |
| [iterator()](#iterator--) | संग्रह के माध्यम से पुनरावृत्ति करने वाला इटेरेटर लौटाता है। |
| [iteratorJava()](#iteratorJava--) | पूरे संग्रह के लिए जावा इटेरेटर लौटाता है। |
### get_Item(int index) {#get-Item-int-}
```
public final ISummaryZoomSection get_Item(int index)
```

निर्दिष्ट अनुक्रमांक पर तत्व प्राप्त करता है। केवल- पढ़ने योग्य [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection).

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| index | int |  |

**वापसी:**  
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)
### addSummaryZoomSection(ISection section) {#addSummaryZoomSection-com.aspose.slides.ISection-}
```
public final ISummaryZoomSection addSummaryZoomSection(ISection section)
```

नया Summary Zoom Section ऑब्जेक्ट बनाता है और संग्रह में जोड़ता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | नए Summary Zoom Section तत्व के लिए सेक्शन [ISection](../../com.aspose.slides/isection)

यदि इस सेक्शन के लिए तत्व पहले से ही संग्रह में मौजूद है, तो मौजूदा तत्व लौटाया जाता है। |

**वापसी:**  
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) – जोड़ा गया [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) तत्व
### size() {#size--}
```
public final int size()
```

वास्तव में संग्रह में मौजूद तत्वों की संख्या प्राप्त करता है। केवल- पढ़ने योग्य int।

**वापसी:**  
int
### indexOf(ISummaryZoomSection summaryZoomSection) {#indexOf-com.aspose.slides.ISummaryZoomSection-}
```
public final int indexOf(ISummaryZoomSection summaryZoomSection)
```

निर्दिष्ट SummaryZoomSection ऑब्जेक्ट का अनुक्रमांक लौटाता है।

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| summaryZoomSection | [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) | खोजने के लिए SummaryZoomSection ऑब्जेक्ट [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection)। |

**वापसी:**  
int - SummaryZoomSection ऑब्जेक्ट का अनुक्रमांक या -1 यदि SummaryZoomSection ऑब्जेक्ट इस संग्रह से नहीं है।
### removeSummaryZoomSection(ISection section) {#removeSummaryZoomSection-com.aspose.slides.ISection-}
```
public final void removeSummaryZoomSection(ISection section)
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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | उस सेक्शन के लिए Summary Zoom Section तत्व हटाने हेतु [ISection](../../com.aspose.slides/isection)। |

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

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| section | [ISection](../../com.aspose.slides/isection) | ढूँढ़ने हेतु सेक्शन [ISection](../../com.aspose.slides/isection) |

**वापसी:**  
[ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) – [ISummaryZoomSection](../../com.aspose.slides/isummaryzoomsection) या null यदि संग्रह में सेक्शन के लिए कोई तत्व नहीं है।
### clear() {#clear--}
```
public final void clear()
```

सभी SummaryZoomSection ऑब्जेक्ट को संग्रह से हटाता है।

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

पूरे संग्रह को निर्दिष्ट एरे में कॉपी करता है।

**परामीटर:**  
| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | लक्ष्य एरे |
| index | int | लक्ष्य एरे में अनुक्रमांक। |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

संकेत करता है कि क्या संग्रह तक पहुंच समकालित (थ्रेड-सुरक्षित) है, इसका मान लौटाता है। केवल- पढ़ने योग्य boolean।

**वापसी:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

समक्रमण मूल (synchronization root) लौटाता है। केवल- पढ़ने योग्य Object।

**वापसी:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iterator()
```

संग्रह के माध्यम से पुनरावृत्ति करने वाला इटेरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - संग्रह के माध्यम से पुनरावृत्ति करने वाला IGenericEnumerator।
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISummaryZoomSection> iteratorJava()
```

पूरे संग्रह के लिए जावा इटेरेटर लौटाता है।

**वापसी:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISummaryZoomSection> - पूरे संग्रह के लिए java.util.Iterator.