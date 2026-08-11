---
title: CreateSignature()
second_title: Aspose.Slides برای C++ مرجع API
description: امضا را برای دادهٔ مشخص‌شده ایجاد می‌کند.
type: docs
weight: 1
url: /fa/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) متد

امضا را برای دادهٔ مشخص‌شده ایجاد می‌کند.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) برای محاسبهٔ هش. |

### Return Value

امضای محاسبه‌شده به شکل آرایه بایت.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) متد

امضا را برای مقدار هش مشخص‌شده ایجاد می‌کند.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### Arguments

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | الگوریتم هش برای استفاده هنگام ایجاد امضا. |

### Return Value

امضای محاسبه‌شده به شکل آرایه بایت.

## همچنین ببینید

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [AsymmetricSignatureFormatter](../)
* Class [HashAlgorithm](../../hashalgorithm/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)