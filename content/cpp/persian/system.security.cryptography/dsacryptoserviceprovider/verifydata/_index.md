---
title: VerifyData()
second_title: مرجع API Aspose.Slides برای C++
description: امضای داده را بررسی می‌کند.
type: docs
weight: 209
url: /fa/system.security.cryptography/dsacryptoserviceprovider/verifydata/
---
## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) method

امضای داده را بررسی می‌کند.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const ByteArrayPtr &signature)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) برای بررسی امضا. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | امضا به‌دست‌آمده. |

## مقدار بازگشت

True اگر امضا معتبر باشد، false در غیر اینصورت.

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

از صحت امضای دادهٔ مشخص‌شده اطمینان حاصل می‌کند.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورتی که امضا معتبر باشد true، در غیر اینصورت false. |

## DSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) method

از صحت امضای دادهٔ مشخص‌شده اطمینان حاصل می‌کند.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده امضا شده. |
| offset | **int32_t** | موقعیت در **data**. |
| count | **int32_t** | تعداد بایت‌ها برای هش کردن. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورتی که امضا معتبر باشد true، در غیر اینصورت false. |

## DSACryptoServiceProvider::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) method

از صحت امضای جریان باینری مشخص‌شده اطمینان حاصل می‌کند.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | داده امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورتی که امضا معتبر باشد true، در غیر اینصورت false. |

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* کلاس [DSACryptoServiceProvider](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* فضای نام [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)