---
title: CreateEncryptor()
second_title: Aspose.Slides برای C++ مرجع API
description: رمزگذار را با پارامترهای مرتبط با شیء الگوریتم ایجاد می‌کند.
type: docs
weight: 183
url: /fa/system.security.cryptography/symmetricalgorithm/createencryptor/
---
## SymmetricAlgorithm::CreateEncryptor() متد

Creates encryptor with parameters associated with algorithm object.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

### مقدار بازگشت

Newly created encryptor object.

## SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) متد

Creates encryptor with explicit parameters.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | کلید مورد استفاده. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مقدار اولیه مورد استفاده. |

### مقدار بازگشت

Newly created encryptor object.

## مراجعه

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICryptoTransform](../../icryptotransform/)
* کلاس [SymmetricAlgorithm](../)
* فضای‌نام [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)