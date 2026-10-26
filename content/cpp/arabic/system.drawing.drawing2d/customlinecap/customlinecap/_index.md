---
title: CustomLineCap()
second_title: Aspose.Slides لـ C++ مرجع API
description: ينشئ نسخة جديدة من الفئة CustomLineCap التي تمثل غطاء خط معرف من قبل المستخدم بالخصائص المحددة.
type: docs
weight: 1
url: /ar/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) المُنشئ

ينشئ نسخة جديدة من الفئة [CustomLineCap](../) التي تمثل غطاء خط معرف من قبل المستخدم بالخصائص المحددة.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | يحدد تعبئة للغطاء المخصص |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | يحدد مخططًا للغطاء المخصص |
| baseCap | [LineCap](../../linecap/) | غطاء الخط الأساسي الذي يُنشأ منه الغطاء المخصص |
| baseInset | **float** | يحدد المسافة بين الخط والغطاء |

## انظر أيضاً

* تعداد [LineCap](../../linecap/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [GraphicsPath](../../graphicspath/)
* فئة [CustomLineCap](../)
* فضاء الاسم [System::Drawing::Drawing2D](../../)
* مكتبة [Aspose.Slides](../../../)