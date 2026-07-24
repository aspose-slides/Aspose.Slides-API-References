---
title: SslStream()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt eine neue Instanz.
type: docs
weight: 326
url: /de/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Der Stream, der zum Senden und Empfangen von Daten verwendet wird. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Der Stream, der zum Senden und Empfangen von Daten verwendet wird. |
| leaveInnerStreamOpen | **bool** | Wenn true, hat das Schließen der aktuellen Instanz keine Auswirkung auf 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Der Stream, der zum Senden und Empfangen von Daten verwendet wird. |
| leaveInnerStreamOpen | **bool** | Wenn true, hat das Schließen der aktuellen Instanz keine Auswirkung auf 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Der Delegat, der zum Validieren des von der Gegenstelle bereitgestellten Zertifikats verwendet wird. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Der Stream, der zum Senden und Empfangen von Daten verwendet wird. |
| leaveInnerStreamOpen | **bool** | Wenn true, hat das Schließen der aktuellen Instanz keine Auswirkung auf 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Der Delegat, der zum Validieren des von der Gegenstelle bereitgestellten Zertifikats verwendet wird. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Der Delegat, der zum Auswählen des für die Authentifizierung verwendeten Zertifikats verwendet wird. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) Konstruktor


Erstellt eine neue Instanz.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Der Stream, der zum Senden und Empfangen von Daten verwendet wird. |
| leaveInnerStreamOpen | **bool** | Wenn true, hat das Schließen der aktuellen Instanz keine Auswirkung auf 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Der Delegat, der zum Validieren des von der Gegenstelle bereitgestellten Zertifikats verwendet wird. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Der Delegat, der zum Auswählen des für die Authentifizierung verwendeten Zertifikats verwendet wird. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Die Verschlüsselungsrichtlinie. |

## Siehe auch

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)