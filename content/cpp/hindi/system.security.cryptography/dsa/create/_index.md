---
title: Create()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट DSA एल्गोरिद्म कार्यान्वयन बनाता है।
type: docs
weight: 105
url: /hi/system.security.cryptography/dsa/create/
---
## DSA::Create() विधि

डिफ़ॉल्ट [DSA](../) एल्गोरिद्म कार्यान्वयन बनाता है।

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```

### वापसी मान

[DSA](../) एल्गोरिद्म ऑब्जेक्ट।

## DSA::Create(const String\&) विधि

डिफ़ॉल्ट [DSA](../) एल्गोरिद्म कार्यान्वयन बनाता है।

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | "System.Security.Cryptography.DSACryptoServiceProvider" होना चाहिए। |

### वापसी मान

[DSA](../) एल्गोरिद्म ऑब्जेक्ट।

## DSA::Create(int32_t) विधि

डिफ़ॉल्ट [DSA](../) एल्गोरिद्म कार्यान्वयन विशिष्ट कुंजी आकार के साथ बनाता है।

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | बिट्स में कुंजी आकार। |

## DSA::Create(const DSAParameters\&) विधि

डिफ़ॉल्ट [DSA](../) एल्गोरिद्म कार्यान्वयन विशिष्ट पैरामीटरों के साथ बनाता है।

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```

### आर्ग्यूमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | [DSA](../) एल्गोरिद्म के पैरामीटर। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* क्लास [DSA](../)
* क्लास [String](../../../system/string/)
* स्ट्रक्ट [DSAParameters](../../dsaparameters/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)