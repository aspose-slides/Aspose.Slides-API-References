---
title: GetCertContentType()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट बाइट ऐरे में निहित प्रमाणपत्र का प्रकार प्राप्त करता है।
type: docs
weight: 391
url: /hi/system.security.cryptography.x509certificates/x509certificate2/getcertcontenttype/
---
## X509Certificate2::GetCertContentType(const ByteArrayPtr\&) विधि

निर्दिष्ट बाइट ऐरे में निहित प्रमाणपत्र का प्रकार प्राप्त करता है।

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const ByteArrayPtr &raw_data)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | प्रमाणपत्र डेटा। |

### रिटर्न मान

X.509 प्रमाणपत्र का प्रकार।

## X509Certificate2::GetCertContentType(const String\&) विधि

निर्दिष्ट फ़ाइल में निहित प्रमाणपत्र का प्रकार प्राप्त करता है।

```cpp
static X509ContentType System::Security::Cryptography::X509Certificates::X509Certificate2::GetCertContentType(const String &filename)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र फ़ाइल नाम। |

### रिटर्न मान

X.509 प्रमाणपत्र का प्रकार।

## संबंधित देखें

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* क्लास [X509Certificate2](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Security::Cryptography::X509Certificates](../../)
* लाइब्रेरी [Aspose.Slides](../../../)