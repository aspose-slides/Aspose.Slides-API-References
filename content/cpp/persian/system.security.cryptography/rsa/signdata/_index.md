---
title: SignData()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش و پدینگ مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.
type: docs
weight: 131
url: /fa/system.security.cryptography/rsa/signdata/
---
## RSA::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) متد

مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش و پدینگ مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه داده ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | حالت پدینگ. مقدار [RSA](../) امضا برای داده ورودی را برمی‌گرداند. |

## RSA::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) متد

مقدار هش آرایه دادهٔ مشخص‌شده را با استفاده از الگوریتم هش و پدینگ مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایه داده ورودی. |
| offset | **int32_t** | موقعیت در **data**. |
| count | **int32_t** | تعداد بایت‌هایی که به عنوان داده ورودی استفاده می‌شوند. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | حالت پدینگ. مقدار [RSA](../) امضا برای داده ورودی را برمی‌گرداند. |

## RSA::SignData(const StreamPtr\&, const HashAlgorithmName\&, const SharedPtr\<RSASignaturePadding\>\&) متد

مقدار هش جریان باینری مشخص‌شده را با استفاده از الگوریتم هش و پدینگ مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::RSA::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm, const SharedPtr<RSASignaturePadding> &padding)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | جریان باینری. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. |
| padding | const [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\>\& | حالت پدینگ. مقدار [RSA](../) امضا برای داده ورودی را برمی‌گرداند. |

## مراجع

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSA](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)