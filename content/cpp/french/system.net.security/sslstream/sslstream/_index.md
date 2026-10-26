---
title: SslStream()
second_title: Référence API Aspose.Slides for C++
description: Crée une nouvelle instance.
type: docs
weight: 326
url: /fr/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor

Construit une nouvelle instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Le flux utilisé pour l'envoi et la réception de données. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor

Construit une nouvelle instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Le flux utilisé pour l'envoi et la réception de données. |
| leaveInnerStreamOpen | **bool** | Si true, la fermeture de l'instance actuelle n'a aucun effet sur 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor

Construit une nouvelle instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Le flux utilisé pour l'envoi et la réception de données. |
| leaveInnerStreamOpen | **bool** | Si true, la fermeture de l'instance actuelle n'a aucun effet sur 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Le délégué utilisé pour valider le certificat fourni par la partie distante. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor

Construit une nouvelle instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Le flux utilisé pour l'envoi et la réception de données. |
| leaveInnerStreamOpen | **bool** | Si true, la fermeture de l'instance actuelle n'a aucun effet sur 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Le délégué utilisé pour valider le certificat fourni par la partie distante. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Le délégué utilisé pour sélectionner le certificat utilisé pour l'authentification. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor

Construit une nouvelle instance.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Le flux utilisé pour l'envoi et la réception de données. |
| leaveInnerStreamOpen | **bool** | Si true, la fermeture de l'instance actuelle n'a aucun effet sur 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Le délégué utilisé pour valider le certificat fourni par la partie distante. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Le délégué utilisé pour sélectionner le certificat utilisé pour l'authentification. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | La politique de chiffrement. |

## See Also

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)