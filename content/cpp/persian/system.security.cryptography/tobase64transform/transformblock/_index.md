---
title: TransformBlock()
second_title: مرجع API Aspose.Slides برای C++
description: یک بلوک از داده‌ها را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌کند.
type: docs
weight: 53
url: /fa/system.security.cryptography/tobase64transform/transformblock/
---
## ToBase64Transform::TransformBlock(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, System::ArrayPtr\<uint8_t\>, int32_t) متد

یک بلوک از داده‌ها را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌کند.

```cpp
int32_t System::Security::Cryptography::ToBase64Transform::TransformBlock(System::ArrayPtr<uint8_t> inputBuffer, int32_t inputOffset, int32_t inputCount, System::ArrayPtr<uint8_t> outputBuffer, int32_t outputOffset)
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن داده‌ها. |
| inputOffset | **int32_t** | افست بافر ورودی. |
| inputCount | **int32_t** | تعداد بایت‌ها برای پردازش. |
| outputBuffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر خروجی برای کپی کردن داده‌ها؛ nullptr برای عدم کپی. |
| outputOffset | **int32_t** | افست بافر خروجی. |

### مقدار بازگشتی

تعداد بایت‌های نوشته شده.

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [ToBase64Transform](../)
* فضای‌نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)