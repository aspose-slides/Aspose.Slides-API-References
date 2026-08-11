---
title: CreateEncryptor()
second_title: Aspose.Slides برای C++ مرجع API
description: یک شیء رمزنگار با پارامترهای صریح ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

یک شیء رمزنگار با پارامترهای صریح ایجاد می‌کند.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | کلید رمزنگاری به صورت آرایه بایت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مقدار اولیه به صورت آرایه بایت. |

### مقدار بازگشتی

شیء رمزنگار تازه ایجاد شده.

## TripleDESManaged::CreateEncryptor() متد

یک شیء رمزنگار با پارامترهای تعریف شده توسط شیء الگوریتم ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

یک شیء رمزنگار با پارامترهای تعریف شده توسط شیء الگوریتم ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)