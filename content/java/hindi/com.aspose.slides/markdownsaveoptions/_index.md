---
title: MarkdownSaveOptions
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रेजेंटेशन को मार्कडाउन में सहेजने के तरीके को नियंत्रित करने वाले विकल्पों का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/markdownsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

प्रेजेंटेशन को मार्कडाउन में सहेजने के तरीके को नियंत्रित करने वाले विकल्पों का प्रतिनिधित्व करता है।

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation(presentationFileName);
>  try {
>      FileOutputStream stream = new FileOutputStream("MdFileForGitHubFlavor");
>      try {
>          MarkdownSaveOptions markdownSaveOptions = new MarkdownSaveOptions();
>          markdownSaveOptions.setShowHiddenSlides(true);
>          markdownSaveOptions.setShowSlideNumber(true);
>          markdownSaveOptions.setFlavor(Flavor.Github);
>          markdownSaveOptions.setExportType(MarkdownExportType.Sequential);
>          markdownSaveOptions.setNewLineType(NewLineType.Windows);
>          markdownSaveOptions.setBasePath(documentResourcesPath);
> 
>          pres.save(stream, new int[]{1, 2, 3, 4, 5, 6, 7, 8, 9}, SaveFormat.Md, markdownSaveOptions);
>      } finally {
>          if (stream != null) stream.close();
>      }
>  } catch (Exception e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## कंस्ट्रक्टर

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | निर्माता |
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getExportType()](#getExportType--) | प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। |
| [setExportType(int value)](#setExportType-int-) | प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। |
| [getBasePath()](#getBasePath--) | संसाधनों वाले दस्तावेज को सहेजने के लिए आधार पथ निर्दिष्ट करता है। |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | संसाधनों वाले दस्तावेज को सहेजने के लिए आधार पथ निर्दिष्ट करता है। |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | चित्रों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | चित्रों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। |
| [getNewLineType()](#getNewLineType--) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियाँ \\r(Macintosh) या \\n(Unix) या \\r\\n(Windows) होनी चाहिए या नहीं। |
| [setNewLineType(int value)](#setNewLineType-int-) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियाँ \\r(Macintosh) या \\n(Unix) या \\r\\n(Windows) होनी चाहिए या नहीं। |
| [getShowComments()](#getShowComments--) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ टिप्पणी दिखाएगा या नहीं। |
| [setShowComments(boolean value)](#setShowComments-boolean-) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ टिप्पणी दिखाएगा या नहीं। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइडें शामिल होंगी या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइडें शामिल होंगी या नहीं। |
| [getShowSlideNumber()](#getShowSlideNumber--) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का नंबर दिखाया जाएगा या नहीं। |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का नंबर दिखाया जाएगा या नहीं। |
| [getFlavor()](#getFlavor--) | प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। |
| [setFlavor(int value)](#setFlavor-int-) | प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | Markdown आउटपुट में स्लाइड नंबर हेडर के लिए उपयोग की जाने वाली प्रारूप स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | Markdown आउटपुट में स्लाइड नंबर हेडर के लिए उपयोग की जाने वाली प्रारूप स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | Markdown निर्यात के दौरान दोहराए गए नियमित स्पेस अक्षरों को कैसे संभालना है, निर्दिष्ट करता है। |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | Markdown निर्यात के दौरान दोहराए गए नियमित स्पेस अक्षरों को कैसे संभालना है, निर्दिष्ट करता है। |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | यदि true सेट किया जाता है, तो अंतिम Markdown आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटा देता है। |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | यदि true सेट किया जाता है, तो अंतिम Markdown आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटा देता है। |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | Markdown निर्यात کے दौरान प्रत्येक non-SVG छवि (बिटमैप या मेटाफाइल) के लिए होता है। |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | Markdown निर्यात کے दौरान प्रत्येक SVG छवि के लिए होता है। |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

निर्माता।

### getExportType() {#getExportType--}
```
public final int getExportType()
```

प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। डिफ़ॉल्ट है TextOnly।

**रिटर्न:**
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। डिफ़ॉल्ट है TextOnly।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

संसाधनों वाले दस्तावेज को सहेजने के लिए आधार पथ निर्दिष्ट करता है। डिफ़ॉल्ट है अनुप्रयोग की वर्तमान निर्देशिका।

**रिटर्न:**
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

संसाधनों वाले दस्तावेज को सहेजने के लिए आधार पथ निर्दिष्ट करता है। डिफ़ॉल्ट है अनुप्रयोग की वर्तमान निर्देशिका।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

चित्रों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। डिफ़ॉल्ट है Images।

**रिटर्न:**
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

चित्रों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। डिफ़ॉल्ट है Images।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियाँ \\r(Macintosh) या \\n(Unix) या \\r\\n(Windows) होनी चाहिए या नहीं। डिफ़ॉल्ट है Unix।

**रिटर्न:**
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियाँ \\r(Macintosh) या \\n(Unix) या \\r\\n(Windows) होनी चाहिए या नहीं। डिफ़ॉल्ट है Unix।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ टिप्पणी दिखाएगा या नहीं। डिफ़ॉल्ट है false।

**रिटर्न:**
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ टिप्पणी दिखाएगा या नहीं। डिफ़ॉल्ट है false।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्दিষ্ট करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइडें शामिल होंगी या नहीं। डिफ़ॉल्ट है false।

**रिटर्न:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइडें शामिल होंगी या नहीं। डिफ़ॉल्ट है false।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का नंबर दिखाया जाएगा या नहीं। डिफ़ॉल्ट है false।

**रिटर्न:**
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

निर्दिष्ट करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का नंबर दिखाया जाएगा या नहीं। डिफ़ॉल्ट है false।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। डिफ़ॉल्ट है Multi-markdown।

**रिटर्न:**
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

प्रेजेंटेशन को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्दिष्ट करता है। डिफ़ॉल्ट है Multi-markdown।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

Markdown आउटपुट में स्लाइड नंबर हेडर के लिए उपयोग की जाने वाली प्रारूप स्ट्रिंग प्राप्त करता है या सेट करता है। स्वरूप में "\{0\}" प्लेसहोल्डर शामिल होना चाहिए, जिसे निर्यात के दौरान स्लाइड क्रमांक से प्रतिस्थापित किया जाएगा। उदाहरण: "\# Slide \{0\}" "\# Slide 1", "\# Slide 2" आदि उत्पन्न करेगा।

**रिटर्न:**
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

Markdown आउटपुट में स्लाइड नंबर हेडर के लिए उपयोग की जाने वाली प्रारूप स्ट्रिंग प्राप्त करता है या सेट करता है। स्वरूप में "\{0\}" प्लेसहोल्डर शामिल होना चाहिए, जिसे निर्यात के दौरान स्लाइड क्रमांक से प्रतिस्थापित किया जाएगा। उदाहरण: "\# Slide \{0\}" "\# Slide 1", "\# Slide 2" आदि उत्पन्न करेगा।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

Markdown निर्यात के दौरान दोहराए गए नियमित स्पेस अक्षरों को कैसे संभालना है, निर्दिष्ट करता है। यह प्रॉपर्टी परिभाषित करती है कि क्रमागत स्पेस: - नियमित स्पेस अक्षर के रूप में संरक्षित रहें, - नियमित स्पेस और non-breaking space entities (�) के बीच बदलते रहें, - या प्रथम के बाद पूरी तरह से non-breaking space से प्रतिस्थापित हों ताकि Markdown आउटपुट में दृश्य संरेखण बना रहे। डिफ़ॉल्ट मान है [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)।

**रिटर्न:**
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

Markdown निर्यात के दौरान दोहराए गए नियमित स्पेस अक्षरों को कैसे संभालना है, निर्दिष्ट करता है। यह प्रॉपर्टी परिभाषित करती है कि क्रमागत स्पेस: - नियमित स्पेस अक्षर के रूप में संरक्षित रहें, - नियमित स्पेस और non-breaking space entities (�) के बीच बदलते रहें, - या प्रथम के बाद पूरी तरह से non-breaking space से प्रतिस्थापित हों ताकि Markdown आउटपुट में दृश्य संरेखण बना रहे। डिफ़ॉल्ट मान है [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp)।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

यदि true सेट किया जाता है, तो अंतिम Markdown आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटा देता है। डिफ़ॉल्ट है false।

**रिटर्न:**
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

यदि true सेट किया जाता है, तो अंतिम Markdown आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटा देता है। डिफ़ॉल्ट है false।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

Markdown निर्यात के दौरान प्रत्येक non-SVG छवि (बिटमैप या मेटाफाइल) के लिए होता है। यह छवि के सहेजे जाने और संदर्भित किए जाने के तरीके को अनुकूलित करने की अनुमति देता है। यदि नहीं संभाला गया, तो छवि स्थानीय रूप से सापेक्ष लिंक के साथ सहेजी जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown छवि सहेजने का इवेंट। |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

Markdown निर्यात के दौरान प्रत्येक SVG छवि के लिए होता है। यह डिफ़ॉल्ट सहेजने और लिंक जनरेशन को ओवरराइड करने की अनुमति देता है। यदि नहीं संभाला गया, तो SVG स्थानीय रूप से सापेक्ष लिंक के साथ सहेजी जाती है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG छवि सहेजने का इवेंट। |