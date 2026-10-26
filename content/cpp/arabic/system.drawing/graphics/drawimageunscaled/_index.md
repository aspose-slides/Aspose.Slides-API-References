---
title: DrawImageUnscaled()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: يرسم الصورة المحددة باستخدام حجمها الفعلي الأصلي في الموقع المحدد.
type: docs
weight: 443
url: /ar/system.drawing/graphics/drawimageunscaled/
---
## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int) طريقة

يرسم الصورة المحددة باستخدام حجمها الفعلي الأصلي في الموقع المحدد.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة المراد رسمها |
| x | int | إحداثي X للزاوية العليا اليسرى للصورة المرسومة |
| y | int | إحداثي Y للزاوية العليا اليسرى للصورة المرسومة |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, int, int, int, int) طريقة

يرسم صورة محددة باستخدام حجمها الفعلي الأصلي في موقع محدد.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة المراد رسمها |
| x | int | إحداثي X للزاوية العليا اليسرى للصورة المرسومة |
| y | int | إحداثي Y للزاوية العليا اليسرى للصورة المرسومة |
| width | int | غير مستخدم |
| height | int | غير مستخدم |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Rectangle\&) طريقة

يرسم صورة محددة باستخدام حجمها الفعلي الأصلي في موقع محدد.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Rectangle &rect)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة المراد رسمها |
| rect | const [Rectangle](../../rectangle/)\& | المستطيل الذي يحدد الزاوية العليا اليسرى للصورة المرسومة. خصائص X و Y للمستطيل تحدد الزاوية العليا اليسرى. قيم العرض والارتفاع يتم تجاهلها. |

## Graphics::DrawImageUnscaled(const SharedPtr\<Image\>\&, const Point\&) طريقة

يرسم صورة محددة باستخدام حجمها الفعلي الأصلي في موقع محدد.

```cpp
void System::Drawing::Graphics::DrawImageUnscaled(const SharedPtr<Image> &image, const Point &point)
```

### المعاملات

| معامل | نوع | الوصف |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة المراد رسمها |
| point | const [Point](../../point/)\& | الهيكل [Point](../../point/) الذي يحدد الزاوية العليا اليسرى للصورة المرسومة. |

## أنظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [Point](../../point/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)