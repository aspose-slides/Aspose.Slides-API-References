---
title: PptxOptions
second_title: Aspose.Slides के लिए Java API संदर्भ
description: OpenXml प्रस्तुतियों (PPTX, PPSX, POTX, PPTM, PPSM, POTM) को सहेजने के विकल्प का प्रतिनिधित्व करता है।
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

OpenXml प्रस्तुतियों (PPTX, PPSX, POTX, PPTM, PPSM, POTM) को सहेजने के विकल्प को दर्शाता है।

## निर्माता

| निर्माता | विवरण |
| --- | --- |
| [PptxOptions()](#PptxOptions--) | PptxOptions का नया उदाहरण बनाता है |

## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getConformance()](#getConformance--) | Presentation दस्तावेज़ द्वारा पालन किए जाने वाले अनुरूपता वर्ग को निर्दिष्ट करता है। |
| [setConformance(int value)](#setConformance-int-) | Presentation दस्तावेज़ द्वारा पालन किए जाने वाले अनुरूपता वर्ग को निर्दिष्ट करता है। |
| [getZip64Mode()](#getZip64Mode--) | Presentation दस्तावेज़ के लिए ZIP64 प्रारूप का उपयोग किया जाता है या नहीं, इसे निर्दिष्ट करता है। |
| [setZip64Mode(int value)](#setZip64Mode-int-) | Presentation दस्तावेज़ के लिए ZIP64 प्रारूप का उपयोग किया जाता है या नहीं, इसे निर्दिष्ट करता है। |
| [getRefreshThumbnail()](#getRefreshThumbnail--) | प्रस्तुति थंबनेल को रीफ़्रेश किया जाएगा या नहीं, इसे निर्दिष्ट करता है। |
| [setRefreshThumbnail(boolean value)](#setRefreshThumbnail-boolean-) | प्रस्तुति थंबनेल को रीफ़्रेश किया जाएगा या नहीं, इसे निर्दिष्ट करता है। |
| [getCompressionLevel()](#getCompressionLevel--) | प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। |
| [setCompressionLevel(int value)](#setCompressionLevel-int-) | प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। |

### PptxOptions() {#PptxOptions--}
```
public PptxOptions()
```

PptxOptions का नया उदाहरण बनाता है

### getConformance() {#getConformance--}
```
public final int getConformance()
```

Presentation दस्तावेज़ द्वारा पालन किए जाने वाले अनुरूपता वर्ग को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**रिटर्न:**
int

### setConformance(int value) {#setConformance-int-}
```
public final void setConformance(int value)
```

Presentation दस्तावेज़ द्वारा पालन किए जाने वाले अनुरूपता वर्ग को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Conformance.Ecma376\_2006](../../com.aspose.slides/conformance\#Ecma376-2006)

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |

### getZip64Mode() {#getZip64Mode--}
```
public final int getZip64Mode()
```

Presentation दस्तावेज़ के लिए ZIP64 प्रारूप का उपयोग किया जाता है या नहीं, इसे निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

Presentation दस्तावेज़ के लिए ZIP64 प्रारूप का उपयोग किया जाता है या नहीं, इसे निर्दिष्ट करता है। डिफ़ॉल्ट मान है [Zip64Mode.IfNecessary](../../com.aspose.slides/zip64mode\#IfNecessary)

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

प्रस्तुति थंबनेल को रीफ़्रेश किया जाएगा या नहीं, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान **true**।

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

जब विकल्प मान **true** हो, तो नया थंबनेल तैयार किया जाएगा।

जब विकल्प मान **false** हो, तो वर्तमान थंबनेल को जैसा है वैसा ही सहेजा जाएगा।

**रिटर्न:**
boolean

### setRefreshThumbnail(boolean value) {#setRefreshThumbnail-boolean-}
```
public final void setRefreshThumbnail(boolean value)
```

प्रस्तुति थंबनेल को रीफ़्रेश किया जाएगा या नहीं, इसे निर्दिष्ट करता है। पढ़ने/लिखने योग्य बूलियन। डिफ़ॉल्ट मान **true**।

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

जब विकल्प मान **true** हो, तो नया थंबनेल तैयार किया जाएगा।

जब विकल्प मान **false** हो, तो वर्तमान थंबनेल को जैसा है वैसा ही सहेजा जाएगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### getCompressionLevel() {#getCompressionLevel--}
```
public final int getCompressionLevel()
```

प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)।

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

उच्च संपीड़न स्तर छोटे फ़ाइलें बनाते हैं लेकिन अधिक प्रोसेसिंग समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रस्तुति की सामग्री पर निर्भर करता है।

**रिटर्न:**
int

### setCompressionLevel(int value) {#setCompressionLevel-int-}
```
public final void setCompressionLevel(int value)
```

प्रस्तुति दस्तावेज़ सहेजते समय उपयोग किए जाने वाले संपीड़न स्तर को निर्दिष्ट करता है। डिफ़ॉल्ट मान है [CompressionLevel.Level6](../../com.aspose.slides/compressionlevel\#Level6)।

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

उच्च संपीड़न स्तर छोटे फ़ाइलें बनाते हैं लेकिन अधिक प्रोसेसिंग समय की आवश्यकता होती है। वास्तविक संपीड़न अनुपात प्रस्तुति की सामग्री पर निर्भर करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |