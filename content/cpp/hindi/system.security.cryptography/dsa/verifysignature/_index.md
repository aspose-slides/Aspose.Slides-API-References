---
title: VerifySignature()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: निर्दिष्ट डेटा के लिए DSA हस्ताक्षर को सत्यापित करें।
type: docs
weight: 14
url: /hi/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) मेथड

सत्यापित करें [DSA](../) हस्ताक्षर निर्दिष्ट डेटा के लिए।

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```

### Arguments

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) को **rgb_signature** के साथ हस्ताक्षर किया गया। |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) हस्ताक्षर। |

### रिटर्न मान

true - यदि **rgb_signature** [DSA](../) हस्ताक्षर से मेल खाता है जो **rgb_hash** पर गणना किया गया है, अन्यथा - false।

## संबंधित देखें

* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* क्लास [DSA](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)