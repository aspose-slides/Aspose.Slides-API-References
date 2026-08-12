---
title: Encrypt()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट पैडिंग मोड का उपयोग करके इनपुट डेटा को एन्क्रिप्ट करता है।
type: docs
weight: 53
url: /hi/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

इनपुट डेटा को निर्दिष्ट पैडिंग मोड का उपयोग करके एन्क्रिप्ट करता है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) एरे। |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | पैडिंग मोड। |

### वापसी मान

बाइट एरे फ़ॉर्मेट में एन्क्रिप्टेड डेटा।

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* क्लास [RSAEncryptionPadding](../../rsaencryptionpadding/)
* क्लास [RSA](../)
* नामस्थान [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)