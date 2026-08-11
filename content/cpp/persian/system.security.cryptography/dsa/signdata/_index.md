---
title: SignData()
second_title: Aspose.Slides برای C++ مرجع API
description: مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.
type: docs
weight: 79
url: /fa/system.security.cryptography/dsa/signdata/
---
## DSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) متد

مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه داده ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوی هش. امضای [DSA](../) را برای داده ورودی باز می‌گرداند. |

## DSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) متد

مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه داده ورودی. |
| offset | **int32_t** | موقعیت در **data**. |
| count | **int32_t** | تعداد بایت‌های استفاده‌شده به عنوان داده ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوی هش. امضای [DSA](../) را برای داده ورودی باز می‌گرداند. |

## DSA::SignData(const StreamPtr\&, const HashAlgorithmName\&) متد

مقدار هش جریان باینری مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::DSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | جریان باینری. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوی هش. امضای [DSA](../) را برای داده ورودی باز می‌گرداند. |

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [DSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)