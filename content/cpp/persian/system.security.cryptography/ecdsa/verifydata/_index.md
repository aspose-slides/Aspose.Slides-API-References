---
title: VerifyData()
second_title: Aspose.Slides برای C++ - مرجع API
description: بررسی می‌کند که امضای داده‌های مشخص شده معتبر باشد.
type: docs
weight: 105
url: /fa/system.security.cryptography/ecdsa/verifydata/
---
## ECDsa::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) متد


بررسی می‌کند که امضای داده‌های مشخص شده معتبر باشد.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورت معتبر بودن امضا true بر می‌گرداند، در غیر این صورت false. |

## ECDsa::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) متد


بررسی می‌کند که امضای داده‌های مشخص شده معتبر باشد.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا شده. |
| offset | **int32_t** | انحراف در **data**. |
| count | **int32_t** | تعداد بایت‌هایی که باید هش شوند. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورت معتبر بودن امضا true بر می‌گرداند، در غیر این صورت false. |

## ECDsa::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) متد


بررسی می‌کند که امضای جریان باینری مشخص شده معتبر باشد.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | داده‌ی امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورت معتبر بودن امضا true بر می‌گرداند، در غیر این صورت false. |

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsa](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)