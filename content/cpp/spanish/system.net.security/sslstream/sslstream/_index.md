---
title: SslStream()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia.
type: docs
weight: 326
url: /es/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | El flujo que se utiliza para enviar y recibir datos. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | **bool** | Si true, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | **bool** | Si true, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | El delegado que se utiliza para validar el certificado suministrado por la parte remota. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | **bool** | Si true, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | El delegado que se utiliza para validar el certificado suministrado por la parte remota. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | El delegado que se utiliza para seleccionar el certificado usado para la autenticación. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor


Construye una nueva instancia.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | El flujo que se utiliza para enviar y recibir datos. |
| leaveInnerStreamOpen | **bool** | Si true, cerrar la instancia actual no tiene efecto sobre 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | El delegado que se utiliza para validar el certificado suministrado por la parte remota. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | El delegado que se utiliza para seleccionar el certificado usado para la autenticación. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | La política de cifrado. |

## Ver también

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)