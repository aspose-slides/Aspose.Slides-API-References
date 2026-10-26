---
title: HashAlgorithmName
second_title: Aspose.Slides for C++ API संदर्भ
description: "हैश एल्गोरिद्म के नाम का प्रतिनिधित्व करने वाली स्ट्रिंग। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए System::SmartPtr क्लास का कभी उपयोग न करें।"
type: docs
weight: 755
url: /hi/system.security.cryptography/hashalgorithmname/
---
## HashAlgorithmName संरचना

[String](../../system/string/) है जो एक हैश एल्गोरिद्म के नाम का प्रतिनिधित्व करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। कभी भी [System::SmartPtr](../../system/smartptr/) क्लास का उपयोग इस प्रकार की वस्तुओं को प्रबंधित करने के लिए न करें।

```cpp
class HashAlgorithmName
```

## विधियां

| विधि | विवरण |
| --- | --- |
| **bool** [Equals](./equals/)(const [HashAlgorithmName](./)\&) const |  |
| static [HashAlgorithmName](./) [FromOid](./fromoid/)(const [String](../../system/string/)\&) | OID-वैल्यू से [HashAlgorithmName](./) बनाएं। |
| static [HashAlgorithmName](./) [get_MD5](./get_md5/)() | एक [HashAlgorithmName](./) प्राप्त करता है जो [MD5](../md5/) का प्रतिनिधित्व करता है। |
| [String](../../system/string/) [get_Name](./get_name/)() const | एल्गोरिद्म नाम का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| static [HashAlgorithmName](./) [get_SHA1](./get_sha1/)() | एक [HashAlgorithmName](./) प्राप्त करता है जो [SHA1](../sha1/) का प्रतिनिधित्व करता है। |
| static [HashAlgorithmName](./) [get_SHA256](./get_sha256/)() | एक [HashAlgorithmName](./) प्राप्त करता है जो [SHA256](../sha256/) का प्रतिनिधित्व करता है। |
| static [HashAlgorithmName](./) [get_SHA384](./get_sha384/)() | एक [HashAlgorithmName](./) प्राप्त करता है जो [SHA384](../sha384/) का प्रतिनिधित्व करता है। |
| static [HashAlgorithmName](./) [get_SHA512](./get_sha512/)() | एक [HashAlgorithmName](./) प्राप्त करता है जो [SHA512](../sha512/) का प्रतिनिधित्व करता है। |
| int [GetHashCode](./gethashcode/)() const |  |
| [HashAlgorithmName](./hashalgorithmname/)() |  |
| [HashAlgorithmName](./hashalgorithmname/)(const [String](../../system/string/)\&) | कंस्ट्रक्टर। |
| **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [HashAlgorithmName](./)\& [operator=](./operator_equal/)(const [HashAlgorithmName](./)\&) |  |
| **bool** [operator==](./operator_equal_equal/)(const [HashAlgorithmName](./)\&) const |  |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| [String](../../system/string/) [ToString](./tostring/)() const | एल्गोरिद्म नाम का स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| static **bool** [TryFromOid](./tryfromoid/)(const [String](../../system/string/)\&, [HashAlgorithmName](./)\&) | OID-वैल्यू से [HashAlgorithmName](./) बनाने का प्रयास करें। |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](./type/)() | एक [TypeInfo](../../system/typeinfo/) ऑब्जेक्ट लौटाता है जो [TimeSpan](../../system/timespan/) संरचना का प्रतिनिधित्व करता है। |

## संबंधित

* नामस्थान [System::Security::Cryptography](../)
* लाइब्रेरी [Aspose.Slides](../../)