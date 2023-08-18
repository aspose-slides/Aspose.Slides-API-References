---
title: SslStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 326
url: /system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream that is used for sending and receiving data. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | **bool** | If true, closing the current instance has no effect on 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | **bool** | If true, closing the current instance has no effect on 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | The delegate that is used for validating the certificate supplied by the remote party. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | **bool** | If true, closing the current instance has no effect on 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | The delegate that is used for validating the certificate supplied by the remote party. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | The delegate that is used for selecting the certificate used for authentication. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | **bool** | If true, closing the current instance has no effect on 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | The delegate that is used for validating the certificate supplied by the remote party. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | The delegate that is used for selecting the certificate used for authentication. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | The encryption policy. |

## See Also

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)