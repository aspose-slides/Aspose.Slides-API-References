---
title: ProtectionManager
second_title: Aspose.Slides के लिए Android, Java API रेफ़रेंस के माध्यम से
description: प्रेजेंटेशन पासवर्ड सुरक्षा प्रबंधन।
type: docs
url: /hi/com.aspose.slides/protectionmanager/
---
**विरासत:**
java.lang.Object

**सभी कार्यान्वित इंटरफ़ेस:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

प्रेजेंटेशन पासवर्ड सुरक्षा प्रबंधन।
## मेथड्स

| मेथड | विवरण |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | यह प्रॉपर्टी तभी सार्थक होती है जब प्रेजेंटेशन पासवर्ड से सुरक्षित हो। |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | यह प्रॉपर्टी तभी सार्थक होती है जब प्रेजेंटेशन पासवर्ड से सुरक्षित हो। |
| [isEncrypted()](#isEncrypted--) | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस एन्क्रिप्टेड है या नहीं। |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | यह प्रॉपर्टी तभी सार्थक होती है जब प्रेजेंटेशन फ़ाइल पासवर्ड से सुरक्षित हो और इस फ़ाइल के दस्तावेज़ गुण सार्वजनिक हों। |
| [isWriteProtected()](#isWriteProtected--) | एक मान प्राप्त करता है जो दर्शाता है कि यह प्रेजेंटेशन लिखने से सुरक्षित है या नहीं। |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ प्रेजेंटेशन को एन्क्रिप्ट करता है। |
| [removeEncryption()](#removeEncryption--) | एन्क्रिप्शन को हटाता है। |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ इस प्रेजेंटेशन के लिए लिखने से सुरक्षा सेट करता है। |
| [removeWriteProtection()](#removeWriteProtection--) | इस प्रेजेंटेशन की लिखने से सुरक्षा को हटाता है। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | निर्धारित करता है कि क्या प्रेजेंटेशन संशोधित करने के लिए पासवर्ड से सुरक्षित है। |
| [getEncryptionPassword()](#getEncryptionPassword--) | प्रेजेंटेशन एन्क्रिप्शन के लिए उपयोग किए जाने वाले पासवर्ड को प्राप्त करता है। |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | रीड-ओनली सिफ़ारिश को प्राप्त या सेट करता है। |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | रीड-ओनली सिफ़ारिश को प्राप्त या सेट करता है। |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


यह प्रॉपर्टी तभी सार्थक होती है जब प्रेजेंटेशन पासवर्ड से सुरक्षित हो। यदि true है तो दस्तावेज़ गुण प्रेजेंटेशन फ़ाइल में एन्क्रिप्ट होते हैं। यदि false है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रेजेंटेशन एन्क्रिप्टेड रहता है। पढ़ने/लिखने योग्य बूलियन।

**रिटर्न:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


यह प्रॉपर्टी तभी सार्थक होती है जब प्रेजेंटेशन पासवर्ड से सुरक्षित हो। यदि true है तो दस्तावेज़ गुण प्रेजेंटेशन फ़ाइल में एन्क्रिप्ट होते हैं। यदि false है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रेजेंटेशन एन्क्रिप्टेड रहता है। पढ़ने/लिखने योग्य बूलियन।

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस एन्क्रिप्टेड है या नहीं। केवल-पढ़ने योग्य बूलियन।

मान: true यदि प्रेजेंटेशन एन्क्रिप्टेड फ़ाइल से लोड किया गया था या \#encrypt(String).encrypt(String) मेथड को कॉल किया गया था; अन्यथा, false।

**रिटर्न:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


यह प्रॉपर्टी तभी सार्थक होती है जब प्रेजेंटेशन फ़ाइल पासवर्ड से सुरक्षित हो और इस फ़ाइल के दस्तावेज़ गुण सार्वजनिक हों। true मान का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रेजेंटेशन फ़ाइल से पासवर्ड के उपयोग के बिना लोड हुए हैं। false मान का अर्थ है कि सही पासवर्ड का उपयोग करके संपूर्ण एन्क्रिप्टेड प्रेजेंटेशन लोड हुआ है, केवल दस्तावेज़ गुण नहीं। यदि प्रेजेंटेशन एन्क्रिप्टेड नहीं है तो प्रॉपर्टी मान हमेशा false रहेगा। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं तो प्रॉपर्टी मान हमेशा false रहेगा। यदि Presentation.EncryptDocumentProperties true है तो IsOnlyDocumentPropertiesLoaded प्रॉपर्टी मान हमेशा false रहेगा। केवल-पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


एक मान प्राप्त करता है जो दर्शाता है कि यह प्रेजेंटेशन लिखने से सुरक्षित है या नहीं। केवल-पढ़ने योग्य बूलियन।

**रिटर्न:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


निर्दिष्ट पासवर्ड के साथ प्रेजेंटेशन को एन्क्रिप्ट करता है।

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| encryptionPassword | java.lang.String | पासवर्ड। |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```


एन्क्रिप्शन को हटाता है।
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```


निर्दिष्ट पासवर्ड के साथ इस प्रेजेंटेशन के लिए लिखने से सुरक्षा सेट करता है।

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| password | java.lang.String | पासवर्ड। |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```


इस प्रेजेंटेशन की लिखने से सुरक्षा को हटाता है।

--------------------

> ```
> यह नमूना कोड दर्शाता है कि आप PowerPoint प्रेज़ेंटेशन से लिखने की सुरक्षा कैसे हटाते हैं।
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


निर्धारित करता है कि क्या प्रेजेंटेशन संशोधित करने के लिए पासवर्ड से सुरक्षित है।

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
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| password | java.lang.String | जाँच के लिए पासवर्ड।

1. आपको इस मेथड को कॉल करने से पहले (\#isWriteProtected.isWriteProtected) प्रॉपर्टी जाँचनी चाहिए। 2. जब पासवर्ड null या empty हो, यह मेथड false रिटर्न करता है।

**रिटर्न:**
boolean - True यदि पासवर्ड वैध है; अन्यथा, false।
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```


प्रेजेंटेशन एन्क्रिप्शन के लिए उपयोग किए जाने वाले पासवर्ड को प्राप्त करता है। केवल-पढ़ने योग्य String।

**रिटर्न:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```


रीड-ओनली सिफ़ारिश को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**रिटर्न:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```


रीड-ओनली सिफ़ारिश को प्राप्त या सेट करता है। पढ़ने/लिखने योग्य बूलियन।

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**पैरामीटर:**
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |