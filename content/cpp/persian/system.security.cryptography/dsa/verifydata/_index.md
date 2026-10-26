---
title: VerifyData()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که امضای دادهٔ مشخص شده معتبر باشد.
type: docs
weight: 92
url: /fa/system.security.cryptography/dsa/verifydata/
---
## DSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) متد


بررسی می‌کند که امضای دادهٔ مشخص شده معتبر باشد.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. return true if signature is valid, otherwise - false. |

## DSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) متد


بررسی می‌کند که امضای دادهٔ مشخص شده معتبر باشد.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا شده. |
| offset | **int32_t** | افست در **data**. |
| count | **int32_t** | تعداد بایت‌هایی که باید هش شوند. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. return true if signature is valid, otherwise - false. |

## DSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) متد


بررسی می‌کند که امضای جریان باینری مشخص شده معتبر باشد.

```cpp
bool System::Security::Cryptography::DSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | دادهٔ امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. return true if signature is valid, otherwise - false. |

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* کلاس [DSA](../)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)