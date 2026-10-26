---
title: CreateDecryptor()
second_title: مرجع API Aspose.Slides برای C++
description: یک شی‌ء رمزگشا را با پارامترهای صریح ایجاد می‌کند.
type: docs
weight: 14
url: /fa/system.security.cryptography/tripledesmanaged/createdecryptor/
---
## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

یک شی‌ء رمزگشا با پارامترهای صریح ایجاد می‌کند.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | کلید رمزنگاری به شکل آرایه بایت. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مقدار اولیه به شکل آرایه بایت. |

### مقدار بازگشتی

شی‌ء رمزگشای تازه ایجاد شده.

## TripleDESManaged::CreateDecryptor() متد

یک شی‌ء رمزگشا با پارامترهایی که توسط شیء الگوریتم تعریف شده‌اند ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## TripleDESManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

یک شی‌ء رمزگشا با پارامترهایی که توسط شیء الگوریتم تعریف شده‌اند ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [TripleDESManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)