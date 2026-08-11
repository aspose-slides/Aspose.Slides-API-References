---
title: SslStream()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بإنشاء نسخة جديدة.
type: docs
weight: 326
url: /ar/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) المنشئ

يقوم بإنشاء نسخة جديدة.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | الدفق المستخدم لإرسال واستقبال البيانات. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) المنشئ

يقوم بإنشاء نسخة جديدة.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | الدفق المستخدم لإرسال واستقبال البيانات. |
| leaveInnerStreamOpen | **bool** | إذا كان true، فإن إغلاق النسخة الحالية لا يؤثر على 'InnerStream'. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) المنشئ

يقوم بإنشاء نسخة جديدة.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | الدفق المستخدم لإرسال واستقبال البيانات. |
| leaveInnerStreamOpen | **bool** | إذا كان true، فإن إغلاق النسخة الحالية لا يؤثر على 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | المفوض الذي يُستَخدم للتحقق من الشهادة التي يزودها الطرف البعيد. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) المنشئ

يقوم بإنشاء نسخة جديدة.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | الدفق المستخدم لإرسال واستقبال البيانات. |
| leaveInnerStreamOpen | **bool** | إذا كان true، فإن إغلاق النسخة الحالية لا يؤثر على 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | المفوض الذي يُستَخدم للتحقق من الشهادة التي يزودها الطرف البعيد. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | المفوض الذي يُستَخدم لاختيار الشهادة المستخدمة للمصادقة. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) المنشئ

يقوم بإنشاء نسخة جديدة.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | الدفق المستخدم لإرسال واستقبال البيانات. |
| leaveInnerStreamOpen | **bool** | إذا كان true، فإن إغلاق النسخة الحالية لا يؤثر على 'InnerStream'. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | المفوض الذي يُستَخدم للتحقق من الشهادة التي يزودها الطرف البعيد. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | المفوض الذي يُستَخدم لاختيار الشهادة المستخدمة للمصادقة. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | سياسة التشفير. |

## انظر أيضًا

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* Class [Stream](../../../system.io/stream/)
* Class [SslStream](../)
* Namespace [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)