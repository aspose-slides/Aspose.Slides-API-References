---
title: SslStream()
second_title: Aspose.Slides for C++ API Referansı
description: Yeni bir örnek oluşturur.
type: docs
weight: 326
url: /tr/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Verileri gönderip almak için kullanılan akış. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Verileri gönderip almak için kullanılan akış. |
| leaveInnerStreamOpen | **bool** | Doğru ise, mevcut örneği kapatmak 'InnerStream' üzerinde hiçbir etki yapmaz. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Verileri gönderip almak için kullanılan akış. |
| leaveInnerStreamOpen | **bool** | Doğru ise, mevcut örneği kapatmak 'InnerStream' üzerinde hiçbir etki yapmaz. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Uzak taraf tarafından sağlanan sertifikayı doğrulamak için kullanılan temsilci. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Verileri gönderip almak için kullanılan akış. |
| leaveInnerStreamOpen | **bool** | Doğru ise, mevcut örneği kapatmak 'InnerStream' üzerinde hiçbir etki yapmaz. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Uzak taraf tarafından sağlanan sertifikayı doğrulamak için kullanılan temsilci. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Kimlik doğrulama için kullanılan sertifikayı seçmek için kullanılan temsilci. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) yapıcı

Yeni bir örnek oluşturur.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Verileri gönderip almak için kullanılan akış. |
| leaveInnerStreamOpen | **bool** | Doğru ise, mevcut örneği kapatmak 'InnerStream' üzerinde hiçbir etki yapmaz. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Uzak taraf tarafından sağlanan sertifikayı doğrulamak için kullanılan temsilci. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Kimlik doğrulama için kullanılan sertifikayı seçmek için kullanılan temsilci. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Şifreleme politikası. |

## İlgili

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Tip Tanımı [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Tip Tanımı [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [SslStream](../)
* İsim Uzayı [System::Net::Security](../../)
* Kütüphane [Aspose.Slides](../../../)