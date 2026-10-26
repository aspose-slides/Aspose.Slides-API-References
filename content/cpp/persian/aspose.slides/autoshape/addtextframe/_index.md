---
title: AddTextFrame()
second_title: مرجع API Aspose.Slides برای C++
description: یک TextFrame جدید به شکل اضافه می‌کند. اگر شکل قبلاً TextFrame داشته باشد، فقط متن آن را تغییر می‌دهد.
type: docs
weight: 66
url: /fa/aspose.slides/autoshape/addtextframe/
---
## AutoShape::AddTextFrame(System::String) روش

یک [TextFrame](../../textframe/) جدید به یک شکل اضافه می‌کند. اگر شکل قبلاً [TextFrame](../../textframe/) داشته باشد، فقط متن آن را تغییر می‌دهد.

```cpp
System::SharedPtr<ITextFrame> Aspose::Slides::AutoShape::AddTextFrame(System::String text) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | متن پیش‌فرض برای یک [TextFrame](../../textframe/) جدید. |

## توضیحات

کد نمونه زیر نشان می‌دهد چگونه متن علامت آب را در PowerPoint [Presentation](../../presentation/) اضافه کنید.
```cpp
auto presentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auto watermarkShape = slide->get_Shapes()->AddAutoShape(ShapeType::Triangle, 0.0f, 0.0f, 150.0f, 50.0f);
System::SharedPtr<ITextFrame> watermarkTextFrame = watermarkShape->AddTextFrame(u"Watermark");
```
مثال زیر نشان می‌دهد چگونه یک Text Box روی [Slide](../../slide/) ایجاد کنید.
```cpp
// یک Presentation را نمونه‌سازی می‌کند
auto pres = System::MakeObject<Presentation>();

// اسلاید اول ارائه را دریافت می‌کند
auto slide = pres->get_Slides()->idx_get(0);
// یک AutoShape با نوع Rectangle اضافه می‌کند
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
// یک TextFrame به Rectangle اضافه می‌کند
shape->AddTextFrame(u" ");
// دسترسی به TextFrame
auto txtFrame = shape->get_TextFrame();
// شیء Paragraph را برای TextFrame ایجاد می‌کند
auto para = txtFrame->get_Paragraphs()->idx_get(0);
// شیء Portion را برای پاراگراف ایجاد می‌کند
auto portion = para->get_Portions()->idx_get(0);
// متن را تنظیم می‌کند
portion->set_Text(u"Aspose TextBox");
// ارائه را در دیسک ذخیره می‌کند
pres->Save(u"TextBox_out.pptx", SaveFormat::Pptx);
```
مثال زیر نشان می‌دهد چگونه ستونی به Text Box اضافه کنید.
```cpp
auto presentation = System::MakeObject<Presentation>();

// اسلاید اول ارائه را دریافت می‌کند
auto slide = presentation->get_Slides()->idx_get(0);
// یک AutoShape با نوع Rectangle اضافه می‌کند
auto shape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
// یک TextFrame به Rectangle اضافه می‌کند
shape->AddTextFrame(System::String(u"All these columns are limited to be within a single text container -- ") +
                    u"you can add or delete text and the new or remaining text automatically adjusts " +
                    u"itself to flow within the container. You cannot have text flow from one container " +
                    u"to other though -- we told you PowerPoint's column options for text are limited!");
// فرمت متن TextFrame را دریافت می‌کند
auto format = shape->get_TextFrame()->get_TextFrameFormat();
// تعداد ستون‌ها در TextFrame را تعیین می‌کند
format->set_ColumnCount(3);
// فاصله بین ستون‌ها را تعیین می‌کند
format->set_ColumnSpacing(10);
// ارائه را ذخیره می‌کند
presentation->Save(u"ColumnCount.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ITextFrame](../../itextframe/)
* Class [String](../../../system/string/)
* Class [AutoShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)