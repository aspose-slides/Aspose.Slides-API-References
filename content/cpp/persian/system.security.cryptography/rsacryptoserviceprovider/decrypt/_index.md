---
title: Decrypt()
second_title: Aspose.Slides برای C++ راهنمای API
description: پیام را رمزگشایی می‌کند. پیاده‌سازی نشده است.
type: docs
weight: 105
url: /fa/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) method

پیام را رمزگشایی می‌کند. پیاده‌سازی نشده است.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) برای رمزگشایی. |
| use_oaep | **bool** | True برای استفاده از padding OAEP، false برای استفاده از padding PKCS#1 v1.5. |

### Return Value

آرایه داده‌های رمزگشایی شده.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) method

داده‌های ورودی را با استفاده از حالت padding مشخص شده رمزگشایی می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) آرایه برای رمزگشایی. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | حالت پرکننده. |

### Return Value

داده‌های رمزگشایی شده به قالب آرایه بایت.

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSACryptoServiceProvider](../)
* Class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)