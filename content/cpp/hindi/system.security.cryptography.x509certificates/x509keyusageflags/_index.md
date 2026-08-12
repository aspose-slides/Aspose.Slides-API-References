---
title: X509KeyUsageFlags
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट करता है कि प्रमाणपत्र कुंजी का उपयोग कैसे किया जा सकता है।
type: docs
weight: 274
url: /hi/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags एनम

प्रमाणपत्र कुंजी का उपयोग कैसे किया जा सकता है, यह निर्धारित करता है।

```cpp
enum class X509KeyUsageFlags : int32_t
```

### मान

| नाम | मान | विवरण |
| --- | --- | --- |
| None | 0 | कोई कुंजी उपयोग पैरामीटर नहीं। |
| EncipherOnly | 1 | कुंजी को केवल एन्क्रिप्शन के लिए उपयोग किया जा सकता है। |
| CrlSign | 2 | कुंजी का उपयोग प्रमाणपत्र रद्दीकरण सूची पर हस्ताक्षर करने के लिए किया जा सकता है। |
| KeyCertSign | 4 | कुंजी का उपयोग प्रमाणपत्रों पर हस्ताक्षर करने के लिए किया जा सकता है। |
| KeyAgreement | 8 | कुंजी का उपयोग कुंजी समझौता निर्धारित करने के लिए किया जा सकता है। |
| DataEncipherment | 16 | कुंजी का उपयोग डेटा एन्क्रिप्शन के लिए किया जा सकता है। |
| KeyEncipherment | 32 | कुंजी का उपयोग कुंजी एन्क्रिप्शन के लिए किया जा सकता है। |
| NonRepudiation | 64 | कुंजी का उपयोग प्रमाणीकरण के लिए किया जा सकता है। |
| DigitalSignature | 128 | कुंजी को डिजिटल हस्ताक्षर के रूप में उपयोग किया जा सकता है। |
| DecipherOnly | 32768 | कुंजी को केवल डिक्रिप्शन के लिए उपयोग किया जा सकता है। |

## देखें

* नामस्थान [System::Security::Cryptography::X509Certificates](../)
* पुस्तकालय [Aspose.Slides](../../)