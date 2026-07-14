---
title: PptxOptions
second_title: Android के लिए Aspose.Slides, Java API संदर्भ द्वारा
description: OpenXml प्रस्तुतियों PPTX, PPSX, POTX, PPTM, PPSM, POTM को सहेजने के विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/pptxoptions/
---
**विरासत:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPptxOptions](../../com.aspose.slides/ipptxoptions), java.lang.Cloneable
```
public final class PptxOptions extends SaveOptions implements IPptxOptions, Cloneable
```

OpenXml प्रस्तुतियों (PPTX, PPSX, POTX, PPTM, PPSM, POTM) को सहेजने के विकल्पों का प्रतिनिधित्व करता है।
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | PptxOptions का नया इंस्टेंस बनाता है |
## मेथड

| मेथड | विवरण |
| --- | --- |
| [getConformance()](#getConformance--) | वह संगतता क्लास निर्दिष्ट करता है जिससे Presentation दस्तावेज़ मेल खाता है। |
| [setConformance(int value)](#setConformance-int-) | वह संगतता क्लास निर्दिष्ट करता है जिससे Presentation दस्तावेज़ मेल खाता है। |
| [getZip64Mode()](#getZip64Mode--) | निर्दिष्ट करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया जाता है या नहीं। |
| [setZip64Mode(int value)](#setZip64Mode-int-) | निर्दिष्ट करता है कि Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट उपयोग किया जाता है या नहीं। |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | निर्दिष्ट करता है कि प्रस्तुति थंबनेल रीफ़्रेश किया जाएगा या नहीं। |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | निर्दिष्ट करता है कि प्रस्तुति थंबनेल रीफ़्रेश किया जाएगा या नहीं। |
| [getCompressionLevel()](#getCompressionLevel--) | प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। |
### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```


PptxOptions का नया इंस्टेंस बनाता है

### getConformance() {#getConformance--}
```
public final int getConformance()
```


Presentation दस्तावेज़ के लिए संगतता क्लास को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**रिटर्न:**
int
### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```


Presentation दस्तावेज़ के लिए संगतता क्लास को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```


Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट का उपयोग किया जाता है या नहीं, इसे निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public final void setZip64Mode(int value)
```


Presentation दस्तावेज़ के लिए ZIP64 फ़ॉर्मेट का उपयोग किया जाता है या नहीं, इसे निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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
public final boolean getRefreshThumbnail()
```


निर्दिष्ट करता है कि प्रस्तुति थंबनेल रीफ़्रेश किया जाएगा या नहीं। पढ़ें/लिखें बूलियन। डिफ़ॉल्ट मान **true**।

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

जब विकल्प मान **true** हो, तो नया थंबनेल उत्पन्न किया जाएगा।

जब विकल्प मान **false** हो, तो मौजूदा थंबनेल जैसा का तैसा सहेजा जाएगा।

**रिटर्न:**
boolean
### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```


निर्दिष्ट करता है कि प्रस्तुति थंबनेल रीफ़्रेश किया जाएगा या नहीं। पढ़ें/लिखें बूलियन। डिफ़ॉल्ट मान **true**।

####################

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

जब विकल्प मान **true** हो, तो नया थंबनेल उत्पन्न किया जाएगा।

जब विकल्प मान **false** हो, तो मौजूदा थंबनेल जैसा का तैसा सहेजा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```


प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

उच्च संपीड़न स्तर छोटे फ़ाइलें बनाते हैं लेकिन अधिक प्रोसेसिंग समय लेते हैं। वास्तविक संपीड़न अनुपात प्रस्तुति की सामग्री पर निर्भर करता है।

**रिटर्न:**
int
### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```


प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6).

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

उच्च संपीड़न स्तर छोटे फ़ाइलें बनाते हैं लेकिन अधिक प्रोसेसिंग समय लेते हैं। वास्तविक संपीड़न अनुपात प्रस्तुति की सामग्री पर निर्भर करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |