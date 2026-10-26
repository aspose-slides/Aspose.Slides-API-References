---
title: WebDocument
second_title: Aspose.Slides for Android के लिए Java API रेफ़रेंस
description: प्रेजेंटेशन को वेब फ़ॉर्मेट में सहेजने के लिए एक ट्रांज़िशन फ़ॉर्म प्रस्तुत करता है।
type: docs
url: /hi/com.aspose.slides/webdocument/
---
**विरासत:**
java.lang.Object
```
public class WebDocument
```

प्रस्तुति को वेब फ़ॉर्मेट में सहेजने के लिए एक ट्रांज़िशन फ़ॉर्म प्रस्तुत करता है।
## निर्माते

| कंस्ट्रक्टर | विवरण |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) कंस्ट्रक्टर। |
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [save()](#save--) | दस्तावेज़ आउटपुट को सहेजता है। |
| [getInput()](#getInput--) | दस्तावेज़ के इनपुट तत्वों (टेम्पलेट) का संग्रह लौटाता है। |
| [getOutput()](#getOutput--) | दस्तावेज़ के आउटपुट तत्वों का संग्रह लौटाता है। |
| [getGlobal()](#getGlobal--) | दस्तावेज़ का ग्लोबल स्टोरेज लौटाता है। |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```


[WebDocument](../../com.aspose.slides/webdocument) कंस्ट्रक्टर।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| options | [WebDocumentOptions](../../com.aspose.slides/webdocumentoptions) | दस्तावेज़ के लिए सेट विकल्प। |
### save() {#save--}
```
public final void save()
```


दस्तावेज़ आउटपुट को सहेजता है।

### getInput() {#getInput--}
```
public final Input getInput()
```


दस्तावेज़ के इनपुट तत्वों (टेम्पलेट) का संग्रह लौटाता है। केवल-पढ़ने योग्य [Input](../../com.aspose.slides/input)(\#getInput.getInput).

**रिटर्न:**
[Input](../../com.aspose.slides/input)
### getOutput() {#getOutput--}
```
public final Output getOutput()
```


दस्तावेज़ के आउटपुट तत्वों का संग्रह लौटाता है। केवल-पढ़ने योग्य [Output](../../com.aspose.slides/output)(\#getOutput.getOutput).

--------------------

> ```
> WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // टेम्प्लेट से उपयोग करने के लिए "slideMargin" प्रॉपर्टी को रखें
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... दस्तावेज़ के अन्य विकल्प सेट करें और फिर दस्तावेज़ को सहेजें
>   document.save();
> ```


**रिटर्न:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```


दस्तावेज़ का ग्लोबल स्टोरेज लौटाता है। केवल-पढ़ने योग्य [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // टेम्प्लेट से उपयोग करने के लिए "slideMargin" प्रॉपर्टी को रखें
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... दस्तावेज़ के अन्य विकल्प सेट करें और फिर दस्तावेज़ को सहेजें
>   document.save();
> ```

**रिटर्न:**
[Storage](../../com.aspose.slides/storage)