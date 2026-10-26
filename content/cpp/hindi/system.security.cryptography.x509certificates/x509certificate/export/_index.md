---
title: Export()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में निर्यात करता है। लागू नहीं है।
type: docs
weight: 287
url: /hi/system.security.cryptography.x509certificates/x509certificate/export/
---
## X509Certificate::Export(X509ContentType) const मेथड

निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में निर्यात करता है। लागू नहीं है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | आउटपुट डेटा को कैसे फ़ॉर्मेट करना है, यह निर्दिष्ट करता है। |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट को दर्शाने वाला बाइट्स का एरे।

## X509Certificate::Export(X509ContentType, const SecureStringPtr\&) const मेथड

निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में निर्यात करता है। लागू नहीं है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const SecureStringPtr &password) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | आउटपुट डेटा को कैसे फ़ॉर्मेट करना है, यह निर्दिष्ट करता है। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | सर्टिफ़िकेट डेटा तक पहुँचने के लिए आवश्यक पासवर्ड। |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट को दर्शाने वाला बाइट्स का एरे।

## X509Certificate::Export(X509ContentType, const String\&) const मेथड

निर्दिष्ट फ़ॉर्मेट का उपयोग करके वर्तमान ऑब्जेक्ट को बाइट एरे में निर्यात करता है। लागू नहीं है।

```cpp
virtual ByteArrayPtr System::Security::Cryptography::X509Certificates::X509Certificate::Export(X509ContentType content_type, const String &password) const
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| content_type | [X509ContentType](../../x509contenttype/) | आउटपुट डेटा को कैसे फ़ॉर्मेट करना है, यह निर्दिष्ट करता है। |
| password | const [String](../../../system/string/)\& | सर्टिफ़िकेट डेटा तक पहुँचने के लिए आवश्यक पासवर्ड। |

### रिटर्न वैल्यू

वर्तमान ऑब्जेक्ट को दर्शाने वाला बाइट्स का एरे।

## देखें

* Enum [X509ContentType](../../x509contenttype/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate](../)
* Class [String](../../../system/string/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)