---
title: SslStream()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru.
type: docs
weight: 326
url: /id/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran yang digunakan untuk mengirim dan menerima data. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran yang digunakan untuk mengirim dan menerima data. |
| leaveInnerStreamOpen | **bool** | Jika true, menutup instance saat ini tidak berpengaruh pada 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran yang digunakan untuk mengirim dan menerima data. |
| leaveInnerStreamOpen | **bool** | Jika true, menutup instance saat ini tidak berpengaruh pada 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegasi yang digunakan untuk memvalidasi sertifikat yang disediakan oleh pihak remote. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran yang digunakan untuk mengirim dan menerima data. |
| leaveInnerStreamOpen | **bool** | Jika true, menutup instance saat ini tidak berpengaruh pada 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegasi yang digunakan untuk memvalidasi sertifikat yang disediakan oleh pihak remote. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Delegasi yang digunakan untuk memilih sertifikat yang dipakai untuk otentikasi. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) konstruktor


Membuat sebuah instance baru.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Aliran yang digunakan untuk mengirim dan menerima data. |
| leaveInnerStreamOpen | **bool** | Jika true, menutup instance saat ini tidak berpengaruh pada 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | Delegasi yang digunakan untuk memvalidasi sertifikat yang disediakan oleh pihak remote. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | Delegasi yang digunakan untuk memilih sertifikat yang dipakai untuk otentikasi. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | Kebijakan enkripsi. |

## Lihat Juga

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [SslStream](../)
* Ruang Nama [System::Net::Security](../../)
* Perpustakaan [Aspose.Slides](../../../)