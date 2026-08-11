---
title: VerifyData()
second_title: Aspose.Slides برای C++ مرجع API
description: بررسی می‌کند که امضای داده‌های مشخص‌شده معتبر باشد.
type: docs
weight: 170
url: /fa/system.security.cryptography/ecdsabotan/verifydata/
---
## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&) متد

امضای داده‌های مشخص‌شده را اعتبارسنجی می‌کند.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. در صورتی که امضا معتبر باشد true برگردانده می‌شود، در غیر این صورت false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&) متد

امضای داده‌های مشخص‌شده را اعتبارسنجی می‌کند.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا شده. |
| offset | **int32_t** | جابجایی در **data**. |
| count | **int32_t** | تعداد بایت‌ها برای هش‌گذاری. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. در صورتی که امضا معتبر باشد true برگردانده می‌شود، در غیر این صورت false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&) متد

امضای جریان باینری مشخص‌شده را اعتبارسنجی می‌کند.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | داده‌ی امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. در صورتی که امضا معتبر باشد true برگردانده می‌شود، در غیر این صورت false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) متد

امضای داده‌های مشخص‌شده را اعتبارسنجی می‌کند.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورتی که امضا معتبر باشد true برگردانده می‌شود، در غیر این صورت false. |

## ECDsaBotan::VerifyData(const ByteArrayPtr\&, int32_t, int32_t, const ByteArrayPtr\&, const HashAlgorithmName\&) متد

امضای داده‌های مشخص‌شده را اعتبارسنجی می‌کند.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const ByteArrayPtr &data, int32_t offset, int32_t count, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا شده. |
| offset | **int32_t** | جابجایی در **data**. |
| count | **int32_t** | تعداد بایت‌ها برای هش‌گذاری. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورتی که امضا معتبر باشد true برگردانده می‌شود، در غیر این صورت false. |

## ECDsaBotan::VerifyData(const StreamPtr\&, const ByteArrayPtr\&, const HashAlgorithmName\&) متد

امضای جریان باینری مشخص‌شده را اعتبارسنجی می‌کند.

```cpp
bool System::Security::Cryptography::ECDsa::VerifyData(const StreamPtr &stream, const ByteArrayPtr &signature, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | داده‌ی امضا شده. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | داده‌ی امضا. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. در صورتی که امضا معتبر باشد true برگردانده می‌شود، در غیر این صورت false. |

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* کلاس [ECDsaBotan](../)
* ساختار [HashAlgorithmName](../../hashalgorithmname/)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)