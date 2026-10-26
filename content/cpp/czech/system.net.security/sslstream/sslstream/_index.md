---
title: SslStream()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Vytvoří novou instanci.
type: docs
weight: 326
url: /cs/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Proud, který se používá k odesílání a přijímání dat. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Proud, který se používá k odesílání a přijímání dat. |
| leaveInnerStreamOpen | **bool** | Pokud je true, uzavření aktuální instance nemá vliv na 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Proud, který se používá k odesílání a přijímání dat. |
| leaveInnerStreamOpen | **bool** | Pokud je true, uzavření aktuální instance nemá vliv na 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegát, který se používá k ověření certifikátu poskytnutého vzdálenou stranou. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Proud, který se používá k odesílání a přijímání dat. |
| leaveInnerStreamOpen | **bool** | Pokud je true, uzavření aktuální instance nemá vliv na 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegát, který se používá k ověření certifikátu poskytnutého vzdálenou stranou. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Delegát, který se používá k výběru certifikátu používaného pro autentizaci. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) konstruktor

Vytvoří novou instanci.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Proud, který se používá k odesílání a přijímání dat. |
| leaveInnerStreamOpen | **bool** | Pokud je true, uzavření aktuální instance nemá vliv na 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegát, který se používá k ověření certifikátu poskytnutého vzdálenou stranou. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Delegát, který se používá k výběru certifikátu používaného pro autentizaci. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Šifrovací politika. |

## Viz také

* Výčet [EncryptionPolicy](../../encryptionpolicy/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Definice typu [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Definice typu [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Třída [Stream](../../../system.io/stream/)
* Třída [SslStream](../)
* Jmenný prostor [System::Net::Security](../../)
* Knihovna [Aspose.Slides](../../../)