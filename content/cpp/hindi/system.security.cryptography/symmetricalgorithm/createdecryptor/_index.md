---
title: CreateDecryptor()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: ऐसे पैरामीटरों के साथ डिक्रिप्टर बनाता है जो एल्गोरिदम ऑब्जेक्ट से जुड़े होते हैं।
type: docs
weight: 196
url: /hi/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() मेथड


Creates decryptor with parameters associated with algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### रिटर्न वैल्यू

नया बना डिक्रिप्टर ऑब्जेक्ट।

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) मेथड


Creates decryptor with explicit parameters.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | उपयोग करने के लिये कुंजी। |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | उपयोग करने के लिये प्रारम्भिक मान। |

### रिटर्न वैल्यू

नया बना डिक्रिप्टर ऑब्जेक्ट।

## संबंधित देखें

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICryptoTransform](../../icryptotransform/)
* क्लास [SymmetricAlgorithm](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)