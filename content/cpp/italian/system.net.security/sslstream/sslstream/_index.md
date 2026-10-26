---
title: SslStream()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una nuova istanza.
type: docs
weight: 326
url: /it/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) costruttore


Crea una nuova istanza.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Il flusso utilizzato per l'invio e la ricezione dei dati. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) costruttore


Crea una nuova istanza.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Il flusso utilizzato per l'invio e la ricezione dei dati. |
| leaveInnerStreamOpen | **bool** | Se true, la chiusura dell'istanza corrente non ha effetto su 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) costruttore


Crea una nuova istanza.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Il flusso utilizzato per l'invio e la ricezione dei dati. |
| leaveInnerStreamOpen | **bool** | Se true, la chiusura dell'istanza corrente non ha effetto su 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Il delegato utilizzato per convalidare il certificato fornito dalla parte remota. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) costruttore


Crea una nuova istanza.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Il flusso utilizzato per l'invio e la ricezione dei dati. |
| leaveInnerStreamOpen | **bool** | Se true, la chiusura dell'istanza corrente non ha effetto su 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Il delegato utilizzato per convalidare il certificato fornito dalla parte remota. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Il delegato utilizzato per selezionare il certificato usato per l'autenticazione. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) costruttore


Crea una nuova istanza.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Il flusso utilizzato per l'invio e la ricezione dei dati. |
| leaveInnerStreamOpen | **bool** | Se true, la chiusura dell'istanza corrente non ha effetto su 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Il delegato utilizzato per convalidare il certificato fornito dalla parte remota. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Il delegato utilizzato per selezionare il certificato usato per l'autenticazione. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | La politica di crittografia. |

## Vedi anche

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)