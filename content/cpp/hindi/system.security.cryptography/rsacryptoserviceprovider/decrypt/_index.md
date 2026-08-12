---
title: Decrypt()
second_title: Aspose.Slides for C++ API संदर्भ
description: संदेश को डिक्रिप्ट करता है। लागू नहीं किया गया है।
type: docs
weight: 105
url: /hi/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) विधि

संदेश को डिक्रिप्ट करता है। लागू नहीं किया गया है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) को डिक्रिप्ट करने के लिए। |
| use_oaep | **bool** | OAEP पैडिंग का उपयोग करने के लिए true, PKCS#1 v1.5 पैडिंग का उपयोग करने के लिए false। |

### रिटर्न वैल्यू

डिक्रिप्ट किया गया डेटा एरे।

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) विधि

निर्दिष्ट पैडिंग मोड का उपयोग करके इनपुट डेटा को डिक्रिप्ट करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### आर्ग्युमेंट

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) एरे को डिक्रिप्ट करने के लिए। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | पैडिंग मोड। |

### रिटर्न वैल्यू

बाइट एरे फॉर्मेट में डिक्रिप्ट किया गया डेटा।

## देखें

* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [RSACryptoServiceProvider](../)
* क्लास [RSAEncryptionPadding](../../rsaencryptionpadding/)
* नामस्थान [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)