---
title: GetLinesCount()
second_title: Aspose.Slides برای C++ مرجع API
description: دریافت تعداد خطوط در یک پاراگراف.
type: docs
weight: 105
url: /fa/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() متد

تعداد خطوط در یک پاراگراف را دریافت می‌کند.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```

### مقدار بازگشتی

تعداد خطوط در یک پاراگراف

## ملاحظات

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

## همچنین ببینید

* کلاس [IParagraph](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)