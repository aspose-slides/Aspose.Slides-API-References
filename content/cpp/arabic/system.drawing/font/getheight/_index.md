---
title: GetHeight()
second_title: مرجع API Aspose.Slides للـ C++
description: ترجع المسافة بين السطور للخط الممثل بالكائن الحالي، بوحدة القياس الحالية لكائن Graphics المحدد.
type: docs
weight: 14
url: /ar/system.drawing/font/getheight/
---
## Font::GetHeight(const SharedPtr\<Graphics\>\&) طريقة

تُعيد المسافة بين السطور للخط الممثَل بالكائن الحالي، بوحدة القياس الحالية لكائن [Graphics](../../graphics/) المحدد.

```cpp
float System::Drawing::Font::GetHeight(const SharedPtr<Graphics> &graphics)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| graphics | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | كائن [Graphics](../../graphics/) يحدد وحدات القياس |

## Font::GetHeight(float) طريقة

تُعيد ارتفاع الخط الممثَل بالكائن الحالي عند رسمه على جهاز عرض بدقة عمودية محددة.

```cpp
float System::Drawing::Font::GetHeight(float dpi=DEFAULT_FONT_OPERATIONS_DPI)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| dpi | **float** | دقة العرض العمودية للجهاز |

### قيمة الإرجاع

ارتفاع الخط بالبكسل

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Graphics](../../graphics/)
* فئة [Font](../)
* نطاق اسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)