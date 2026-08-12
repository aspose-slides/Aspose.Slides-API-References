---
title: VerifyData()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट डेटा के हस्ताक्षर की वैधता की जाँच करता है।
type: docs
weight: 170
url: /hi/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) मेथड

निर्दिष्ट डेटा का हस्ताक्षर वैध है, यह सत्यापित करता है।

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षरित डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) मेथड

निर्दिष्ट डेटा का हस्ताक्षर वैध है, यह सत्यापित करता है।

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षरित डेटा। |
| offset | **int32_t** | **data** में ऑफ़सेट। |
| count | **int32_t** | हैश करने के लिए बाइट्स की संख्या। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) मेथड

निर्दिष्ट बाइनरी स्ट्रीम का हस्ताक्षर वैध है, यह सत्यापित करता है।

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | हस्ताक्षरित डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) मेथड

निर्दिष्ट डेटा का हस्ताक्षर वैध है, यह सत्यापित करता है।

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षरित डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) मेथड

निर्दिष्ट डेटा का हस्ताक्षर वैध है, यह सत्यापित करता है।

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षरित डेटा। |
| offset | **int32_t** | **data** में ऑफ़सेट। |
| count | **int32_t** | हैश करने के लिए बाइट्स की संख्या। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) मेथड

निर्दिष्ट बाइनरी स्ट्रीम का हस्ताक्षर वैध है, यह सत्यापित करता है।

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| परामीटर | प्रकार | विवरण |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | हस्ताक्षरित डेटा। |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | हस्ताक्षर डेटा। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिदम। यदि हस्ताक्षर वैध है तो true लौटाएँ, अन्यथा false। |

## संबंधित देखें

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* क्लास [ECDsaBotan](../)
* संरचना [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)