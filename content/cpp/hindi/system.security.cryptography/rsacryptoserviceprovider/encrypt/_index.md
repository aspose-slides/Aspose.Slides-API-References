---
title: Encrypt()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: संदेश को एन्क्रिप्ट करता है। लागू नहीं किया गया है।
type: docs
weight: 118
url: /hi/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) method


संदेश को एन्क्रिप्ट करता है। लागू नहीं किया गया है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) को एन्क्रिप्ट करने के लिए। |
| use_oaep | **bool** | OAEP पैडिंग उपयोग करने के लिए true, PKCS#1 v1.5 पैडिंग उपयोग करने के लिए false। |

### रिटर्न वैल्यू

एन्क्रिप्टेड डेटा ऐरे।

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method


निर्दिष्ट पैडिंग मोड का उपयोग करके इनपुट डेटा को एन्क्रिप्ट करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```


### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) ऐरे को एन्क्रिप्ट करने के लिए। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | पैडिंग मोड। |

### रिटर्न वैल्यू

बाइट ऐरे फ़ॉर्मेट में एन्क्रिप्टेड डेटा।

## संबंधित देखें

* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [RSACryptoServiceProvider](../)
* क्लास [RSAEncryptionPadding](../../rsaencryptionpadding/)
* नामस्थान [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)