---
title: SslStream()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый экземпляр.
type: docs
weight: 326
url: /ru/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) конструктор


Создает новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток, используемый для отправки и получения данных. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) конструктор


Создает новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток, используемый для отправки и получения данных. |
| leaveInnerStreamOpen | **bool** | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) конструктор


Создает новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток, используемый для отправки и получения данных. |
| leaveInnerStreamOpen | **bool** | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Делегат, используемый для проверки сертификата, предоставленного удаленной стороной. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) конструктор


Создает новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток, используемый для отправки и получения данных. |
| leaveInnerStreamOpen | **bool** | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Делегат, используемый для проверки сертификата, предоставленного удаленной стороной. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Делегат, используемый для выбора сертификата, используемого для аутентификации. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) конструктор


Создает новый экземпляр.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Поток, используемый для отправки и получения данных. |
| leaveInnerStreamOpen | **bool** | Если true, закрытие текущего экземпляра не влияет на 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Делегат, используемый для проверки сертификата, предоставленного удаленной стороной. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Делегат, используемый для выбора сертификата, используемого для аутентификации. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Политика шифрования. |

## См. также

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Класс [Stream](../../../system.io/stream/)
* Класс [SslStream](../)
* Пространство имен [System::Net::Security](../../)
* Библиотека [Aspose.Slides](../../../)