---
title: FromStream()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: ينشئ كائن Image من الدفق المحدد.
type: docs
weight: 339
url: /ar/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) طريقة

ينشئ كائن [Image](../) من الدفق المحدد.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### المعلمات

| Parameter | Type | Description |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | دفق يحتوي على بيانات الصورة |
| use_embedded_color_management | **bool** | IGNORED |
| validate_image_data | **bool** | IGNORED |

### قيمة الإرجاع

مؤشر مشترك إلى كائن [Image](../) الذي تم إنشاؤه.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Image](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)