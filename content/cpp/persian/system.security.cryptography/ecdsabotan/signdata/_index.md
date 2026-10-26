---
title: SignData()
second_title: مرجع API Aspose.Slides برای C++
description: مقدار هش آرایهٔ دادهٔ مشخص‌شده را محاسبه می‌کند و نتیجه را امضا می‌نماید.
type: docs
weight: 131
url: /fa/system.security.cryptography/ecdsabotan/signdata/
---
## ECDsaBotan::SignData(const ByteArrayPtr\&) method


مقدار هش دادهٔ مشخص‌شده را محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایهٔ دادهٔ ورودی. امضای ECDSA برای دادهٔ ورودی را برمی‌گرداند. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t) method


مقدار هش دادهٔ مشخص‌شده را محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایهٔ دادهٔ ورودی. |
| offset | **int32_t** | جابه‌جایی در **data**. |
| count | **int32_t** | تعداد بایت‌هایی که به عنوان دادهٔ ورودی استفاده می‌شوند. امضای ECDSA برای دادهٔ ورودی را برمی‌گرداند. |

## ECDsaBotan::SignData(const StreamPtr\&) method


مقدار هش جریان باینری مشخص‌شده را محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignData(const StreamPtr &stream)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | جریان باینری. امضای ECDSA برای دادهٔ ورودی را برمی‌گرداند. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, const HashAlgorithmName\&) method


مقدار هش دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, const HashAlgorithmName &hash_algorithm)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایهٔ دادهٔ ورودی. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. امضای ECDSA برای دادهٔ ورودی را برمی‌گرداند. |

## ECDsaBotan::SignData(const ByteArrayPtr\&, int32_t, int32_t, const HashAlgorithmName\&) method


مقدار هش دادهٔ مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const ByteArrayPtr &data, int32_t offset, int32_t count, const HashAlgorithmName &hash_algorithm)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | آرایهٔ دادهٔ ورودی. |
| offset | **int32_t** | جابه‌جایی در **data**. |
| count | **int32_t** | تعداد بایت‌هایی که به عنوان دادهٔ ورودی استفاده می‌شوند. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. امضای ECDSA برای دادهٔ ورودی را برمی‌گرداند. |

## ECDsaBotan::SignData(const StreamPtr\&, const HashAlgorithmName\&) method


مقدار هش جریان باینری مشخص‌شده را با استفاده از الگوریتم هش مشخص‌شده محاسبه می‌کند و نتیجه را امضا می‌نماید.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignData(const StreamPtr &stream, const HashAlgorithmName &hash_algorithm)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [StreamPtr](../../../system/streamptr/)\& | جریان باینری. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | الگوریتم هش. امضای ECDSA برای دادهٔ ورودی را برمی‌گرداند. |

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [StreamPtr](../../../system/streamptr/)
* Class [ECDsaBotan](../)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)