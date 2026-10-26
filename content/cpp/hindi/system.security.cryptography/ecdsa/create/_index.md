---
title: Create()
second_title: Aspose.Slides for C++ API संदर्भ
description: डिफ़ॉल्ट ECDSA एल्गोरिद्म इम्प्लीमेंटेशन बनाता है।
type: docs
weight: 131
url: /hi/system.security.cryptography/ecdsa/create/
---
## ECDsa::Create() मेथड

डिफ़ॉल्ट ECDSA एल्गोरिद्म इम्प्लीमेंटेशन बनाता है।

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create()
```

### रिटर्न वैल्यू

ECDSA algorithm object.

## ECDsa::Create(const ECCurve\&) मेथड

निर्दिष्ट वक्र पर नए बनाए गए कुंजी के साथ डिफ़ॉल्ट ECDSA एल्गोरिद्म इम्प्लीमेंटेशन बनाता है।

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECCurve &curve)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | कुंजी निर्माण के लिए उपयोग किया जाने वाला वक्र। |

### रिटर्न वैल्यू

ECDSA algorithm object.

## ECDsa::Create(const ECParameters\&) मेथड

निर्दिष्ट पैरामीटर का उपयोग करके डिफ़ॉल्ट ECDSA एल्गोरिद्म इम्प्लीमेंटेशन बनाता है।

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const ECParameters &parameters)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | कुंजी को दर्शाने वाले पैरामीटर। |

### रिटर्न वैल्यू

ECDSA algorithm object.

## ECDsa::Create(const String\&) मेथड

निर्दिष्ट ECDSA एल्गोरिद्म इम्प्लीमेंटेशन बनाता है।

```cpp
static SharedPtr<ECDsa> System::Security::Cryptography::ECDsa::Create(const String &algorithm)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| algorithm | const [String](../../../system/string/)\& | एल्गोरिद्म का नाम। |

### रिटर्न वैल्यू

ECDSA algorithm object.

## देखें भी

* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [ECDsa](../)
* क्लास [String](../../../system/string/)
* स्ट्रक्ट [ECCurve](../../eccurve/)
* स्ट्रक्ट [ECParameters](../../ecparameters/)
* नामस्थान [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)