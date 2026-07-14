---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
type: docs
url: /hi/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

प्रस्तुति फ़ाइल के बारे में जानकारी
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | यदि बाइंडेड प्रेजेंटेशन एन्क्रिप्टेड है तो True प्राप्त करता है, अन्यथा False। |
| [isPasswordProtected()](#isPasswordProtected--) | एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रेजेंटेशन को खोलने के लिए पासवर्ड द्वारा संरक्षित किया गया है या नहीं। |
| [isWriteProtected()](#isWriteProtected--) | एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रेजेंटेशन लिखने से संरक्षित है या नहीं। |
| [getLoadFormat()](#getLoadFormat--) | बाइंडेड प्रेजेंटेशन का फ़ॉर्मेट प्राप्त करता है। |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | जाँचता है कि खुलने वाले पासवर्ड के साथ संरक्षित प्रेजेंटेशन के लिए पासवर्ड सही है या नहीं। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | जाँचता है कि संशोधित करने के पासवर्ड लिखने से सुरक्षित प्रेजेंटेशन के लिए सही है या नहीं। |
| [readDocumentProperties()](#readDocumentProperties--) | बाइंडेड प्रेजेंटेशन के दस्तावेज़ गुण प्राप्त करता है। |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | बाइंडेड प्रेजेंटेशन के गुण अपडेट करता है। |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | बाइंडेड प्रेजेंटेशन को स्ट्रीम में लिखता है। |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | बाइंडेड प्रेजेंटेशन को फ़ाइल में लिखता है। |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

यदि बाइंडेड प्रेजेंटेशन एन्क्रिप्टेड है तो True प्राप्त करता है, अन्यथा False। केवल पढ़ने योग्य boolean।

**रिटर्न:**  
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रेजेंटेशन को खोलने के लिए पासवर्ड द्वारा संरक्षित किया गया है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**रिटर्न:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

एक मान प्राप्त करता है जो दर्शाता है कि बाइंडेड प्रेजेंटेशन लिखने से संरक्षित है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

यदि प्रेजेंटेशन को खोलने के लिए पासवर्ड द्वारा सुरक्षित किया गया है, तो प्रॉपर्टी मान NotDefined के बराबर होगा। देखें [NullableBool](../../com.aspose.slides/nullablebool) enumeration।

**रिटर्न:**  
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

बाइंडेड प्रेजेंटेशन का फ़ॉर्मेट प्राप्त करता है। केवल पढ़ने योग्य [LoadFormat](../../com.aspose.slides/loadformat)।

**रिटर्न:**  
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

जाँचता है कि खुलने वाले पासवर्ड के साथ संरक्षित प्रेजेंटेशन के लिए पासवर्ड सही है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | java.lang.String | जाँचने के लिए पासवर्ड। |

--------------------

जब पासवर्ड null या खाली हो, यह मेथड false लौटाता है। |

**रिटर्न:**  
boolean - True यदि प्रेजेंटेशन खुलने वाले पासवर्ड से सुरक्षित है और पासवर्ड सही है, तथा अन्यथा false।
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

जाँचता है कि संशोधित करने के पासवर्ड लिखने से सुरक्षित प्रेजेंटेशन के लिए सही है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
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

1. इस मेथड को कॉल करने से पहले (\#isWriteProtected.isWriteProtected) प्रॉपर्टी की जाँच करनी चाहिए। 2. जब पासवर्ड null या खाली हो, यह मेथड false लौटाता है। |

**रिटर्न:**  
boolean - True यदि प्रेजेंटेशन लिखने से सुरक्षित है और पासवर्ड सही है। False अन्यथा।
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

बाइंडेड प्रेजेंटेशन के दस्तावेज़ गुण प्राप्त करता है।

**रिटर्न:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - दस्तावेज़ गुण [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

बाइंडेड प्रेजेंटेशन के गुण अपडेट करता है।

--------------------

> ``` 
> यह नमूना दिखाता है कि कैसे #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) मेथड को कॉल किया जाए ताकि
>  दस्तावेज़ गुण को अपडेट करें जो #readDocumentProperties.readDocumentProperties मेथड के कॉल द्वारा लौटाए गए हैं।
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | दस्तावेज़ गुण [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

बाइंडेड प्रेजेंटेशन को स्ट्रीम में लिखता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम seekable और writable होना चाहिए। |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

बाइंडेड प्रेजेंटेशन को फ़ाइल में लिखता है।

**पैरामीटर:**  
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| file | java.lang.String | प्रेजेंटेशन फ़ाइल। |