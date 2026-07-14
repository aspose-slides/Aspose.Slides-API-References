---
title: MarkdownSaveOptions
second_title: Aspose.Slides for Android हेतु Java API रेफ़रेंस
description: प्रस्तुति को मार्कडाउन में सहेजने के तरीके को नियंत्रित करने वाले विकल्पों को दर्शाता है।
type: docs
url: /hi/com.aspose.slides/markdownsaveoptions/
---
**विरासत:**  
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)
```
public class MarkdownSaveOptions extends SaveOptions
```

प्रस्तुति को मार्कडाउन में सहेजने के तरीके को नियंत्रित करने वाले विकल्पों को दर्शाता है।

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

## कन्स्ट्रक्टर

| कन्स्ट्रक्टर | विवरण |
| --- | --- |
| [MarkdownSaveOptions()](#MarkdownSaveOptions--) | कंस्ट्रक्टर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getExportType()](#getExportType--) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। |
| [setExportType(int value)](#setExportType-int-) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। |
| [getBasePath()](#getBasePath--) | वह आधार पथ निर्दिष्ट करता है जहाँ संसाधनों के साथ दस्तावेज़ सहेजा जाएगा। |
| [setBasePath(String value)](#setBasePath-java.lang.String-) | वह आधार पथ निर्दिष्ट करता है जहाँ संसाधनों के साथ दस्तावेज़ सहेजा जाएगा। |
| [getImagesSaveFolderName()](#getImagesSaveFolderName--) | छवियों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। |
| [setImagesSaveFolderName(String value)](#setImagesSaveFolderName-java.lang.String-) | छवियों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। |
| [getNewLineType()](#getNewLineType--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियां \\r (Macintosh) या \\n (Unix) या \\r\\n (Windows) हों। |
| [setNewLineType(int value)](#setNewLineType-int-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियां \\r (Macintosh) या \\n (Unix) या \\r\\n (Windows) हों। |
| [getShowComments()](#getShowComments--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ टिप्पणियों को दिखाए या नहीं। |
| [setShowComments(boolean value)](#setShowComments-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ टिप्पणियों को दिखाए या नहीं। |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड शामिल करें या नहीं। |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड शामिल करें या नहीं। |
| [getShowSlideNumber()](#getShowSlideNumber--) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का क्रमांक दिखाए या नहीं। |
| [setShowSlideNumber(boolean value)](#setShowSlideNumber-boolean-) | निर्धारित करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का क्रमांक दिखाए या नहीं। |
| [getFlavor()](#getFlavor--) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। |
| [setFlavor(int value)](#setFlavor-int-) | प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। |
| [getSlideNumberFormat()](#getSlideNumberFormat--) | स्लाइड नंबर हेडर के लिए प्रयुक्त स्वरूप स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [setSlideNumberFormat(String value)](#setSlideNumberFormat-java.lang.String-) | स्लाइड नंबर हेडर के लिए प्रयुक्त स्वरूप स्ट्रिंग प्राप्त करता है या सेट करता है। |
| [getHandleRepeatedSpaces()](#getHandleRepeatedSpaces--) | मार्कडाउन निर्यात के दौरान दोहराए गए सामान्य स्पेस वर्णों को कैसे संभालना है, यह निर्धारित करता है। |
| [setHandleRepeatedSpaces(int value)](#setHandleRepeatedSpaces-int-) | मार्कडाउन निर्यात के दौरान दोहराए गए सामान्य स्पेस वर्णों को कैसे संभालना है, यह निर्धारित करता है। |
| [getRemoveEmptyLines()](#getRemoveEmptyLines--) | यदि true सेट किया गया है, तो अंतिम मार्कडाउन आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटाता है। |
| [setRemoveEmptyLines(boolean value)](#setRemoveEmptyLines-boolean-) | यदि true सेट किया गया है, तो अंतिम मार्कडाउन आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटाता है। |
| [setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)](#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-) | प्रत्येक non-SVG छवि (बिटमैप या मेटाफाइल) के लिए मार्कडाउन निर्यात के दौरान होता है। |
| [setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)](#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-) | प्रत्येक SVG छवि के लिए मार्कडाउन निर्यात के दौरान होता है। |
### MarkdownSaveOptions() {#MarkdownSaveOptions--}
```
public MarkdownSaveOptions()
```

कंस्ट्रक्टर।

### getExportType() {#getExportType--}
```
public final int getExportType()
```

प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। डिफ़ॉल्ट है TextOnly।

**वापसी:**  
int
### setExportType(int value) {#setExportType-int-}
```
public final void setExportType(int value)
```

प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। डिफ़ॉल्ट है TextOnly।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getBasePath() {#getBasePath--}
```
public final String getBasePath()
```

संसाधनों के साथ दस्तावेज़ जहाँ सहेजा जाएगा, उसके आधार पथ को निर्दिष्ट करता है। डिफ़ॉल्ट वर्तमान एप्लिकेशन की निर्देशिका है।

**वापसी:**  
java.lang.String
### setBasePath(String value) {#setBasePath-java.lang.String-}
```
public final void setBasePath(String value)
```

संसाधनों के साथ दस्तावेज़ जहाँ सहेजा जाएगा, उसके आधार पथ को निर्दिष्ट करता है। डिफ़ॉल्ट वर्तमान एप्लिकेशन की निर्देशिका है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getImagesSaveFolderName() {#getImagesSaveFolderName--}
```
public final String getImagesSaveFolderName()
```

छवियों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। डिफ़ॉल्ट Images है।

**वापसी:**  
java.lang.String
### setImagesSaveFolderName(String value) {#setImagesSaveFolderName-java.lang.String-}
```
public final void setImagesSaveFolderName(String value)
```

छवियों को सहेजने के लिए फ़ोल्डर नाम निर्दिष्ट करता है। डिफ़ॉल्ट Images है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getNewLineType() {#getNewLineType--}
```
public final int getNewLineType()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियां \\r (Macintosh) या \\n (Unix) या \\r\\n (Windows) हों। डिफ़ॉल्ट Unix है।

**वापसी:**  
int
### setNewLineType(int value) {#setNewLineType-int-}
```
public final void setNewLineType(int value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में नई पंक्तियां \\r (Macintosh) या \\n (Unix) या \\r\\n (Windows) हों। डिफ़ॉल्ट Unix है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getShowComments() {#getShowComments--}
```
public final boolean getShowComments()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में टिप्पणियां दिखें या नहीं। डिफ़ॉल्ट false है।

**वापसी:**  
boolean
### setShowComments(boolean value) {#setShowComments-boolean-}
```
public final void setShowComments(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में टिप्पणियां दिखें या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड शामिल करें या नहीं। डिफ़ॉल्ट false है।

**वापसी:**  
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में छिपी स्लाइड शामिल करें या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getShowSlideNumber() {#getShowSlideNumber--}
```
public final boolean getShowSlideNumber()
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का क्रमांक दिखाए या नहीं। डिफ़ॉल्ट false है।

**वापसी:**  
boolean
### setShowSlideNumber(boolean value) {#setShowSlideNumber-boolean-}
```
public final void setShowSlideNumber(boolean value)
```

निर्धारित करता है कि उत्पन्न दस्तावेज़ में प्रत्येक स्लाइड का क्रमांक दिखाए या नहीं। डिफ़ॉल्ट false है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### getFlavor() {#getFlavor--}
```
public final int getFlavor()
```

प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। डिफ़ॉल्ट Multi-markdown है।

**वापसी:**  
int
### setFlavor(int value) {#setFlavor-int-}
```
public final void setFlavor(int value)
```

प्रस्तुति को परिवर्तित करने के लिए मार्कडाउन विशिष्टता निर्धारित करता है। डिफ़ॉल्ट Multi-markdown है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getSlideNumberFormat() {#getSlideNumberFormat--}
```
public final String getSlideNumberFormat()
```

स्लाइड नंबर हेडर के लिए प्रयुक्त स्वरूप स्ट्रिंग प्राप्त करता है या सेट करता है। स्वरूप में "\{0\}" प्लेसहोल्डर होना आवश्यक है, जिसे निर्यात के दौरान स्लाइड इंडेक्स से बदला जाएगा। उदाहरण: "\# Slide \{0\}" "\# Slide 1", "\# Slide 2" आदि उत्पन्न करेगा।

**वापसी:**  
java.lang.String
### setSlideNumberFormat(String value) {#setSlideNumberFormat-java.lang.String-}
```
public final void setSlideNumberFormat(String value)
```

स्लाइड नंबर हेडर के लिए प्रयुक्त स्वरूप स्ट्रिंग प्राप्त करता है या सेट करता है। स्वरूप में "\{0\}" प्लेसहोल्डर होना आवश्यक है, जिसे निर्यात के दौरान स्लाइड इंडेक्स से बदला जाएगा। उदाहरण: "\# Slide \{0\}" "\# Slide 1", "\# Slide 2" आदि उत्पन्न करेगा।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | java.lang.String |  |
### getHandleRepeatedSpaces() {#getHandleRepeatedSpaces--}
```
public final int getHandleRepeatedSpaces()
```

मार्कडाउन निर्यात के दौरान दोहराए गए सामान्य स्पेस वर्णों को कैसे संभालना है, यह निर्धारित करता है। यह गुण परिभाषित करता है कि क्रमागत स्पेस: - नियमित स्पेस वर्णों के रूप में संरक्षित रहें, - नियमित स्पेस और नॉन-ब्रेकिंग स्पेस एंटिटी (�) के बीच वैकल्पिक हों, - या पूर्णतः (पहले के बाद) नॉन-ब्रेकिंग स्पेस से प्रतिस्थापित हों ताकि मार्कडाउन आउटपुट में दृश्य संरेखण बना रहे। डिफ़ॉल्ट मान [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) है।

**वापसी:**  
int
### setHandleRepeatedSpaces(int value) {#setHandleRepeatedSpaces-int-}
```
public final void setHandleRepeatedSpaces(int value)
```

मार्कडाउन निर्यात के दौरान दोहराए गए सामान्य स्पेस वर्णों को कैसे संभालना है, यह निर्धारित करता है। यह गुण परिभाषित करता है कि क्रमागत स्पेस: - नियमित स्पेस वर्णों के रूप में संरक्षित रहें, - नियमित स्पेस और नॉन-ब्रेकिंग स्पेस एंटिटी (�) के बीच वैकल्पिक हों, - या पूर्णतः (पहले के बाद) नॉन-ब्रेकिंग स्पेस से प्रतिस्थापित हों ताकि मार्कडाउन आउटपुट में दृश्य संरेखण बना रहे। डिफ़ॉल्ट मान [HandleRepeatedSpaces.AlternateSpacesToNbsp](../../com.aspose.slides/handlerepeatedspaces\#AlternateSpacesToNbsp) है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | int |  |
### getRemoveEmptyLines() {#getRemoveEmptyLines--}
```
public final boolean getRemoveEmptyLines()
```

यदि true सेट किया गया है, तो अंतिम मार्कडाउन आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटाता है। डिफ़ॉल्ट false है।

**वापसी:**  
boolean
### setRemoveEmptyLines(boolean value) {#setRemoveEmptyLines-boolean-}
```
public final void setRemoveEmptyLines(boolean value)
```

यदि true सेट किया गया है, तो अंतिम मार्कडाउन आउटपुट से खाली या केवल whitespace वाली पंक्तियों को हटाता है। डिफ़ॉल्ट false है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event) {#setImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownImageSavingHandler-}
```
public final void setImageSaving(MarkdownSaveOptions.MarkdownImageSavingHandler event)
```

मार्कडाउन निर्यात के दौरान प्रत्येक non-SVG छवि (बिटमैप या मेटाफाइल) के लिए होता है। छवि को सहेजने और संदर्भित करने के तरीके को अनुकूलित करने की अनुमति देता है। यदि नहीं संभाला गया, तो छवि स्थानीय रूप से सापेक्ष लिंक के साथ सहेजी जाती है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| event | [MarkdownImageSavingHandler](../../com.aspose.slides/markdownimagesavinghandler) | Markdown छवि सहेजने की घटना। |
### setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event) {#setSvgImageSaving-com.aspose.slides.MarkdownSaveOptions.MarkdownSvgImageSavingHandler-}
```
public final void setSvgImageSaving(MarkdownSaveOptions.MarkdownSvgImageSavingHandler event)
```

मार्कडाउन निर्यात के दौरान प्रत्येक SVG छवि के लिए होता है। डिफ़ॉल्ट सहेजने और लिंक निर्माण को ओवरराइड करने की अनुमति देता है। यदि नहीं संभाला गया, तो SVG स्थानीय रूप से सापेक्ष लिंक के साथ सहेजी जाती है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| event | [MarkdownSvgImageSavingHandler](../../com.aspose.slides/markdownsvgimagesavinghandler) | Markdown SVG छवि सहेजने की घटना। |