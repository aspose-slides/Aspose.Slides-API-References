---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API संदर्भ
description: स्पष्ट पैरामीटर्स के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।
type: docs
weight: 14
url: /hi/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि

स्पष्ट पैरामीटर्स के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### आर्ग्युमेंट

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट एरे रूप में एन्क्रिप्शन कुंजी। |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट एरे रूप में प्रारम्भिक मान। |

### रिटर्न मान

नया निर्मित डिक्रिप्टर ऑब्जेक्ट।

## TripleDESManaged::CreateDecryptor() विधि

एल्गोरिद्म ऑब्जेक्ट द्वारा परिभाषित पैरामीटर्स के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि

एल्गोरिद्म ऑब्जेक्ट द्वारा परिभाषित पैरामीटर्स के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICryptoTransform](../../icryptotransform/)
* क्लास [TripleDESManaged](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)