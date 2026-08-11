---
title: CreateEncryptor()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شیء رمزنگار را با پارامترهای صریح ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.security.cryptography/rijndaelmanaged/createencryptor/
---
## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

یک شیء رمزنگار با پارامترهای صریح ایجاد می‌کند.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### آرگومان‌ها

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | کلید رمزنگاری به شکل آرایه بایت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مقدار اولیه به شکل آرایه بایت. |

### مقدار بازگشتی

شیء رمزنگار تازه ساخته‌شده.

## RijndaelManaged::CreateEncryptor() متد

یک شیء رمزنگار با پارامترهای تعریف‌شده توسط شیء الگوریتم ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

یک شیء رمزنگار با پارامترهای تعریف‌شده توسط شیء الگوریتم ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICryptoTransform](../../icryptotransform/)
* کلاس [RijndaelManaged](../)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)