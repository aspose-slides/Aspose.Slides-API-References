---
title: SslStream()
second_title: Aspose.Slides for C++ API Reference
description: Constructs a new instance.
type: docs
weight: 326
url: /cpp/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream([System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream that is used for sending and receiving data. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
## SslStream::SslStream([System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>, **bool**) constructor


Constructs a new instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | The stream that is used for sending and receiving data. |
| leaveInnerStreamOpen | **bool** | If true, closing the current instance has no effect on 'InnerStream'. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
## SslStream::SslStream([System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)) constructor


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
## SslStream::SslStream([System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)) constructor


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

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
## SslStream::SslStream([System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>, **bool**, [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/), [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/), [EncryptionPolicy](../../encryptionpolicy/)) constructor


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

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)
