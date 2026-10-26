---
title: X509KeyUsageExtension()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: डिफ़ॉल्ट कंस्ट्रक्टर।
type: docs
weight: 1
url: /hi/system.security.cryptography.x509certificates/x509keyusageextension/x509keyusageextension/
---
## X509KeyUsageExtension::X509KeyUsageExtension() कंस्ट्रक्टर

डिफ़ॉल्ट कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension()
```

## X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr\<AsnEncodedData\>\&, bool) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(const SharedPtr<AsnEncodedData> &encoded_key_usage, bool critical)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| encoded_key_usage | const [SharedPtr](../../../system/sharedptr/)\<[AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)\>\& | कुंजी उपयोगों का एन्कोडेड डेटा। |
| critical | **bool** | क्रिटिकलिटी संकेत। |

## X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags, bool) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509KeyUsageExtension::X509KeyUsageExtension(X509KeyUsageFlags key_usages, bool critical)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| key_usages | [X509KeyUsageFlags](../../x509keyusageflags/) | कुंजी उपयोग। |
| critical | **bool** | क्रिटिकलिटी संकेत। |

## देखें

* Enum [X509KeyUsageFlags](../../x509keyusageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [X509KeyUsageExtension](../)
* Class [AsnEncodedData](../../../system.security.cryptography/asnencodeddata/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)