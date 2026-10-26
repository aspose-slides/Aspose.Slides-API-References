---
title: CustomLineCap()
second_title: Aspose.Slides برای C++ مرجع API
description: یک نمونه جدید از کلاس CustomLineCap را می‌سازد که سر خط تعریف‌شده توسط کاربر را با ویژگی‌های مشخص‌شده نشان می‌دهد.
type: docs
weight: 1
url: /fa/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) سازنده

یک نمونه جدید از [CustomLineCap](../) کلاس که یک سر خط تعریف‌شده توسط کاربر را با ویژگی‌های مشخص‌شده نشان می‌دهد.

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | پرکننده‌ای را برای سر سفارشی مشخص می‌کند |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | یک طرح کلی برای سر سفارشی را مشخص می‌کند |
| baseCap | [LineCap](../../linecap/) | سر خط پایه‌ای که از آن سر سفارشی ساخته می‌شود |
| baseInset | **float** | فاصله بین خط و سر را مشخص می‌کند |

## موارد مرتبط

* Enum [LineCap](../../linecap/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsPath](../../graphicspath/)
* Class [CustomLineCap](../)
* Namespace [System::Drawing::Drawing2D](../../)
* Library [Aspose.Slides](../../../)