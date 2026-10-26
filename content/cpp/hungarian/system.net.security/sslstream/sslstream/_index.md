---
title: SslStream()
second_title: Aspose.Slides a C++ API hivatkozása
description: Új példányt hoz létre.
type: docs
weight: 326
url: /hu/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) konstruktor

Új példányt hoz létre.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az adatküldésre és -fogadásra használt adatfolyam. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) konstruktor

Új példányt hoz létre.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az adatküldésre és -fogadásra használt adatfolyam. |
| leaveInnerStreamOpen | **bool** | Ha igaz, a jelenlegi példány bezárása nem befolyásolja az 'InnerStream'-et. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) konstruktor

Új példányt hoz létre.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az adatküldésre és -fogadásra használt adatfolyam. |
| leaveInnerStreamOpen | **bool** | Ha igaz, a jelenlegi példány bezárása nem befolyásolja az 'InnerStream'-et. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | A delegált, amelyet a távoli fél által biztosított tanúsítvány érvényesítésére használnak. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) konstruktor

Új példányt hoz létre.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az adatküldésre és -fogadásra használt adatfolyam. |
| leaveInnerStreamOpen | **bool** | Ha igaz, a jelenlegi példány bezárása nem befolyásolja az 'InnerStream'-et. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | A delegált, amelyet a távoli fél által biztosított tanúsítvány érvényesítésére használnak. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | A delegált, amelyet a hitelesítéshez használt tanúsítvány kiválasztására használnak. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) konstruktor

Új példányt hoz létre.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | Az adatküldésre és -fogadásra használt adatfolyam. |
| leaveInnerStreamOpen | **bool** | Ha igaz, a jelenlegi példány bezárása nem befolyásolja az 'InnerStream'-et. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | A delegált, amelyet a távoli fél által biztosított tanúsítvány érvényesítésére használnak. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | A delegált, amelyet a hitelesítéshez használt tanúsítvány kiválasztására használnak. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | A titkosítási szabályzat. |

## Lásd még

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [SslStream](../)
* Névtere [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)