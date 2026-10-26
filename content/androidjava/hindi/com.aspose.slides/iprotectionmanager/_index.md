---
title: IProtectionManager
second_title: Aspose.Slides for Android के लिए जावा API रेफ़रेंस
description: प्रस्तुति पासवर्ड संरक्षण प्रबंधन।
type: docs
url: /hi/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

प्रस्तुति पासवर्ड संरक्षण प्रबंधन।
## विधियाँ

| विधि | विवरण |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | यदि प्रस्तुति पासवर्ड संरक्षित है तो यह गुण सार्थक होता है। |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | यदि प्रस्तुति पासवर्ड संरक्षित है तो यह गुण सार्थक होता है। |
| [isEncrypted()](#isEncrypted--) | एक मान प्राप्त करता है जो यह इंगित करता है कि यह उदाहरण एन्क्रिप्टेड है या नहीं। |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | यदि प्रस्तुति फ़ाइल पासवर्ड संरक्षित है और इस फ़ाइल की दस्तावेज़ गुण सार्वजनिक हैं तो यह गुण सार्थक होता है। |
| [isWriteProtected()](#isWriteProtected--) | एक मान प्राप्त करता है जो यह दर्शाता है कि यह प्रस्तुति लिखने से संरक्षित है या नहीं। |
| [getEncryptionPassword()](#getEncryptionPassword--) | एन्क्रिप्शन पासवर्ड लौटाता है। |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | पढ़ने-केवल अनुशंसा प्राप्त करता है या सेट करता है। |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | पढ़ने-केवल अनुशंसा प्राप्त करता है या सेट करता है। |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ प्रस्तुति को एन्क्रिप्ट करता है। |
| [removeEncryption()](#removeEncryption--) | एन्क्रिप्शन को हटाता है। |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ इस प्रस्तुति के लिए लिखने की सुरक्षा सेट करता है। |
| [removeWriteProtection()](#removeWriteProtection--) | इस प्रस्तुति के लिए लिखने की सुरक्षा हटाता है। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | निर्धारित करता है कि प्रस्तुति को संशोधित करने के लिए पासवर्ड द्वारा संरक्षित है या नहीं। |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```


यदि प्रस्तुति पासवर्ड संरक्षित है तो यह गुण सार्थक होता है। यदि सत्य है तो दस्तावेज़ गुण प्रस्तुति फ़ाइल में एन्क्रिप्टेड होते हैं। यदि असत्य है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रस्तुति एन्क्रिप्टेड रहती है। पढ़ें/लिखें बूलियन।

**परिणाम:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```


यदि प्रस्तुति पासवर्ड संरक्षित है तो यह गुण सार्थक होता है। यदि सत्य है तो दस्तावेज़ गुण प्रस्तुति फ़ाइल में एन्क्रिप्टेड होते हैं। यदि असत्य है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रस्तुति एन्क्रिप्टेड रहती है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


एक मान प्राप्त करता है जो यह इंगित करता है कि यह उदाहरण एन्क्रिप्टेड है या नहीं। केवल-पढ़ने-योग्य बूलियन।

मान: सत्य यदि प्रस्तुति को एन्क्रिप्टेड फ़ाइल से लोड किया गया हो या #encrypt(String).encrypt(String) मेथड को कॉल किया गया हो; अन्यथा, असत्य।

**परिणाम:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```


यदि प्रस्तुति फ़ाइल पासवर्ड संरक्षित है और इस फ़ाइल की दस्तावेज़ गुण सार्वजनिक हैं तो यह गुण सार्थक होता है। सत्य मान का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रस्तुति फ़ाइल से पासवर्ड के बिना लोड किए गए हैं। असत्य मान का अर्थ है कि पूरी एन्क्रिप्टेड प्रस्तुति सही पासवर्ड के साथ लोड की गई है, केवल दस्तावेज़ गुण नहीं। यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो यह गुण हमेशा असत्य रहेगा। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं तो यह गुण हमेशा असत्य रहेगा। यदि PresentationEx.EncryptDocumentProperties सत्य है तो IsOnlyDocumentPropertiesLoaded गुण हमेशा असत्य रहेगा। केवल-पढ़ने-योग्य बूलियन।

**परिणाम:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```


एक मान प्राप्त करता है जो यह दर्शाता है कि यह प्रस्तुति लिखने से संरक्षित है या नहीं। केवल-पढ़ने-योग्य बूलियन।

**परिणाम:**  
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```


एन्क्रिप्शन पासवर्ड लौटाता है। केवल-पढ़ने-योग्य स्ट्रिंग।

**परिणाम:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```


पढ़ने-केवल अनुशंसा प्राप्त करता है या सेट करता है। पढ़ें/लिखें बूलियन।

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**परिणाम:**  
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


पढ़ने-केवल अनुशंसा प्राप्त करता है या सेट करता है। पढ़ें/लिखें बूलियन।

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```


निर्दिष्ट पासवर्ड के साथ प्रस्तुति को एन्क्रिप्ट करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
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


निर्दिष्ट पासवर्ड के साथ इस प्रस्तुति के लिए लिखने की सुरक्षा सेट करता है।

**पैरामीटर:**  
| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| password | java.lang.String | पासवर्ड। |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```


इस प्रस्तुति के लिए लिखने की सुरक्षा हटाता है।
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


निर्धारित करता है कि प्रस्तुति को संशोधित करने के लिए पासवर्ड द्वारा संरक्षित है या नहीं।

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

1. इस मेथड को कॉल करने से पहले आपको (\#isWriteProtected.isWriteProtected) गुण की जांच करनी चाहिए। 2. जब पासवर्ड null या खाली हो, यह मेथड false लौटाता है।

**परिणाम:**  
boolean - यदि पासवर्ड वैध है तो सत्य; अन्यथा, असत्य।