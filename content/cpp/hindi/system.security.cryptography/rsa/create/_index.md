---
title: Create()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डिफॉल्ट RSA एल्गोरिद्म कार्यान्वयन बनाता है।
type: docs
weight: 183
url: /hi/system.security.cryptography/rsa/create/
---
## RSA::Create() विधि


डिफॉल्ट [RSA](../) एल्गोरिद्म कार्यान्वयन बनाता है।

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) विधि


डिफॉल्ट [RSA](../) एल्गोरिद्म कार्यान्वयन बनाता है।

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | यह \"System.Security.Cryptography.RSACryptoServiceProvider\" होना चाहिए। |

## RSA::Create(int32_t) विधि


डिफॉल्ट [RSA](../) एल्गोरिद्म कार्यान्वयन, निर्दिष्ट कुंजी आकार के साथ बनाता है।

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | कुंजी का आकार, बिट्स में। |

## RSA::Create(const RSAParameters\&) विधि


डिफॉल्ट [RSA](../) एल्गोरिद्म कार्यान्वयन, निर्दिष्ट पैरामीटरों के साथ बनाता है।

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | [RSA](../) एल्गोरिद्म के लिए पैरामीटर। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [RSA](../)
* क्लास [String](../../../system/string/)
* स्ट्रक्ट [RSAParameters](../../rsaparameters/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)