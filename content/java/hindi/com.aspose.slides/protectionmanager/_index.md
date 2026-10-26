---
title: ProtectionManager
second_title: Aspose.Slides के लिए Java API संदर्भ
description: प्रस्तुति पासवर्ड सुरक्षा प्रबंधन।
type: docs
url: /hi/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

प्रस्तुति पासवर्ड सुरक्षा प्रबंधन.
## विधियां

| विधि | विवरण |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | यह प्रॉपर्टी तभी अर्थपूर्ण है जब प्रस्तुति पासवर्ड-संरक्षित हो। |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | यह प्रॉपर्टी तभी अर्थपूर्ण है जब प्रस्तुति पासवर्ड-संरक्षित हो। |
| [isEncrypted()](#isEncrypted--) | यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस एन्क्रिप्टेड है या नहीं। |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | यह प्रॉपर्टी तभी अर्थपूर्ण है जब प्रस्तुति फ़ाइल पासवर्ड-संरक्षित हो और इस फ़ाइल की दस्तावेज़ गुण सार्वजनिक हों। |
| [isWriteProtected()](#isWriteProtected--) | यह दर्शाने वाला मान प्राप्त करता है कि यह प्रस्तुति लिखने से संरक्षित है या नहीं। |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ प्रस्तुति को एन्क्रिप्ट करता है। |
| [removeEncryption()](#removeEncryption--) | एन्क्रिप्शन को हटाता है। |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | निर्दिष्ट पासवर्ड के साथ इस प्रस्तुति के लिए लिखने की सुरक्षा सेट करता है। |
| [removeWriteProtection()](#removeWriteProtection--) | इस प्रस्तुति के लिए लिखने की सुरक्षा हटाता है। |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | निर्धारित करता है कि प्रस्तुति संशोधित करने के लिए पासवर्ड-संरक्षित है या नहीं। |
| [getEncryptionPassword()](#getEncryptionPassword--) | प्रस्तुति एन्क्रिप्शन के लिए उपयोग किया गया पासवर्ड प्राप्त करता है। |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | रीड-ओनली अनुशंसा प्राप्त करता है या सेट करता है। |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | रीड-ओनली अनुशंसा प्राप्त करता है या सेट करता है। |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

यह प्रॉपर्टी तभी अर्थपूर्ण है जब प्रस्तुति पासवर्ड-संरक्षित हो। यदि true है तो दस्तावेज़ गुण प्रस्तुति फ़ाइल में एन्क्रिप्ट होते हैं। यदि false है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रस्तुति एन्क्रिप्ट रहती है। पढ़ें/लिखें बूलियन।

**वापसी:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

यह प्रॉपर्टी तभी अर्थपूर्ण है जब प्रस्तुति पासवर्ड-संरक्षित हो। यदि true है तो दस्तावेज़ गुण प्रस्तुति फ़ाइल में एन्क्रिप्ट होते हैं। यदि false है तो दस्तावेज़ गुण सार्वजनिक होते हैं जबकि प्रस्तुति एन्क्रिप्ट रहती है। पढ़ें/लिखें बूलियन।

**पैरामीटर:**
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

यह दर्शाने वाला मान प्राप्त करता है कि यह इंस्टेंस एन्क्रिप्टेड है या नहीं। केवल-पढ़ने योग्य बूलियन।

मान: true यदि प्रस्तुति एन्क्रिप्टेड फ़ाइल से लोड की गई हो या \#encrypt(String).encrypt(String) मेथड को कॉल किया गया हो; अन्यथा false।

**वापसी:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

यह प्रॉपर्टी तभी अर्थपूर्ण है जब प्रस्तुति फ़ाइल पासवर्ड-संरक्षित हो और इस फ़ाइल के दस्तावेज़ गुण सार्वजनिक हों। true का अर्थ है कि केवल दस्तावेज़ गुण एन्क्रिप्टेड प्रस्तुति फ़ाइल से पासवर्ड के बिना लोड किए गए हैं। false का अर्थ है कि पूरी एन्क्रिप्टेड प्रस्तुति सही पासवर्ड के साथ लोड की गई है, केवल दस्तावेज़ गुण नहीं। यदि प्रस्तुति एन्क्रिप्टेड नहीं है तो प्रॉपर्टी हमेशा false होगी। यदि एन्क्रिप्टेड फ़ाइल के दस्तावेज़ गुण सार्वजनिक नहीं हैं तो प्रॉपर्टी हमेशा false होगी। यदि Presentation.EncryptDocumentProperties true है तो IsOnlyDocumentPropertiesLoaded प्रॉपर्टी हमेशा false होगी। केवल-पढ़ने योग्य बूलियन।

**वापसी:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

यह दर्शाने वाला मान प्राप्त करता है कि यह प्रस्तुति लिखने से संरक्षित है या नहीं। केवल-पढ़ने योग्य बूलियन।

**वापसी:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

निर्दिष्ट पासवर्ड के साथ प्रस्तुति को एन्क्रिप्ट करता है।

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
| पैरामीटर | प्रकार | विवरण |
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

निर्दिष्ट पासवर्ड के साथ इस प्रस्तुति के लिए लिखने की सुरक्षा सेट करता है।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| password | java.lang.String | पासवर्ड। |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

इस प्रस्तुति के लिए लिखने की सुरक्षा हटाता है।

--------------------

> ```
> यह नमूना कोड दिखाता है कि कैसे एक PowerPoint प्रस्तुति से लिखने की सुरक्षा हटाई जाए।
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

निर्धारित करता है कि प्रस्तुति संशोधित करने के लिए पासवर्ड-संरक्षित है या नहीं।

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

1. इस मेथड को कॉल करने से पहले आपको (\#isWriteProtected.isWriteProtected) प्रॉपर्टी जांचनी चाहिए। 2. जब पासवर्ड null या खाली हो, यह मेथड false लौटाता है। |

**वापसी:**
boolean - true यदि पासवर्ड मान्य है; अन्यथा false।
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

प्रस्तुति एन्क्रिप्शन के लिए उपयोग किया गया पासवर्ड प्राप्त करता है। केवल-पढ़ने योग्य स्ट्रिंग।

**वापसी:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

रीड-ओनली अनुशंसा प्राप्त करता है या सेट करता है। पढ़ें/लिखें बूलियन।

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

**वापसी:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

रीड-ओनली अनुशंसा प्राप्त करता है या सेट करता है। पढ़ें/लिखें बूलियन।

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
| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| value | boolean |  |