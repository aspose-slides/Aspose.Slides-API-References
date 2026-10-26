---
title: GetLinesCount()
second_title: مرجع API Aspose.Slides برای C++
description: دریافت تعداد خطوط در یک پاراگراف.
type: docs
weight: 118
url: /fa/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() متد


تعداد خطوط در یک پاراگراف را دریافت کنید.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```


### مقدار بازگشتی

تعداد خطوط در یک پاراگراف
## توضیحات


مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```


## موارد مرتبط

* کلاس [Paragraph](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)