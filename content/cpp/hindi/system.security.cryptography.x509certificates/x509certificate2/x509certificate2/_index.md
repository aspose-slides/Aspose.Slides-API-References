---
title: X509Certificate2()
second_title: Aspose.Slides C++ के लिए API संदर्भ
description: खाली X509Certificate2 बनाता है।
type: docs
weight: 1
url: /hi/system.security.cryptography.x509certificates/x509certificate2/x509certificate2/
---
## X509Certificate2::X509Certificate2() कन्स्ट्रक्टर

खाली [X509Certificate2](../) बनाता है।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2()
```

## X509Certificate2::X509Certificate2(const String\&) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र को लोड करने वाली फ़ाइल। |

## X509Certificate2::X509Certificate2(const SharedPtr\<X509Certificate\>\&) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const SharedPtr<X509Certificate> &cert)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| cert | const [SharedPtr](../../../system/sharedptr/)\<[X509Certificate](../../x509certificate/)\>\& | एक [X509Certificate](../../x509certificate/) ऑब्जेक्ट। |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | बाइटों का क्रम जो एन्कोडेड प्रमाणपत्र को दर्शाता है। |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | बाइटों का क्रम जो एन्कोडेड प्रमाणपत्र को दर्शाता है। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र पासवर्ड। |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | बाइटों का क्रम जो एन्कोडेड प्रमाणपत्र को दर्शाता है। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र पासवर्ड। |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const String\&, X509KeyStorageFlags) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const String &password, X509KeyStorageFlags key_storage_flags)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | बाइटों का क्रम जो एन्कोडेड प्रमाणपत्र को दर्शाता है। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए यह दर्शाने वाले फ़्लैग। |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const SecureStringPtr\&, X509KeyStorageFlags) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | बाइटों का क्रम जो एन्कोडेड प्रमाणपत्र को दर्शाता है। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए यह दर्शाने वाले फ़्लैग। |

## X509Certificate2::X509Certificate2(const String\&, const String\&) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र को लोड करने वाली फ़ाइल। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र पासवर्ड। |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र को लोड करने वाली फ़ाइल। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र पासवर्ड। |

## X509Certificate2::X509Certificate2(const String\&, const String\&, X509KeyStorageFlags) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const String &password, X509KeyStorageFlags key_storage_flags)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र को लोड करने वाली फ़ाइल। |
| password | const [String](../../../system/string/)\& | प्रमाणपत्र पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए यह दर्शाने वाले फ़्लैग। |

## X509Certificate2::X509Certificate2(const String\&, const SecureStringPtr\&, X509KeyStorageFlags) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const String &filename, const SecureStringPtr &password, X509KeyStorageFlags key_storage_flags)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | प्रमाणपत्र को लोड करने वाली फ़ाइल। |
| password | const [SecureStringPtr](../../../system.security/securestringptr/)\& | प्रमाणपत्र पासवर्ड। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए यह दर्शाने वाले फ़्लैग। |

## X509Certificate2::X509Certificate2(const ByteArrayPtr\&, const ByteArrayPtr\&, X509KeyStorageFlags) कन्स्ट्रक्टर

कन्स्ट्रक्टर।

```cpp
System::Security::Cryptography::X509Certificates::X509Certificate2::X509Certificate2(const ByteArrayPtr &raw_data, const ByteArrayPtr &private_key, X509KeyStorageFlags key_storage_flags)
```

### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| raw_data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | बाइटों का क्रम जो एन्कोडेड प्रमाणपत्र (सार्वजनिक भाग) को दर्शाता है। |
| private_key | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | बाइटों का क्रम जो निजी कुंजी को दर्शाता है। |
| key_storage_flags | [X509KeyStorageFlags](../../x509keystorageflags/) | की को कैसे संग्रहीत किया जाए यह दर्शाने वाले फ़्लैग। |

## देखें

* Enum [X509KeyStorageFlags](../../x509keystorageflags/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SecureStringPtr](../../../system.security/securestringptr/)
* Class [X509Certificate2](../)
* Class [String](../../../system/string/)
* Class [X509Certificate](../../x509certificate/)
* Namespace [System::Security::Cryptography::X509Certificates](../../)
* Library [Aspose.Slides](../../../)