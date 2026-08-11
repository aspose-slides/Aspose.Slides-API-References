---
title: Fallback()
second_title: Aspose.Slides برای مرجع API C++
description: رویه واقعی fallback را اجرا می‌کند.
type: docs
weight: 14
url: /fa/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) متد

رویه واقعی fallback را اجرا می‌کند.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) از بایت‌ها شامل بایتی که مفسر نتوانست رمزگشایی کند. |
| index | int | [Index](../../../system/index/) از بایتی که خطا را ایجاد کرد. |

### مقدار بازگشت

True اگر بافر بایت‌های ناشناخته را پردازش کند، false اگر آن‌ها را نادیده بگیرد.

## موارد مرتبط

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [DecoderFallbackBuffer](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)