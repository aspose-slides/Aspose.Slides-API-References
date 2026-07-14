---
title: IPptxOptions
second_title: Aspose.Slides for Android के लिए Java API संदर्भ
description: OpenXml प्रस्तुतियों (PPTX, PPSX, POTX, PPTM, PPSM, POTM) को सहेजने के विकल्प दर्शाता है।
type: docs
url: /hi/com.aspose.slides/ipptxoptions/
---
**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IPptxOptions extends ISaveOptions
```

OpenXml प्रस्तुतियों (PPTX, PPSX, POTX, PPTM, PPSM, POTM) को सहेजने के विकल्पों को दर्शाता है।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getConformance()](#getConformance--) | निर्दिष्ट करता है कि Presentation दस्तावेज़ किस कन्फॉर्मेंस क्लास का पालन करता है। |
| [setConformance(int value)](#setConformance-int-) | निर्दिष्ट करता है कि Presentation दस्तावेज़ किस कन्फॉर्मेंस क्लास का पालन करता है। |
| [getZip64Mode()](#getZip64Mode--) | निर्दिष्ट करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया गया है या नहीं। |
| [setZip64Mode(int value)](#setZip64Mode-int-) | निर्दिष्ट करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया गया है या नहीं। |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | निर्दिष्ट करता है कि प्रस्तुतिकरण थंबनेल रीफ़्रेश किया जाएगा या नहीं। |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | निर्दिष्ट करता है कि प्रस्तुतिकरण थंबनेल रीफ़्रेश किया जाएगा या नहीं। |
| [getCompressionLevel()](#getCompressionLevel--) | निर्दिष्ट करता है कि प्रस्तुतिकरण दस्तावेज़ को सहेजते समय किस संपीड़न स्तर का उपयोग किया गया है। |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | निर्दिष्ट करता है कि प्रस्तुतिकरण दस्तावेज़ को सहेजते समय किस संपीड़न स्तर का उपयोग किया गया है। |
### getConformance() {#getConformance--}
```
public abstract int getConformance()
```


निर्दिष्ट करता है कि Presentation दस्तावेज़ किस कन्फॉर्मेंस क्लास का पालन करता है। डिफ़ॉल्ट मान [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**रिटर्न:**
int
### setConformance(int value) {#setConformance-int-}
```
public abstract void setConformance(int value)
```


निर्दिष्ट करता है कि Presentation दस्तावेज़ किस कन्फॉर्मेंस क्लास का पालन करता है। डिफ़ॉल्ट मान [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public abstract int getZip64Mode()
```


निर्दिष्ट करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया गया है या नहीं। डिफ़ॉल्ट मान [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**रिटर्न:**
int
### setZip64Mode(int value) {#setZip64Mode-int-}
```
public abstract void setZip64Mode(int value)
```


निर्दिष्ट करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया गया है या नहीं। डिफ़ॉल्ट मान [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setZip64Mode(Zip64Mode.Always);
>      pres.save("demo-zip64.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getRefreshThumbnail() {#getRefreshThumbnail--}
```
public abstract boolean getRefreshThumbnail()
```


निर्दिष्ट करता है कि प्रस्तुतिकरण थंबनेल रीफ़्रेश किया जाएगा या नहीं। रीड/राइट बूलियन। डिफ़ॉल्ट मान **true** है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

जब विकल्प मूल्य **true** हो, नया थंबनेल जनरेट किया जाएगा।

जब विकल्प मूल्य **false** हो, वर्तमान थंबनेल जैसा का तैसा सहेजा जाएगा।

**रिटर्न:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public abstract void setRefreshThumbnail(boolean value)
```


निर्दिष्ट करता है कि प्रस्तुतिकरण थंबनेल रीफ़्रेश किया जाएगा या नहीं। रीड/राइट बूलियन। डिफ़ॉल्ट मान **true** है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setRefreshThumbnail(false);
>      pres.save("result_with_old_thumbnail.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

जब विकल्प मूल्य **true** हो, नया थंबनेल जनरेट किया जाएगा।

जब विकल्प मूल्य **false** हो, वर्तमान थंबनेल जैसा का तैसा सहेजा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public abstract int getCompressionLevel()
```


निर्दिष्ट करता है कि प्रस्तुतिकरण दस्तावेज़ को सहेजते समय किस संपीड़न स्तर का उपयोग किया गया है। डिफ़ॉल्ट मान [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

उच्च संपीड़न स्तर छोटे फ़ाइलें बनाते हैं लेकिन अधिक प्रोसेसिंग समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रस्तुतिकरण की सामग्री पर निर्भर करता है।

**रिटर्न:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public abstract void setCompressionLevel(int value)
```


निर्दिष्ट करता है कि प्रस्तुतिकरण दस्तावेज़ को सहेजते समय किस संपीड़न स्तर का उपयोग किया गया है। डिफ़ॉल्ट मान [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      PptxOptions pptxOptions = new PptxOptions();
>      pptxOptions.setCompressionLevel(CompressionLevel.Level8);
>      pres.save("demo-level8.pptx", SaveFormat.Pptx, pptxOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

उच्च संपीड़न स्तर छोटे फ़ाइलें बनाते हैं लेकिन अधिक प्रोसेसिंग समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रस्तुतिकरण की सामग्री पर निर्भर करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |