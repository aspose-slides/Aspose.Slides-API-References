---
title: ICommonSlideViewProperties
second_title: Aspose.Slides for Android via Java API Reference
description: सामान्य स्लाइड दृश्य गुणों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/icommonslideviewproperties/
---```
public interface ICommonSlideViewProperties
```

सामान्य स्लाइड दृश्य गुणों का प्रतिनिधित्व करता है।
## विधियों

| विधि | विवरण |
| --- | --- |
| [getScale()](#getScale--) | दृश्य स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। |
| [setScale(int value)](#setScale-int-) | दृश्य स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। |
| [getVariableScale()](#getVariableScale--) | निर्दिष्ट करता है कि दृश्य सामग्री को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से सर्वोत्तम फिट के लिए स्केल किया जाए। |
| [setVariableScale(boolean value)](#setVariableScale-boolean-) | निर्दिष्ट करता है कि दृश्य सामग्री को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से सर्वोत्तम फिट के लिए स्केल किया जाए। |
| [getDrawingGuides()](#getDrawingGuides--) | ड्राइंग गाइड की संग्रह लौटाता है। |
### getScale() {#getScale--}
```
public abstract int getScale()
```


दृश्य स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। पढ़ें/लिखें int.

**रिटर्न:**
int
### setScale(int value) {#setScale-int-}
```
public abstract void setScale(int value)
```


दृश्य स्केलिंग अनुपात को प्रतिशत में निर्दिष्ट करता है। पढ़ें/लिखें int.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getVariableScale() {#getVariableScale--}
```
public abstract boolean getVariableScale()
```


निर्दिष्ट करता है कि दृश्य सामग्री को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से सर्वोत्तम फिट के लिए स्केल किया जाए। पढ़ें/लिखें boolean.

**रिटर्न:**
boolean
### setVariableScale(boolean value) {#setVariableScale-boolean-}
```
public abstract void setVariableScale(boolean value)
```


निर्दिष्ट करता है कि दृश्य सामग्री को वर्तमान विंडो आकार के अनुसार स्वचालित रूप से सर्वोत्तम फिट के लिए स्केल किया जाए। पढ़ें/लिखें boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


ड्राइंग गाइड की संग्रह लौटाता है। केवल पढ़ने योग्य [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> The following sample code shows how to add the new drawing guides in a PowerPoint presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getViewProperties().getSlideViewProperties().getDrawingGuides();
>       // स्लाइड केंद्र के दाएँ ओर नया ऊर्ध्वाधर ड्राइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Vertical, (float)(slideSize.getWidth() / 2) + 12.5f);
>       // स्लाइड केंद्र के नीचे नया क्षैतिज ड्राइंग गाइड जोड़ रहा है
>      guides.add(Orientation.Horizontal, (float)(slideSize.getHeight() / 2) + 12.5f);
> 
>      pres.save("DrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)