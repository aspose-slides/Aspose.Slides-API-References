---
title: VerifySignature()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा हैश के हस्ताक्षर को सत्यापित करता है।
type: docs
weight: 40
url: /hi/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method


डेटा हैश के हस्ताक्षर को सत्यापित करता है।

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा के लिए गणना किया गया हैश। |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा के लिए प्राप्त हस्ताक्षर। |

### वापसी मान

यदि हस्ताक्षर वैध है तो True, अन्यथा false।

## संबंधित देखें

* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [RSAPKCS1SignatureDeformatter](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)