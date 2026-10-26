---
title: SslStream()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een nieuw exemplaar aan.
type: docs
weight: 326
url: /nl/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | De stream die wordt gebruikt voor het verzenden en ontvangen van gegevens. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | De stream die wordt gebruikt voor het verzenden en ontvangen van gegevens. |
| leaveInnerStreamOpen | **bool** | Indien true, heeft het sluiten van de huidige instantie geen effect op 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | De stream die wordt gebruikt voor het verzenden en ontvangen van gegevens. |
| leaveInnerStreamOpen | **bool** | Indien true, heeft het sluiten van de huidige instantie geen effect op 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | De delegate die wordt gebruikt om het door de externe partij geleverde certificaat te valideren. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | De stream die wordt gebruikt voor het verzenden en ontvangen van gegevens. |
| leaveInnerStreamOpen | **bool** | Indien true, heeft het sluiten van de huidige instantie geen effect op 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | De delegate die wordt gebruikt om het door de externe partij geleverde certificaat te valideren. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | De delegate die wordt gebruikt voor het selecteren van het certificaat dat wordt gebruikt voor authenticatie. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) constructor

Maakt een nieuw exemplaar aan.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | De stream die wordt gebruikt voor het verzenden en ontvangen van gegevens. |
| leaveInnerStreamOpen | **bool** | Indien true, heeft het sluiten van de huidige instantie geen effect op 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | De delegate die wordt gebruikt om het door de externe partij geleverde certificaat te valideren. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | De delegate die wordt gebruikt voor het selecteren van het certificaat dat wordt gebruikt voor authenticatie. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Het encryptiebeleid. |

## Zie ook

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Klasse [Stream](../../../system.io/stream/)
* Klasse [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)