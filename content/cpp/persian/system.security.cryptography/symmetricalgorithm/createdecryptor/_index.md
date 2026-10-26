---
title: CreateDecryptor()
second_title: Aspose.Slides برای C++ مرجع API
description: یک رمزگشا با پارامترهای مرتبط با شیء الگوریتم ایجاد می‌کند.
type: docs
weight: 196
url: /fa/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() متد

یک رمزگشای با پارامترهای مرتبط با شیء الگوریتم ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

### مقدار بازگشت

شیء رمزگشای تازه ایجاد شده.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

یک رمزگشا با پارامترهای صریح ایجاد می‌کند.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | کلید برای استفاده. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مقدار اولیه برای استفاده. |

### مقدار بازگشت

شیء رمزگشای تازه ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICryptoTransform](../../icryptotransform/)
* کلاس [SymmetricAlgorithm](../)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)