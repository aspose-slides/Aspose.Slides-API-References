---
title: SignData()
second_title: Aspose.Slides برای C++ مرجع API
description: امضای مقدار ورودی مشخص‌شده را محاسبه می‌کند.
type: docs
weight: 183
url: /fa/system.security.cryptography/dsacryptoserviceprovider/signdata/
---
## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&) method

امضای مقدار ورودی مشخص شده را محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) برای خواندن داده‌های ورودی از. |

### مقدار بازگشت

[DSA](../../dsa/) امضا برای داده‌های مشخص شده.

## DSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&) method

امضای مقدار ورودی مشخص شده را محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان برای خواندن داده‌های امضا شده از. |

### مقدار بازگشت

[DSA](../../dsa/) امضا برای داده‌های مشخص شده.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t) method

امضای مقدار ورودی مشخص شده را محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) برای خواندن داده‌های ورودی از. |
| offset | **int32_t** | ایندکس شروع برش بافر ورودی. |
| count | **int32_t** | اندازه برش بافر ورودی. |

### مقدار بازگشت

[DSA](../../dsa/) امضا برای داده‌های مشخص شده.

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method

مقدار هش داده‌های آرایه‌ی مشخص شده را با استفاده از الگوریتم هش مشخص شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه داده‌های ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. بازگشت [DSA](../../dsa/) امضا برای داده‌های ورودی. |

## DSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method

مقدار هش داده‌های آرایه‌ی مشخص شده را با استفاده از الگوریتم هش مشخص شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه داده‌های ورودی. |
| offset | **int32_t** | جابه‌جایی در **data**. |
| count | **int32_t** | تعداد بایت‌ها برای استفاده به عنوان داده ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. بازگشت [DSA](../../dsa/) امضا برای داده‌های ورودی. |

## DSACryptoServiceProvider::SignData(const StreamPtr\&, const HashAlgorithmName\&) method

مقدار هش جریان باینری مشخص شده را با استفاده از الگوریتم هش مشخص شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | جریان باینری. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. بازگشت [DSA](../../dsa/) امضا برای داده‌های ورودی. |

## همچنین ببینید

* تعریف نوع [ByteArrayPtr](../../../system/bytearrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [StreamPtr](../../../system/streamptr/)
* کلاس [DSACryptoServiceProvider](../)
* کلاس [Stream](../../../system.io/stream/)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)