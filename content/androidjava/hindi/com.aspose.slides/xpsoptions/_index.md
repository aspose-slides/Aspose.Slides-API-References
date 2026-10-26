---
title: XpsOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: प्रेज़ेंटेशन को XPS फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/xpsoptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**  
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)  
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

प्रेज़ेंटेशन को XPS फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // एक Presentation ऑब्जेक्ट बनाता है जो प्रस्तुतीकरण फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pers = new Presentation("Convert_XPS.pptx");
>  try {
>      // प्रस्तुतीकरण को XPS दस्तावेज़ में सहेज रहा है
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // एक Presentation ऑब्जेक्ट बनाता है जो प्रस्तुतीकरण फ़ाइल का प्रतिनिधित्व करता है
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // TiffOptions क्लास का इंस्टेंस बनाता है
>      XpsOptions options = new XpsOptions();
>      // MetaFiles को PNG के रूप में सहेजें
>      options.setSaveMetafilesAsPng(true);
>      // प्रस्तुतीकरण को XPS दस्तावेज़ में सहेज रहा है
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## कन्स्ट्रक्टर्स

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | डिफ़ॉल्ट कन्स्ट्रक्टर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | यह निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | यह निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | प्रेज़ेंटेशन में उपयोग की गई सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए true। |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | प्रेज़ेंटेशन में उपयोग की गई सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए true। |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | प्रत्येक स्लाइड के चारों ओर काला फ्रेम खींचने के लिए true। |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | प्रत्येक स्लाइड के चारों ओर काला फ्रेम खींचने के लिए true। |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

डिफ़ॉल्ट कन्स्ट्रक्टर।

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

यह निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट false है।

**वापसी मान:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

यह निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होंगी या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

प्रेज़ेंटेशन में उपयोग की गई सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए true। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **true** है।

**वापसी मान:**  
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

प्रेज़ेंटेशन में उपयोग की गई सभी मेटा-फ़ाइलों को PNG छवियों में बदलने के लिए true। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **true** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

प्रत्येक स्लाइड के चारों ओर काला फ्रेम खींचने के लिए true। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **false** है।

**वापसी मान:**  
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

प्रत्येक स्लाइड के चारों ओर काला फ्रेम खींचने के लिए true। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **false** है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |