---
title: WebDocument
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रस्तुति को वेब फ़ॉर्मेट में सहेजने के लिए एक संक्रमण रूप का प्रतिनिधित्व करता है।
type: docs
url: /hi/com.aspose.slides/webdocument/
---
**विरासत:**
java.lang.Object
```
public class WebDocument
```

वेब फ़ॉर्मेट में सहेजने हेतु प्रस्तुति का परिवर्तन रूप दर्शाता है।
## निर्माता

| Constructor | Description |
| --- | --- |
| [WebDocument(WebDocumentOptions options)](#WebDocument-com.aspose.slides.WebDocumentOptions-) | [WebDocument](../../com.aspose.slides/webdocument) निर्माता। |
## विधियाँ

| Method | Description |
| --- | --- |
| [save()](#save--) | दस्तावेज़ आउटपुट को सहेजता है। |
| [getInput()](#getInput--) | दस्तावेज़ के इनपुट तत्वों (टेम्पलेट) का संग्रह लौटाता है। |
| [getOutput()](#getOutput--) | दस्तावेज़ के आउटपुट तत्वों का संग्रह लौटाता है। |
| [getGlobal()](#getGlobal--) | दस्तावेज़ का वैश्विक भंडारण लौटाता है। |
### WebDocument(WebDocumentOptions options) {#WebDocument-com.aspose.slides.WebDocumentOptions-}
```
public WebDocument(WebDocumentOptions options)
```

[WebDocument](../../com.aspose.slides/webdocument) निर्माता।

**पैरामीटर:**
| Parameter | Type | Description |
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
>   // टेम्प्लेट से उपयोग के लिए "slideMargin" प्रॉपर्टी डालें
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... दस्तावेज़ के अन्य विकल्प सेट करें और फिर दस्तावेज़ सहेजें
>   document.save();
> ```


**रिटर्न:**
[Output](../../com.aspose.slides/output)
### getGlobal() {#getGlobal--}
```
public final Storage getGlobal()
```

दस्तावेज़ का वैश्विक भंडारण लौटाता है। केवल-पढ़ने योग्य [Storage](../../com.aspose.slides/storage).

--------------------

> ```
> Using this (#getGlobal.getGlobal) property (implementation of [Storage](../../com.aspose.slides/storage) interface) a
>   property can be put to use it later in the template:
>   
>   WebDocumentOptions options = new WebDocumentOptions();
> 
>   WebDocument document = new WebDocument(options);
> 
>   // टेम्प्लेट से उपयोग के लिए "slideMargin" प्रॉपर्टी डालें
>   document.getGlobal().put("slideMargin", 10);
> 
>   // ... दस्तावेज़ के अन्य विकल्प सेट करें और फिर दस्तावेज़ सहेजें
>   document.save();
> ```


**रिटर्न:**
[Storage](../../com.aspose.slides/storage)