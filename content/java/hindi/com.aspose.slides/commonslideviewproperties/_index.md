---
title: CommonSlideViewProperties
second_title: Aspose.Slides के लिए Java API संदर्भ
description: सामान्य स्लाइड व्यू गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/commonslideviewproperties/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ICommonSlideViewProperties](../../com.aspose.slides/icommonslideviewproperties)
```
public class CommonSlideViewProperties implements ICommonSlideViewProperties
```

सामान्य स्लाइड व्यू गुणों का प्रतिनिधित्व करता है।

--------------------

> ```
> The following example shows how to set the zoom value for slide of PowerPoint Presentation.
>  
>  // एक Presentation ऑब्जेक्ट बनाएं जो प्रस्तुति फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Presentation की व्यू प्रॉपर्टी सेट करना
>      pres.getViewProperties().getSlideViewProperties().setScale(100); // स्लाइड व्यू के लिए प्रतिशत में ज़ूम मान
>      pres.getViewProperties().getNotesViewProperties().setScale(100); // नोट्स व्यू के लिए प्रतिशत में ज़ूम मान
>      pres.save("Zoom_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## विधाएँ

| विधि | विवरण |
| --- | --- |
| [getScale()](#getScale--) | व्यू स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। |
| [setScale(int value)](#setScale-int-) | व्यू स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। |
| [getVariableScale()](#getVariableScale--) | व्यू कंटेंट को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से स्केल करने को निर्दिष्ट करता है। |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | व्यू कंटेंट को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से स्केल करने को निर्दिष्ट करता है। |
| [getDrawingGuides()](#getDrawingGuides--) | ड्राइंग गाइड्स के संग्रह को लौटाता है। |
### getScale() {#getScale--}
```
public final int getScale()
```

व्यू स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। पढ़ने/लिखने योग्य int.

**रिटर्न:**
int
### setScale(int value) {#setScale-int-}
```
public final void setScale(int value)
```

व्यू स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। पढ़ने/लिखने योग्य int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public final boolean getVariableScale()
```

व्यू कंटेंट को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से स्केल करने को निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**रिटर्न:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public final void setVariableScale(boolean value)
```

व्यू कंटेंट को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से स्केल करने को निर्दिष्ट करता है। पढ़ने/लिखने योग्य boolean।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

ड्राइंग गाइड्स के संग्रह को लौटाता है। केवल-पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>      // स्लाइड केंद्र के दाएँ हिस्से में नई लंबवत ड्राइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth()) / 2 + 12.5f);
>      // स्लाइड केंद्र के नीचे नई क्षैतिज ड्राइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)