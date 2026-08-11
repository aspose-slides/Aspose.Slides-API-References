---
title: TransformBlock()
second_title: مرجع API Aspose.Slides برای C++
description: بخش داده‌ها را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌گیرد.
type: docs
weight: 1
url: /fa/system.security.cryptography/icryptotransform/transformblock/
---
## ICryptoTransform::TransformBlock(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<uint8_t\>, int) method

بخش داده‌ها را پردازش می‌کند و داده‌ها را به آرایه خروجی کپی می‌گیرد.

```cpp
virtual int System::Security::Cryptography::ICryptoTransform::TransformBlock(ArrayPtr<uint8_t> inputBuffer, int inputOffset, int inputCount, ArrayPtr<uint8_t> outputBuffer, int outputOffset)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| inputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) برای خواندن داده‌ها از. |
| inputOffset | int | افست بافر ورودی. |
| inputCount | int | تعداد بایت‌های قابل پردازش. |
| outputBuffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | بافر خروجی برای کپی کردن داده‌ها؛ nullptr برای عدم کپی. |
| outputOffset | int | افست بافر خروجی. |

### مقدار بازگشت

تعداد بایت‌های نوشته شده.

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* کلاس [ICryptoTransform](../)
* فضای نام [System::Security::Cryptography](../../)
* کتابخانه [Aspose.Slides](../../../)