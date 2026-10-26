---
title: CreateDecryptor()
second_title: C++ के लिए Aspose.Slides API रेफ़रेंस
description: स्पष्ट पैरामीटर के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।
type: docs
weight: 14
url: /hi/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) मेथड

स्पष्ट पैरामीटर के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट ऐरे रूप में एन्क्रिप्शन कुंजी। |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | बाइट ऐरे रूप में प्रारंभिक मान। |

### रिटर्न मान

नया बनाया गया डिक्रिप्टर ऑब्जेक्ट।

## RijndaelManaged::CreateDecryptor() मेथड

एल्गोरिद्म ऑब्जेक्ट द्वारा परिभाषित पैरामीटर के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) मेथड

एल्गोरिद्म ऑब्जेक्ट द्वारा परिभाषित पैरामीटर के साथ डिक्रिप्टर ऑब्जेक्ट बनाता है।

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## देखें

* टाइपडेफ [SharedPtr](../../../system/sharedptr/)
* टाइपडेफ [ArrayPtr](../../../system/arrayptr/)
* क्लास [ICryptoTransform](../../icryptotransform/)
* क्लास [RijndaelManaged](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)