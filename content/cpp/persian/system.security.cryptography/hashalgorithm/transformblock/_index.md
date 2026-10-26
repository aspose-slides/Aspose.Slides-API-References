---
title: TransformBlock()
second_title: مرجع API Aspose.Slides برای C++
description: بلوک داده‌ها را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌کند.
type: docs
weight: 66
url: /fa/system.security.cryptography/hashalgorithm/transformblock/
---
## HashAlgorithm::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method


بلوک داده‌ها را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌کند.

```cpp
int System::Security::Cryptography::HashAlgorithm::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن داده‌ها از |
| inputOffset | int | جابه‌جایی بافر ورودی |
| inputCount | int | تعداد بایت‌ها برای پردازش |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر خروجی برای کپی کردن داده‌ها؛ nullptr برای عدم کپی |
| outputOffset | int | جابه‌جایی بافر خروجی |

### مقدار بازگشت

تعداد بایت‌های نوشته شده.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HashAlgorithm](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)