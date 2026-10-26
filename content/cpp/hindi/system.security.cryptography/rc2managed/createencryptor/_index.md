---
title: CreateEncryptor()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: स्पष्ट पैरामीटरों के साथ एन्क्रिप्टर ऑब्जेक्ट बनाता है।
type: docs
weight: 1
url: /hi/system.security.cryptography/rc2managed/createencryptor/
---
## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि


स्पष्ट पैरामीटरों के साथ एन्क्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट एरे रूप में एन्क्रिप्शन कुंजी। |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट एरे रूप में प्रारंभिक मान। |

### वापसी मान

नया बनाया गया एन्क्रिप्टर ऑब्जेक्ट।

## RC2Managed::CreateEncryptor() विधि


एल्गोरिदम ऑब्जेक्ट द्वारा परिभाषित पैरामीटरों के साथ एन्क्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RC2Managed::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) विधि


एल्गोरिदम ऑब्जेक्ट द्वारा परिभाषित पैरामीटरों के साथ एन्क्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* टाइपडेफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICryptoTransform](../../icryptotransform/)
* क्लास [RC2Managed](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)