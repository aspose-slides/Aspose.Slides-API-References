---
title: SignData()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: निर्दिष्ट इनपुट मान की हस्ताक्षर की गणना करता है।
type: docs
weight: 183
url: /hi/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) मेथड

निर्दिष्ट इनपुट मान की हस्ताक्षर की गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) इनपुट डेटा पढ़ने के लिए। |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | उपयोग करने हेतु हैश एल्गोरिदम। |

### रिटर्न मान

[RSA](../../rsa/) निर्दिष्ट डेटा के लिए हस्ताक्षर।

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) मेथड

निर्दिष्ट इनपुट मान की हस्ताक्षर की गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | हस्ताक्षरित डेटा पढ़ने के लिए स्ट्रीम। |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | उपयोग करने हेतु हैश एल्गोरिदम। |

### रिटर्न मान

[RSA](../../rsa/) निर्दिष्ट डेटा के लिए हस्ताक्षर।

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) मेथड

निर्दिष्ट इनपुट मान की हस्ताक्षर की गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```

### आर्ग्युमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) इनपुट डेटा पढ़ने के लिए। |
| offset | **int32_t** | इनपुट बफ़र स्लाइस की प्रारंभिक इंडेक्स। |
| count | **int32_t** | इनपुट बफ़र स्लाइस का आकार। |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | उपयोग करने हेतु हैश एल्गोरिदम। |

### रिटर्न मान

[RSA](../../rsa/) निर्दिष्ट डेटा के लिए हस्ताक्षर।

## देखें भी

* टाइपडिफ़ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* क्लास [Object](../../../system/object/)
* क्लास [RSACryptoServiceProvider](../)
* क्लास [Stream](../../../system.io/stream/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)