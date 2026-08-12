---
title: get_ColumnCount()
second_title: Aspose.Slides สำหรับ C++ เอกสารอ้างอิง API
description: คืนค่าจำนวนคอลัมน์ในพื้นที่ข้อความ. ค่าดังกล่าวต้องเป็นจำนวนบวก. หรือไม่ค่าจะถูกตั้งเป็นศูนย์. ค่า 0 หมายถึงค่าที่ไม่กำหนด. อ่าน int32_t.
type: docs
weight: 248
url: /th/aspose.slides/textframeformat/get_columncount/
---
## TextFrameFormat::get_ColumnCount() เมธอด


คืนค่าจำนวนคอลัมน์ในพื้นที่ข้อความ ค่านี้จะต้องเป็นจำนวนบวก มิฉะนั้น ค่าจะถูกตั้งเป็นศูนย์ ค่า 0 หมายถึงค่าว่างเปล่า อ่าน **int32_t**.

```cpp
int32_t Aspose::Slides::TextFrameFormat::get_ColumnCount() override
```

## หมายเหตุ


ตัวอย่างโค้ดต่อไปนี้แสดงวิธีเพิ่มคอลัมน์ใน Text frame ภายใน PowerPoint [Presentation](../../presentation/). 
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

## ดูเพิ่มเติม

* คลาส [TextFrameFormat](../)
* เนมสเปซ [Aspose::Slides](../../)
* ไลบรารี [Aspose.Slides](../../../)