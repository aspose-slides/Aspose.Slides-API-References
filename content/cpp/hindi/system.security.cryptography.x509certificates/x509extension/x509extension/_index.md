---
title: X509Extension()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: कंस्ट्रक्टर।
type: docs
weight: 1
url: /hi/system.security.cryptography.x509certificates/x509extension/x509extension/
---
## X509Extension::X509Extension(const SharedPtr\<AsnEncodedData\>\&, bool) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<AsnEncodedData> &encoded_extension, bool critical)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| encoded_extension | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | प्रमाणपत्र से जुड़ा एन्कोडेड डेटा। |
| critical | **bool** | क्रिटिकलिटी संकेत। |

## X509Extension::X509Extension(const SharedPtr\<Oid\>\&, const ByteArrayPtr\&, bool) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const SharedPtr<Oid> &oid, const ByteArrayPtr &raw_data, bool critical)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oid | const [SharedPtr](../../../system/sharedptr/)\<[Oid](../../../system.security.cryptography/oid/)\>\& | [Object](../../../system/object/) पहचानकर्ता विस्तार से जुड़ा। |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्रमाणपत्र से जुड़ा कच्चा डेटा। |
| critical | **bool** | क्रिटिकलिटी संकेत। |

## X509Extension::X509Extension(const String\&, const ByteArrayPtr\&, bool) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Extension::X509Extension(const String &oid, const ByteArrayPtr &raw_data, bool critical)
```

### आर्गुमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| oid | const [String](../../../system/string/)\& | [Object](../../../system/object/) पहचानकर्ता विस्तार से जुड़ा। |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्रमाणपत्र से जुड़ा कच्चा डेटा। |
| critical | **bool** | क्रिटिकलिटी संकेत। |

## संबंधित देखें

* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* क्लास [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* क्लास [X509Extension](../)
* क्लास [Oid](../../../system.security.cryptography/oid/)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Security::Cryptography::X509Certificates](../../)
* लाइब्रेरी [Aspose.Slides](../../../)