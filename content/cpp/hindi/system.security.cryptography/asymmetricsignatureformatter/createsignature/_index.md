---
title: CreateSignature()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: निर्दिष्ट डेटा के लिए हस्ताक्षर बनाता है।
type: docs
weight: 1
url: /hi/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) विधि

निर्दिष्ट डेटा के लिए हस्ताक्षर बनाता है।

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) के लिए हैश गणना करने हेतु। |

### वापसी मान

बाइट एरे रूप में गणना किया गया हस्ताक्षर।

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) विधि

निर्दिष्ट हैश मान के लिए हस्ताक्षर बनाता है।

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### आर्ग्युमेंट्स

| परिमाण | प्रकार | विवरण |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | हस्ताक्षर बनाने के लिए उपयोग किया जाने वाला हैश एल्गोरिदम। |

### वापसी मान

बाइट एरे रूप में गणना किया गया हस्ताक्षर।

## संबंधित देखें

* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [AsymmetricSignatureFormatter](../)
* क्लास [HashAlgorithm](../../hashalgorithm/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)