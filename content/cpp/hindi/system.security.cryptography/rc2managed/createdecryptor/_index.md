---
title: CreateDecryptor()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्पष्ट पैरामीटर के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।
type: docs
weight: 14
url: /hi/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि

स्पष्ट पैरामीटर के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट ऐरे स्वरूप में एन्क्रिप्शन कुंजी। |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट ऐरे स्वरूप में प्रारंभिक मान। |

### रिटर्न मान

नया निर्मित डिक्रिप्टर ऑब्जेक्ट।

## RC2Managed::CreateDecryptor() विधि

एल्गोरिद्म ऑब्जेक्ट द्वारा परिभाषित पैरामीटर्स के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि

एल्गोरिद्म ऑब्जेक्ट द्वारा परिभाषित पैरामीटर्स के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## संबंधित देखें

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICryptoTransform](../../icryptotransform/)
* क्लास [RC2Managed](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)