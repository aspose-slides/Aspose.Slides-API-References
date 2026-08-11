---
title: ReadBlock()
second_title: مرجع API Aspose.Slides برای C++
description: حداکثر تعداد کاراکترهای مشخص‌شده را از خوانندهٔ متنی کنونی می‌خواند و داده‌ها را در بافر می‌نویسد، شروع از شاخص مشخص‌شده.
type: docs
weight: 53
url: /fa/system.io/textreader/readblock/
---
## TextReader::ReadBlock(ArrayPtr\<char_t\>, int, int) method

حداکثر تعداد کاراکترهای مشخص‌شده را از خوانندهٔ متنی فعلی می‌خواند و داده‌ها را در یک بافر می‌نویسد، شروع از شاخص مشخص‌شده.

```cpp
virtual int System::IO::TextReader::ReadBlock(ArrayPtr<char_t> buffer, int index, int count)
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | یک **buffer** کاراکتری برای نوشتن داده‌های خوانده شده |
| index | int | یک شاخص صفرمحور در **buffer** برای شروع نوشتن |
| count | int | حداکثر تعداد کاراکترهایی که باید خوانده شوند |

### مقدار بازگشت

تعداد واقعی کاراکترهای خوانده شده

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextReader](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)