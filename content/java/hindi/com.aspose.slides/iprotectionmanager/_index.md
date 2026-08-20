---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: प्रेजेंटेशन पासवर्ड सुरक्षा प्रबंधन।
type: docs
url: /hi/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

प्रेजेंटेशन पासवर्ड सुरक्षा प्रबंधन।
## विधियां

| विधि | विवरण |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | यह गुण केवल तभी सार्थक है जब प्रेजेंटेशन पासवर्ड से सुरक्षित हो। |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | यह गुण केवल तभी सार्थक है जब प्रेजेंटेशन पासवर्ड से सुरक्षित हो। |
| [isEncrypted()](#isEncrypted--) | यह मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस एन्क्रिप्टेड है या नहीं। |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | यह गुण केवल तभी सार्थक है जब प्रेजेंटेशन फ़ाइल पासवर्ड से सुरक्षित हो और इस फ़ाइल की दस्तावेज़ गुण सार्वजनिक हों। |
| [isWriteProtected()](#isWriteProtected--) | यह मान प्राप्त करता है जो दर्शाता है कि यह प्रेजेंटेशन लेखन संरक्षण वाला है या नहीं। |
| [getEncryptionPassword()](#getEncryptionPassword--) | एन्क्रिप्शन पासवर्ड लौटाता है। |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | रीड-ओनली सिफ़ारिश प्राप्त करता या सेट करता है। |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | रीड-ओनली सिफ़ारिश प्राप्त करता या सेट करता है। |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ प्रेजेंटेशन को एन्क्रिप्ट करता है। |
| [removeEncryption()](#removeEncryption--) | एन्क्रिप्शन को हटाता है। |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ इस प्रेजेंटेशन के लिए लेखन संरक्षण सेट करता है। |
| [removeWriteProtection()](#removeWriteProtection--) | इस प्रेजेंटेशन के लिए लेखन संरक्षण हटाता है। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | निर्धारित करता है कि प्रेजेंटेशन संशोधित करने के लिए पासवर्ड संरक्षित है या नहीं। |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```


यह गुण केवल तभी सार्थक है यदि प्रेजेंटेशन पासवर्ड से सुरक्षित हो। यदि true हो तो दस्तावेज़ गुण प्रेजेंटेशन फ़ाइल में एन्क्रिप्टेड होते हैं। यदि false हो तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रेजेंटेशन एन्क्रिप्टेड रहता है। Read/write boolean.

**Returns:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```


यह गुण केवल तभी सार्थक है यदि प्रेजेंटेशन पासवर्ड से सुरक्षित हो। यदि true हो तो दस्तावेज़ गुण प्रेजेंटेशन फ़ाइल में एन्क्रिप्टेड होते हैं। यदि false हो तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रेजेंटेशन एन्क्रिप्टेड रहता है। Read/write boolean.

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


यह मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस एन्क्रिप्टेड है या नहीं। Read-only boolean.

मान: true यदि प्रेजेंटेशन एन्क्रिप्टेड फ़ाइल से लोड किया गया था या #encrypt(String).encrypt(String) मेथड को कॉल किया गया था; अन्यथा, false।

**Returns:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```


यह गुण केवल तभी सार्थक है जब प्रेजेंटेशन फ़ाइल पासवर्ड से सुरक्षित हो और इस फ़ाइल के दस्तावेज़ गुण सार्वजनिक हों। true मान का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रेजेंटेशन फ़ाइल से पासवर्ड के बिना लोड होते हैं। false मान का अर्थ है कि सही पासवर्ड का उपयोग करके संपूर्ण एन्क्रिप्टेड प्रेजेंटेशन लोड होता है, केवल दस्तावेज़ गुण नहीं। यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो गुण का मान हमेशा false रहेगा। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं तो गुण का मान हमेशा false रहेगा। यदि PresentationEx.EncryptDocumentProperties true है तो IsOnlyDocumentPropertiesLoaded गुण का मान हमेशा false रहेगा। Read-only boolean.

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```


यह मान प्राप्त करता है जो दर्शाता है कि यह प्रेजेंटेशन लेखन संरक्षण वाला है या नहीं। Read-only boolean.

**Returns:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```


एन्क्रिप्शन पासवर्ड लौटाता है। Read-only String.

**Returns:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```


रीड-ओनली सिफ़ारिश प्राप्त करता या सेट करता है। Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Returns:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


रीड-ओनली सिफ़ारिश प्राप्त करता या सेट करता है। Read/write boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```


निर्दिष्ट पासवर्ड के साथ प्रेजेंटेशन को एन्क्रिप्ट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encryptionPassword | java.lang.String | पासवर्ड। |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```


एन्क्रिप्शन को हटाता है।

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```


निर्दिष्ट पासवर्ड के साथ इस प्रेजेंटेशन के लिए लेखन संरक्षण सेट करता है।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | java.lang.String | पासवर्ड। |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```


इस प्रेजेंटेशन के लिए लेखन संरक्षण हटाता है।

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


निर्धारित करता है कि प्रेजेंटेशन संशोधित करने के लिए पासवर्ड संरक्षित है या नहीं।

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | java.lang.String | जाँच के लिए पासवर्ड।

--------------------

1. आपको इस विधि को कॉल करने से पहले (#isWriteProtected.isWriteProtected) गुण की जाँच करनी चाहिए। 2. जब पासवर्ड null या खाली हो, यह विधि false लौटाती है।

**Returns:**
boolean - True if the password is valid; otherwise, false.