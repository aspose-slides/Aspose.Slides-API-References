---
title: XpsOptions
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: प्रस्तुति को XPS फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।
type: docs
url: /hi/com.aspose.slides/xpsoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**All Implemented Interfaces:**
[com.aspose.slides.IXpsOptions](../../com.aspose.slides/ixpsoptions)
```
public class XpsOptions extends SaveOptions implements IXpsOptions
```

एक प्रस्तुति को XPS फ़ॉर्मेट में सहेजने के तरीके को नियंत्रित करने वाले विकल्प प्रदान करता है।

--------------------

> ```
> The following example shows how to converting presentations to XPS using default settings.
>  
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला Presentation ऑब्जेक्ट बनाएं
>  Presentation pres = new Presentation("Convert_XPS.pptx");
>  try {
>      // प्रस्तुति को XPS दस्तावेज़ में सहेजना
>      pres.save("XPS_Output_Without_XPSOption_out.xps", SaveFormat.Xps);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to converting presentations to XPS using custom settings.
>  
>  // प्रस्तुति फ़ाइल का प्रतिनिधित्व करने वाला Presentation ऑब्जेक्ट बनाएं
>  Presentation pres = new Presentation("Convert_XPS_Options.pptx");
>  try {
>      // TiffOptions वर्ग को बनाएं
>      XpsOptions options = new XpsOptions();
>      // MetaFiles को PNG के रूप में सहेजें
>      options.setSaveMetafilesAsPng(true);
>      // प्रस्तुति को XPS दस्तावेज़ में सहेजें
>      pres.save("XPS_With_Options_out.xps", SaveFormat.Xps, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Constructors

| Constructor | Description |
| --- | --- |
| [XpsOptions()](#XpsOptions--) | डिफ़ॉल्ट कन्स्ट्रक्टर। |
## Methods

| Method | Description |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। |
| [getSaveMetafilesAsPng()](#getSaveMetafilesAsPng--) | प्रस्तुति में उपयोग की गई सभी मेटाफाइलों को PNG छवियों में बदलने के लिए True। |
| [setSaveMetafilesAsPng(boolean value)](#setSaveMetafilesAsPng-boolean-) | प्रस्तुति में उपयोग की गई सभी मेटाफाइलों को PNG छवियों में बदलने के लिए True। |
| [getDrawSlidesFrame()](#getDrawSlidesFrame--) | प्रत्येक स्लाइड के आसपास काली फ्रेम खींचने के लिए True। |
| [setDrawSlidesFrame(boolean value)](#setDrawSlidesFrame-boolean-) | प्रत्येक स्लाइड के आसपास काली फ्रेम खींचने के लिए True। |
### XpsOptions() {#XpsOptions--}
```
public XpsOptions()
```

डिफ़ॉल्ट कन्स्ट्रक्टर।

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट false है।

**Returns:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड्स शामिल होनी चाहिए या नहीं। डिफ़ॉल्ट false है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveMetafilesAsPng() {#getSaveMetafilesAsPng--}
```
public final boolean getSaveMetafilesAsPng()
```

प्रस्तुति में उपयोग की गई सभी मेटाफाइलों को PNG छवियों में बदलने के लिए True। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **true** है।

**Returns:**
boolean
### setSaveMetafilesAsPng(boolean value) {#setSaveMetafilesAsPng-boolean-}
```
public final void setSaveMetafilesAsPng(boolean value)
```

प्रस्तुति में उपयोग की गई सभी मेटाफाइलों को PNG छवियों में बदलने के लिए True। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **true** है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDrawSlidesFrame() {#getDrawSlidesFrame--}
```
public final boolean getDrawSlidesFrame()
```

प्रत्येक स्लाइड के आसपास काली फ्रेम खींचने के लिए True। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **false** है।

**Returns:**
boolean
### setDrawSlidesFrame(boolean value) {#setDrawSlidesFrame-boolean-}
```
public final void setDrawSlidesFrame(boolean value)
```

प्रत्येक स्लाइड के आसपास काली फ्रेम खींचने के लिए True। पढ़ने/लिखने योग्य बूलियन।

--------------------

डिफ़ॉल्ट **false** है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |