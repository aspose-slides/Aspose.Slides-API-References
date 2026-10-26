---
title: FromStream()
second_title: Aspose.Slides برای مرجع API C++
description: یک شیء Image را از جریان مشخص شده ایجاد می‌کند.
type: docs
weight: 339
url: /fa/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) متد

یک شیء [Image](../) را از جریان مشخص شده ایجاد می‌کند.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | جریانی که حاوی داده‌های تصویر است |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### مقدار بازگشتی

یک shared pointer به شیء [Image](../) ایجاد شده.

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [Image](../)
* کلاس [Stream](../../../system.io/stream/)
* نام‌فضا [System::Drawing](../../)
* Library [Aspose.Slides](../../../)