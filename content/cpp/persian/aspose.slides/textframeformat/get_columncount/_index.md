---
title: get_ColumnCount()
second_title: Aspose.Slides برای C++ مرجع API
description: تعداد ستون‌ها را در ناحیه متن برمی‌گرداند. این مقدار باید عددی مثبت باشد. در غیر این صورت، مقدار به صفر تنظیم می‌شود. مقدار 0 به معنای مقدار تعریف نشده است. با نوع int32_t خوانده می‌شود.
type: docs
weight: 248
url: /fa/aspose.slides/textframeformat/get_columncount/
---
## TextFrameFormat::get_ColumnCount() متد

تعداد ستون‌ها در ناحیه متن را برمی‌گرداند. این مقدار باید عددی مثبت باشد. در غیر اینصورت، مقدار به صفر تنظیم می‌شود. مقدار ۰ به معنی مقدار تعریف نشده است. خواندن **int32_t**.

```cpp
int32_t Aspose::Slides::TextFrameFormat::get_ColumnCount() override
```

## توضیحات

کد نمونه زیر نشان می‌دهد چگونه ستونی به فریم متن در یک PowerPoint [Presentation](../../presentation/) اضافه کنیم.
```cpp
System::String outPptxFileName = u"ColumnsTest.pptx";

auto pres = System::MakeObject<Presentation>();

auto shape1 = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 100.0f, 100.0f, 300.0f, 300.0f);
auto format = System::ExplicitCast<Aspose::Slides::TextFrameFormat>(shape1->get_TextFrame()->get_TextFrameFormat());
format->set_ColumnCount(2);
shape1->get_TextFrame()->set_Text(System::String(u"All these columns are forced to stay within a single text container -- ") + u"you can add or delete text - and the new or remaining text automatically adjusts " + u"itself to stay within the container. You cannot have text spill over from one container " + u"to other, though -- because PowerPoint's column options for text are limited!");
pres->Save(outPptxFileName, Aspose::Slides::Export::SaveFormat::Pptx);


{
    auto test = System::MakeObject<Presentation>(outPptxFileName);
    assert(2 == (System::ExplicitCast<Aspose::Slides::AutoShape>(test->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)))->get_TextFrame()->get_TextFrameFormat()->get_ColumnCount());
    assert(std::numeric_limits<double>::quiet_NaN() == (System::ExplicitCast<Aspose::Slides::AutoShape>(test->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)))->get_TextFrame()->get_TextFrameFormat()->get_ColumnSpacing());
}

format->set_ColumnSpacing(20);
pres->Save(outPptxFileName, SaveFormat::Pptx);

{
    auto test = System::MakeObject<Presentation>(outPptxFileName);
    assert(2 == (System::ExplicitCast<Aspose::Slides::AutoShape>(test->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)))->get_TextFrame()->get_TextFrameFormat()->get_ColumnCount());
    assert(20 == (System::ExplicitCast<Aspose::Slides::AutoShape>(test->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)))->get_TextFrame()->get_TextFrameFormat()->get_ColumnSpacing());
}

format->set_ColumnCount(3);
format->set_ColumnSpacing(15);
pres->Save(outPptxFileName, SaveFormat::Pptx);

{
    auto test = System::MakeObject<Presentation>(outPptxFileName);
    assert(3 == (System::ExplicitCast<Aspose::Slides::AutoShape>(test->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)))->get_TextFrame()->get_TextFrameFormat()->get_ColumnCount());
    assert(15 == (System::ExplicitCast<Aspose::Slides::AutoShape>(test->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)))->get_TextFrame()->get_TextFrameFormat()->get_ColumnSpacing());
}
```

## موارد مرتبط

* کلاس [TextFrameFormat](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)