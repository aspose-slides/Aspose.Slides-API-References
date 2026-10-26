---
title: VerifyData()
second_title: Aspose.Slides برای C++ مرجع API
description: تأیید می‌کند که امضای داده‌های مشخص شده معتبر است.
type: docs
weight: 157
url: /fa/system.security.cryptography/rsa/verifydata/
---
## RSA::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) متد

تأیید می‌کند که امضای داده‌های مشخص شده معتبر است.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | حالت padding. در صورت معتبر بودن امضا true بر می‌گرداند، در غیر این صورت false. |

## RSA::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) متد

تأیید می‌کند که امضای داده‌های مشخص شده معتبر است.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا شده. |
| offset | **int32_t** | موقعیت در **data**. |
| count | **int32_t** | تعداد بایت‌هایی که باید هش شوند. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | حالت padding. در صورت معتبر بودن امضا true بر می‌گرداند، در غیر این صورت false. |

## RSA::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) متد

تأیید می‌کند که امضای جریان باینری مشخص شده معتبر است.

```cpp
bool System::Security::Cryptography::RSA::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | دادهٔ امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | دادهٔ امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | حالت padding. در صورت معتبر بودن امضا true بر می‌گرداند، در غیر این صورت false. |

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* کلاس [RSASignaturePadding](../../rsasignaturepadding/)
* کلاس [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* فضای نام [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)