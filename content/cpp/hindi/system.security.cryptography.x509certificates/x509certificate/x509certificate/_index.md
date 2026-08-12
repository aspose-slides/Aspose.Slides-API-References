---
title: X509Certificate()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 1
url: /hi/system.security.cryptography.x509certificates/x509certificate/x509certificate/
---
## X509Certificate::X509Certificate(const X509Certificate\&) कंस्ट्रक्टर




```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const X509Certificate &)=delete
```

## X509Certificate::X509Certificate() कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate()
```

## X509Certificate::X509Certificate(const ByteArrayPtr\&) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &data)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | एन्कोडेड प्रमाणपत्र का प्रतिनिधित्व करने वाले बाइट्स की श्रृंखला। |

## X509Certificate::X509Certificate(const String\&) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र लोड करने के लिए फ़ाइल। |

## X509Certificate::X509Certificate(const SharedPtr\<X509Certificate\>\&) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const SharedPtr<X509Certificate> &cert)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../)\>\& | इस ऑब्जेक्ट को प्रारम्भ करने के लिए उपयोग किया गया प्रमाणपत्र। |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | एन्कोडेड प्रमाणपत्र का प्रतिनिधित्व करने वाले बाइट्स की श्रृंखला। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | एन्कोडेड प्रमाणपत्र का प्रतिनिधित्व करने वाले बाइट्स की श्रृंखला। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |

## X509Certificate::X509Certificate(const String\&, const String\&) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र लोड करने के लिए फ़ाइल। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र लोड करने के लिए फ़ाइल। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | एन्कोडेड प्रमाणपत्र का प्रतिनिधित्व करने वाले बाइट्स की श्रृंखला। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए दर्शाने वाले फ़्लैग। |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | एन्कोडेड प्रमाणपत्र का प्रतिनिधित्व करने वाले बाइट्स की श्रृंखला। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए दर्शाने वाले फ़्लैग। |

## X509Certificate::X509Certificate(const String\&, const String\&, X509KeyStorageFlags) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र लोड करने के लिए फ़ाइल। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए दर्शाने वाले फ़्लैग। |

## X509Certificate::X509Certificate(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र लोड करने के लिए फ़ाइल। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र डेटा तक पहुँचने के लिए उपयोग किया गया पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए दर्शाने वाले फ़्लैग। |

## X509Certificate::X509Certificate(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) कंस्ट्रक्टर

कंस्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate::X509Certificate(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | एन्कोडेड प्रमाणपत्र (सार्वजनिक भाग) का प्रतिनिधित्व करने वाले बाइट्स की श्रृंखला। |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | निजी कुंजी का प्रतिनिधित्व करने वाले बाइट्स की श्रृंखला। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए दर्शाने वाले फ़्लैग। |

## देखें

* एन्यूम [X509KeyStorageFlags](../../x509keystorageflags/)
* टाइपडिफ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ [SecureStringPtr](../../../system.security/securestringptr/)
* क्लास [X509Certificate](../)
* क्लास [String](../../../system/string/)
* नेमस्पेस [System::Security::Cryptography::X509Certificates](../../)
* लाइब्रेरी [Aspose.Slides](../../../)