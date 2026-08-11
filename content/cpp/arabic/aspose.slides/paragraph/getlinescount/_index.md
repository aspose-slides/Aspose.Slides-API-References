---
title: GetLinesCount()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: احصل على عدد الأسطر في الفقرة.
type: docs
weight: 118
url: /ar/aspose.slides/paragraph/getlinescount/
---
## Paragraph::GetLinesCount() طريقة


عدد الأسطر في الفقرة.

```cpp
int32_t Aspose::Slides::Paragraph::GetLinesCount() override
```


### قيمة الإرجاع

عدد الأسطر في الفقرة
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


## انظر أيضًا

* فئة [Paragraph](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)