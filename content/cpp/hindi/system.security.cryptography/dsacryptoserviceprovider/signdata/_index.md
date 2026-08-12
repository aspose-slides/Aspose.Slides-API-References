---
title: SignData()
second_title: Aspose.Slides for C++ API संदर्भ
description: निर्दिष्ट इनपुट मान का हस्ताक्षर गणना करता है।
type: docs
weight: 183
url: /hi/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) विधि

निर्दिष्ट इनपुट मान का हस्ताक्षर गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) इनपुट डेटा पढ़ने के लिए। |

### रिटर्न मान

[DSA](../../dsa/) निर्दिष्ट डेटा के लिए हस्ताक्षर।

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) विधि

निर्दिष्ट इनपुट मान का हस्ताक्षर गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | साइन किए जा रहे डेटा को पढ़ने के लिए स्ट्रीम। |

### रिटर्न मान

[DSA](../../dsa/) निर्दिष्ट डेटा के लिए हस्ताक्षर।

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) विधि

निर्दिष्ट इनपुट मान का हस्ताक्षर गणना करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) इनपुट डेटा पढ़ने के लिए। |
| offset | **int32_t** | इनपुट बफ़र स्लाइस की प्रारंभिक इंडेक्स। |
| count | **int32_t** | इनपुट बफ़र स्लाइस का आकार। |

### रिटर्न मान

[DSA](../../dsa/) निर्दिष्ट डेटा के लिए हस्ताक्षर।

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) विधि

निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके निर्दिष्ट डेटा एरे का हैश मान गणना करता है, और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। इनपुट डेटा के लिए [DSA](../../dsa/) हस्ताक्षर वापस करता है। |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) विधि

निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके निर्दिष्ट डेटा एरे का हैश मान गणना करता है, और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | इनपुट डेटा एरे। |
| offset | **int32_t** | **data** में ऑफ़सेट। |
| count | **int32_t** | इनपुट डेटा के रूप में उपयोग किए जाने वाले बाइट्स की संख्या। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। इनपुट डेटा के लिए [DSA](../../dsa/) हस्ताक्षर वापस करता है। |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) विधि

निर्दिष्ट हैश एल्गोरिद्म का उपयोग करके निर्दिष्ट बाइनरी स्ट्रीम का हैश मान गणना करता है, और परिणाम पर हस्ताक्षर करता है।

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | बाइनरी स्ट्रीम। |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | हैश एल्गोरिद्म। इनपुट डेटा के लिए [DSA](../../dsa/) हस्ताक्षर वापस करता है। |

## देखिए

* टाइपडिफ़ [ByteArrayPtr](../../../system/bytearrayptr/)
* टाइपडिफ़ [SharedPtr](../../../system/sharedptr/)
* टाइपडिफ़ [StreamPtr](../../../system/streamptr/)
* क्लास [DSACryptoServiceProvider](../)
* क्लास [Stream](../../../system.io/stream/)
* संरचना [HashAlgorithmName](../../hashalgorithmname/)
* नेमस्पेस [System::Security::Cryptography](../../)
* लाइब्रेरी [Aspose.Slides](../../../)