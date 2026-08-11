---
title: GetVisualBounds()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على الحدود البصرية للشكل المحسوبة من المحتوى المُرَسَّم.
type: docs
weight: 677
url: /ar/aspose.slides/shape/getvisualbounds/
---
## Shape::GetVisualBounds() طريقة

يحصل على الحدود البصرية للشكل المحسوبة من المحتوى المُرَسَّم.

```cpp
System::Drawing::RectangleF Aspose::Slides::Shape::GetVisualBounds()
```

### قيمة الإرجاع

[System::Drawing::RectangleF](../../../system.drawing/rectanglef/) التي تمثل الحدود البصرية للشكل في إحداثيات الشريحة.

## ملاحظات

المستطيل الذي يتم إرجاعه يمثل الحدود المتمحورة لجميع المحتوى الذي يُنتجه الشكل أثناء العرض في فضاء إحداثيات الشريحة.

قد تختلف هذه الحدود عن حدود نموذج الشكل ([Shape::X](../), [Shape::Y](../), [Shape::Width](../), [Shape::Height](../)) وقد تحتوي على إحداثيات سالبة إذا امتد المحتوى المُرَسَّم إلى ما وراء أصل الشريحة.

تأخذ الحدود البصرية في الاعتبار الجوانب المتعلقة بالعرض مثل التحولات (على سبيل المثال، الدوران)، عرض الحد وتقاطعاته، تخطيط النص والفيض، هندسة [SmartArt](../../../aspose.slides.smartart/)، وغيرها من تأثيرات التخطيط التي تؤثر على المظهر النهائي المعروض للشكل.

الحدود المعادة غير مقصوصة إلى مستطيل الشريحة.

## انظر أيضا

* الفئة [RectangleF](../../../system.drawing/rectanglef/)
* الفئة [Shape](../)
* مساحة الاسم [Aspose::Slides](../../)
* المكتبة [Aspose.Slides](../../../)