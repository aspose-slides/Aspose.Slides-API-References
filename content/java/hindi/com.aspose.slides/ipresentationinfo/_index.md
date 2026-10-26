---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Information about presentation file
type: docs
url: /hi/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Presentation फ़ाइल के बारे में जानकारी
## Methods

| Method | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | यदि बाइंडेड प्रेज़ेंटेशन एन्क्रिप्टेड है तो True लौटाता है, अन्यथा False। |
| [isPasswordProtected()](#isPasswordProtected--) | यह दर्शाता है कि क्या बाइंडेड प्रेज़ेंटेशन को खोलने के लिए पासवर्ड से संरक्षित किया गया है। |
| [isWriteProtected()](#isWriteProtected--) | यह दर्शाता है कि बाइंडेड प्रेज़ेंटेशन लेखन-प्रोटेक्टेड है या नहीं। |
| [getLoadFormat()](#getLoadFormat--) | बाइंडेड प्रेज़ेंटेशन का फ़ॉर्मेट देता है। |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | खुले पासवर्ड से संरक्षित प्रेज़ेंटेशन के लिए पासवर्ड सही है या नहीं, जाँचता है। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | लिखने-प्रोटेक्टेड प्रेज़ेंटेशन के लिए संशोधन पासवर्ड सही है या नहीं, जाँचता है। |
| [readDocumentProperties()](#readDocumentProperties--) | बाइंडेड प्रेज़ेंटेशन के दस्तावेज़ गुण प्राप्त करता है। |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | बाइंडेड प्रेज़ेंटेशन के गुण अपडेट करता है। |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | बाइंडेड प्रेज़ेंटेशन को स्ट्रीम में लिखता है। |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | बाइंडेड प्रेज़ेंटेशन को फ़ाइल में लिखता है। |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


यदि बाइंडेड प्रेज़ेंटेशन एन्क्रिप्टेड है तो True लौटाता है, अन्यथा False। केवल-पढ़ने योग्य बूलियन।

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


यह दर्शाता है कि क्या बाइंडेड प्रेज़ेंटेशन को खोलने के लिए पासवर्ड से संरक्षित किया गया है।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```


यह दर्शाता है कि बाइंडेड प्रेज़ेंटेशन लेखन-प्रोटेक्टेड है या नहीं।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

यदि प्रेज़ेंटेशन खोलने के लिए पासवर्ड से संरक्षित है, तो प्रॉपर्टी मान NotDefined के बराबर होता है। देखें [NullableBool](../../com.aspose.slides/nullablebool) एनीमरेशन।

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


बाइंडेड प्रेज़ेंटेशन का फ़ॉर्मेट देता है। केवल-पढ़ने योग्य [LoadFormat](../../com.aspose.slides/loadformat)।

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```


खुले पासवर्ड से संरक्षित प्रेज़ेंटेशन के लिए पासवर्ड सही है या नहीं, जाँचता है.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | जाँचने के लिए पासवर्ड। |

--------------------

जब पासवर्ड null या खाली हो, यह विधि false लौटाती है। |

**Returns:**
boolean - True यदि प्रेज़ेंटेशन खुले पासवर्ड से संरक्षित है और पासवर्ड सही है, अन्यथा false।
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


लिखने-प्रोटेक्टेड प्रेज़ेंटेशन के लिए संशोधन पासवर्ड सही है या नहीं, जाँचता है।

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | जाँचने के लिए पासवर्ड। |

--------------------

1. इस विधि को कॉल करने से पहले (\#isWriteProtected.isWriteProtected) प्रॉपर्टी की जाँच करें। 2. जब पासवर्ड null या खाली हो, यह विधि false लौटाती है। |

**Returns:**
boolean - True यदि प्रेज़ेंटेशन लिखने-प्रोटेक्टेड है और पासवर्ड सही है। false अन्यथा।
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```


बाइंडेड प्रेज़ेंटेशन के दस्तावेज़ गुण प्राप्त करता है।

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - दस्तावेज़ गुण [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```


बाइंडेड प्रेज़ेंटेशन के गुण अपडेट करता है।

--------------------

> ```
> यह नमूना दर्शाता है कि कैसे #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) मेथड को कॉल करके
>  #readDocumentProperties.readDocumentProperties मेथड द्वारा लौटाए गए दस्तावेज़ गुणों को अपडेट किया जाए।
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | दस्तावेज़ गुण [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


बाइंडेड प्रेज़ेंटेशन को स्ट्रीम में लिखता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | स्ट्रीम सख्यात्मक और लिखने योग्य होना चाहिए। |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


बाइंडेड प्रेज़ेंटेशन को फ़ाइल में लिखता है।

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| file | java.lang.String | प्रेज़ेंटेशन फ़ाइल। |