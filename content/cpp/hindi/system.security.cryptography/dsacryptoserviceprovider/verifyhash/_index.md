---
title: VerifyHash()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: डेटा हस्ताक्षर की जाँच करता है।
type: docs
weight: 222
url: /hi/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr&, const String&, const ByteArrayPtr&) मेथड

डेटा हस्ताक्षर की जाँच करता है।

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्राप्त डेटा के लिए गणना किया गया हैश। |
| str | const [String](../../../system/string/)\& | प्रयुक्त हैश एल्गोरिदम का नाम। |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्राप्त हस्ताक्षर। |

### रिटर्न वैल्यू

यदि हस्ताक्षर वैध है तो सत्य, अन्यथा असत्य।

## देखें

* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* क्लास [String](../../../system/string/)
* क्लास [DSACryptoServiceProvider](../)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)