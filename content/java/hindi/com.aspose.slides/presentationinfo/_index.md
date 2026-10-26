---
title: PresentationInfo
second_title: Aspose.Slides के लिए जावा API संदर्भ
description: प्रस्तुति फ़ाइल की जानकारी
type: docs
url: /hi/com.aspose.slides/presentationinfo/
---
**विरासत:**
java.lang.Object

**सभी लागू इंटरफ़ेस:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

प्रस्तुति फ़ाइल की जानकारी
## विधियाँ

| मेथड | विवरण |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | यदि बाइंडेड प्रस्तुति एन्क्रिप्टेड है तो True लौटाता है, अन्यथा False। |
| [isPasswordProtected()](#isPasswordProtected--) | एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति को खोलने के लिए पासवर्ड द्वारा सुरक्षित किया गया है या नहीं। |
| [isWriteProtected()](#isWriteProtected--) | एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति लिखने के लिए सुरक्षित है या नहीं। |
| [getLoadFormat()](#getLoadFormat--) | बाइंडेड प्रस्तुति का फ़ॉर्मेट प्राप्त करता है। |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | जाँचता है कि खुला पासवर्ड के साथ सुरक्षित प्रस्तुति के लिए पासवर्ड सही है या नहीं। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | जाँचता है कि लिखने के लिए सुरक्षित प्रस्तुति के संशोधन पासवर्ड सही है या नहीं। |
| [readDocumentProperties()](#readDocumentProperties--) | बाइंडेड प्रस्तुति के दस्तावेज़ गुण प्राप्त करता है। |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | बाइंडेड प्रस्तुति के गुण अपडेट करता है। |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | बाइंडेड प्रस्तुति को स्ट्रीम में लिखता है। |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | बाइंडेड प्रस्तुति को फ़ाइल में लिखता है। |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


यदि बाइंडेड प्रस्तुति एन्क्रिप्टेड है तो True लौटाता है, अन्यथा False। केवल-पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति को खोलने के लिए पासवर्ड द्वारा सुरक्षित किया गया है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**रिटर्न:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```


एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रस्तुति लिखने के लिए सुरक्षित है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

यदि प्रस्तुति को खोलने के लिए पासवर्ड द्वारा सुरक्षित किया गया है, तो प्रॉपर्टी मूल्य NotDefined के बराबर होता है।

**रिटर्न:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


बाइंडेड प्रस्तुति का फ़ॉर्मेट प्राप्त करता है। केवल-पढ़ने योग्य [LoadFormat](../../com.aspose.slides/loadformat)।

**रिटर्न:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```


जाँचता है कि खुला पासवर्ड से सुरक्षित प्रस्तुति के लिए पासवर्ड सही है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | java.lang.String | जाँचने के लिए पासवर्ड। |

--------------------

जब पासवर्ड null या empty हो, यह मेथड false लौटाता है। |

**रिटर्न:**
boolean - True यदि प्रस्तुति खुला पासवर्ड से सुरक्षित है और पासवर्ड सही है और false अन्यथा।
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


जाँचता है कि संशोधन पासवर्ड लिखने के लिए सुरक्षित प्रस्तुति के लिए सही है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | java.lang.String | जाँचने के लिए पासवर्ड। |

--------------------

1. आपको इस मेथड को कॉल करने से पहले (\#isWriteProtected.isWriteProtected) प्रॉपर्टी जाँचनी चाहिए। 2. जब पासवर्ड null या empty हो, यह मेथड false लौटाता है। |

**रिटर्न:**
boolean - True यदि प्रस्तुति लिखने के लिए सुरक्षित है और पासवर्ड सही है। False अन्यथा।
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```


बाइंडेड प्रस्तुति के दस्तावेज़ गुण प्राप्त करता है।

**रिटर्न:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```


बाइंडेड प्रस्तुति के गुण अपडेट करता है।

--------------------

> ```
> यह उदाहरण दिखाता है कि #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) मेथड को कैसे कॉल किया जाए
>  #readDocumentProperties.readDocumentProperties मेथड के कॉल द्वारा प्राप्त दस्तावेज़ गुणों को अपडेट करें।
>  
  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
>  ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```


बाइंडेड प्रस्तुति को स्ट्रीम में लिखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम को seekable और writable होना चाहिए। |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```


बाइंडेड प्रस्तुति को फ़ाइल में लिखता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | प्रस्तुति फ़ाइल। |