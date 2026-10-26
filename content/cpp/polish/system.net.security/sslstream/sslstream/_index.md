---
title: SslStream()
second_title: Odwołanie API Aspose.Slides dla C++
description: Tworzy nową instancję.
type: docs
weight: 326
url: /pl/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień używany do wysyłania i odbierania danych. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień używany do wysyłania i odbierania danych. |
| leaveInnerStreamOpen | **bool** | Jeśli true, zamknięcie bieżącej instancji nie ma wpływu na 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień używany do wysyłania i odbierania danych. |
| leaveInnerStreamOpen | **bool** | Jeśli true, zamknięcie bieżącej instancji nie ma wpływu na 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegat używany do walidacji certyfikatu dostarczonego przez zdalną stronę. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień używany do wysyłania i odbierania danych. |
| leaveInnerStreamOpen | **bool** | Jeśli true, zamknięcie bieżącej instancji nie ma wpływu na 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegat używany do walidacji certyfikatu dostarczonego przez zdalną stronę. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Delegat używany do wyboru certyfikatu używanego do uwierzytelniania. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) konstruktor


Tworzy nową instancję.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Strumień używany do wysyłania i odbierania danych. |
| leaveInnerStreamOpen | **bool** | Jeśli true, zamknięcie bieżącej instancji nie ma wpływu na 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegat używany do walidacji certyfikatu dostarczonego przez zdalną stronę. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Delegat używany do wyboru certyfikatu używanego do uwierzytelniania. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Polityka szyfrowania. |

## Zobacz także

* Wyliczenie [EncryptionPolicy](../../encryptionpolicy/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Definicja typu [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Definicja typu [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Klasa [Stream](../../../system.io/stream/)
* Klasa [SslStream](../)
* Przestrzeń nazw [System::Net::Security](../../)
* Biblioteka [Aspose.Slides](../../../)