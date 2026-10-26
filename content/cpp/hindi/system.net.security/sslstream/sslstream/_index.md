---
title: SslStream()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: एक नया उदाहरण बनाता है।
type: docs
weight: 326
url: /hi/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) कंस्ट्रक्टर


एक नया उदाहरण बनाता है।

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला स्ट्रीम। |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) कंस्ट्रक्टर


एक नया उदाहरण बनाता है।

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला स्ट्रीम। |
| leaveInnerStreamOpen | **bool** | यदि true है, तो वर्तमान उदाहरण को बंद करने से 'InnerStream' पर कोई प्रभाव नहीं पड़ता। |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) कंस्ट्रक्टर


एक नया उदाहरण बनाता है।

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला स्ट्रीम। |
| leaveInnerStreamOpen | **bool** | यदि true है, तो वर्तमान उदाहरण को बंद करने से 'InnerStream' पर कोई प्रभाव नहीं पड़ता। |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | रिमोट पक्ष द्वारा प्रदान किया गया प्रमाणपत्र मान्य करने के लिए उपयोग किया जाने वाला डेलिगेट। |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) कंस्ट्रक्टर


एक नया उदाहरण बनाता है।

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला स्ट्रीम। |
| leaveInnerStreamOpen | **bool** | यदि true है, तो वर्तमान उदाहरण को बंद करने से 'InnerStream' पर कोई प्रभाव नहीं पड़ता। |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | रिमोट पक्ष द्वारा प्रदान किया गया प्रमाणपत्र मान्य करने के लिए उपयोग किया जाने वाला डेलिगेट। |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | प्रमाणन के लिए उपयोग किया गया प्रमाणपत्र चुनने के लिए उपयोग किया जाने वाला डेलिगेट। |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) कंस्ट्रक्टर


एक नया उदाहरण बनाता है।

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### तर्क

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | डेटा भेजने और प्राप्त करने के लिए उपयोग किया जाने वाला स्ट्रीम। |
| leaveInnerStreamOpen | **bool** | यदि true है, तो वर्तमान उदाहरण को बंद करने से 'InnerStream' पर कोई प्रभाव नहीं पड़ता। |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | रिमोट पक्ष द्वारा प्रदान किया गया प्रमाणपत्र मान्य करने के लिए उपयोग किया जाने वाला डेलिगेट। |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | प्रमाणन के लिए उपयोग किया गया प्रमाणपत्र चुनने के लिए उपयोग किया जाने वाला डेलिगेट। |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | एन्क्रिप्शन नीति। |

## संबंधित देखें

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* क्लास [Stream](../../../system.io/stream/)
* क्लास [SslStream](../)
* नामस्थान [System::Net::Security](../../)
* लाइब्रेरी [Aspose.Slides](../../../)