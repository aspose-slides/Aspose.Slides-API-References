---
title: VerifySignature()
second_title: Aspose.Slides for C++ API संदर्भ
description: डेटा पर हस्ताक्षर की पुष्टि करता है।
type: docs
weight: 27
url: /hi/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि

डेटा पर हस्ताक्षर की पुष्टि करता है।

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) **rgbSignature** के साथ हस्ताक्षरित। |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा के लिए सत्यापित करने वाला हस्ताक्षर। |

### रिटर्न मान

यदि हस्ताक्षर जांच सफल हो तो true, अन्यथा false।

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) विधि

डेटा पर हस्ताक्षर की पुष्टि करता है। अभी लागू नहीं किया गया है।

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | हैशिंग के लिए उपयोग किया जाने वाला एल्गोरिदम। |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | डेटा के लिए सत्यापित करने वाला हस्ताक्षर। |

### रिटर्न मान

यदि हस्ताक्षर जांच सफल हो तो true, अन्यथा false।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [AsymmetricSignatureDeformatter](../)
* क्लास [HashAlgorithm](../../hashalgorithm/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)