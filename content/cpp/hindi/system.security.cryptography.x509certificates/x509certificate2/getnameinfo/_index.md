---
title: GetNameInfo()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: प्रमाणपत्र से सब्जेक्ट या जारीकर्ता का नाम प्राप्त करता है।
type: docs
weight: 248
url: /hi/system.security.cryptography.x509certificates/x509certificate2/getnameinfo/
---
## X509Certificate2::GetNameInfo(X509NameType, bool) const method

प्रमाणपत्र से सब्जेक्ट या जारीकर्ता का नाम प्राप्त करता है।

```cpp
String System::Security::Cryptography::X509Certificates::X509Certificate2::GetNameInfo(X509NameType name_type, bool for_issuer) const
```

### तर्क

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| name_type | [X509NameType](../../x509nametype/) | नाम स्वरूपण विकल्प। |
| for_issuer | **bool** | यदि सत्य हो तो जारीकर्ता नाम लौटाता है, अन्यथा सब्जेक्ट नाम लौटाता है। |

### रिटर्न मान

स्वरूपित जारीकर्ता या सब्जेक्ट नाम।

## देखें

* एनम [X509NameType](../../x509nametype/)
* क्लास [String](../../../system/string/)
* क्लास [X509Certificate2](../)
* नेमस्पेस [System::Security::Cryptography::X509Certificates](../../)
* लाइब्रेरी [Aspose.Slides](../../../)