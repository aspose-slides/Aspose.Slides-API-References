---
title: SignData()
second_title: Aspose.Slides برای مرجع API C++
description: امضای مقدار ورودی مشخص را محاسبه می‌کند.
type: docs
weight: 183
url: /fa/system.security.cryptography/rsacryptoserviceprovider/signdata/
---
## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&) method


امضای مقدار ورودی مشخص را محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) برای خواندن داده‌های ورودی. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الگوریتم هش برای استفاده. |

### مقدار بازگشتی

[RSA](../../rsa/) امضا برای داده‌های مشخص.

## RSACryptoServiceProvider::SignData(const SharedPtr\<IO::Stream\>\&, const SharedPtr\<Object\>\&) method


امضای مقدار ورودی مشخص را محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const SharedPtr<IO::Stream> &input_stream, const SharedPtr<Object> &halg)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| input_stream | const [SharedPtr](../../../system/sharedptr/)\<[IO::Stream](../../../system.io/stream/)\>\& | جریان برای خواندن داده‌های امضا شده. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الگوریتم هش برای استفاده. |

### مقدار بازگشتی

[RSA](../../rsa/) امضا برای داده‌های مشخص.

## RSACryptoServiceProvider::SignData(const ByteArrayPtr\&, int32_t, int32_t, const SharedPtr\<Object\>\&) method


امضای مقدار ورودی مشخص را محاسبه می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignData(const ByteArrayPtr &buffer, int32_t offset, int32_t count, const SharedPtr<Object> &halg)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Buffer](../../../system/buffer/) برای خواندن داده‌های ورودی. |
| offset | **int32_t** | اندیس آغازین بخش از بافر ورودی. |
| count | **int32_t** | اندازه بخش از بافر ورودی. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | الگوریتم هش برای استفاده. |

### مقدار بازگشتی

[RSA](../../rsa/) امضا برای داده‌های مشخص.

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Object](../../../system/object/)
* Class [RSACryptoServiceProvider](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)