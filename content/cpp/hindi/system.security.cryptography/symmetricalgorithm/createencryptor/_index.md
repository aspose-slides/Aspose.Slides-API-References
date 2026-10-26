---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API संदर्भ
description: एल्गोरिद्म ऑब्जेक्ट से जुड़े पैरामीटरों के साथ एन्क्रिप्टर बनाता है।
type: docs
weight: 183
url: /hi/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() विधि


एन्क्रिप्टर बनाता है जो एल्गोरिद्म ऑब्जेक्ट से जुड़े पैरामीटरों के साथ।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```


### Return Value

नया निर्मित एन्क्रिप्टर ऑब्जेक्ट।

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि


स्पष्ट पैरामीटर के साथ एन्क्रिप्टर बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | उपयोग के लिए कुंजी। |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | उपयोग के लिए प्रारम्भिक मान। |

### Return Value

नया निर्मित एन्क्रिप्टर ऑब्जेक्ट।

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [SymmetricAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)