---
title: Encrypt()
second_title: Aspose.Slides برای C++ مرجع API
description: پیغام را رمزنگاری می‌کند. پیاده‌سازی نشده است.
type: docs
weight: 118
url: /fa/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr&, bool) متد

پیام را رمزنگاری می‌کند. پیاده‌سازی نشده است.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) برای رمزنگاری. |
| use_oaep | **bool** | True برای استفاده از پدینگ OAEP، false برای استفاده از پدینگ PKCS#1 v1.5. |

### مقدار بازگشتی

آرایه داده‌های رمزگذاری‌شده.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) متد

داده‌های ورودی را با استفاده از حالت پدینگ مشخص شده رمزنگاری می‌کند.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) آرایه برای رمزنگاری. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | حالت پدینگ. |

### مقدار بازگشتی

داده‌های رمزگذاری‌شده به فرمت آرایه بایت.

## موارد مرتبط

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [RSACryptoServiceProvider](../)
* کلاس [RSAEncryptionPadding](../../rsaencryptionpadding/)
* فضای نام [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)