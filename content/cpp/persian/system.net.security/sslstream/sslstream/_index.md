---
title: SslStream()
second_title: Aspose.Slides برای C++ - مرجع API
description: یک نمونه جدید ایجاد می‌کند.
type: docs
weight: 326
url: /fa/system.net.security/sslstream/sslstream/
---
## SslStream::SslStream(System::SharedPtr\<IO::Stream\>) سازنده

یک نمونهٔ جدید ایجاد می‌کند.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریانی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool) سازنده

یک نمونهٔ جدید ایجاد می‌کند.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریانی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |
| leaveInnerStreamOpen | **bool** | اگر مقدار true باشد، بستن نمونهٔ جاری اثری بر 'InnerStream' ندارد. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback) سازنده

یک نمونهٔ جدید ایجاد می‌کند.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریانی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |
| leaveInnerStreamOpen | **bool** | اگر مقدار true باشد، بستن نمونهٔ جاری اثری بر 'InnerStream' ندارد. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | نماینده‌ای که برای اعتبارسنجی گواهی ارائه‌شده توسط طرف ریموت استفاده می‌شود. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback) سازنده

یک نمونهٔ جدید ایجاد می‌کند.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریانی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |
| leaveInnerStreamOpen | **bool** | اگر مقدار true باشد، بستن نمونهٔ جاری اثری بر 'InnerStream' ندارد. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | نماینده‌ای که برای اعتبارسنجی گواهی ارائه‌شده توسط طرف ریموت استفاده می‌شود. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | نماینده‌ای که برای انتخاب گواهی مورد استفاده برای احراز هویت استفاده می‌شود. |

## SslStream::SslStream(System::SharedPtr\<IO::Stream\>, bool, RemoteCertificateValidationCallback, LocalCertificateSelectionCallback, EncryptionPolicy) سازنده

یک نمونهٔ جدید ایجاد می‌کند.

```cpp
System::Net::Security::SslStream::SslStream(System::SharedPtr<IO::Stream> innerStream, bool leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback, EncryptionPolicy encryptionPolicy)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| innerStream | [System::SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\> | جریانی که برای ارسال و دریافت داده‌ها استفاده می‌شود. |
| leaveInnerStreamOpen | **bool** | اگر مقدار true باشد، بستن نمونهٔ جاری اثری بر 'InnerStream' ندارد. |
| userCertificateValidationCallback | [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/) | نماینده‌ای که برای اعتبارسنجی گواهی ارائه‌شده توسط طرف ریموت استفاده می‌شود. |
| userCertificateSelectionCallback | [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/) | نماینده‌ای که برای انتخاب گواهی مورد استفاده برای احراز هویت استفاده می‌شود. |
| encryptionPolicy | [EncryptionPolicy](../../encryptionpolicy/) | سیاست رمزگذاری. |

## مراجع

* Enum [EncryptionPolicy](../../encryptionpolicy/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [RemoteCertificateValidationCallback](../../remotecertificatevalidationcallback/)
* Typedef [LocalCertificateSelectionCallback](../../localcertificateselectioncallback/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [SslStream](../)
* فضای‌نام [System::Net::Security](../../)
* Library [Aspose.Slides](../../../)