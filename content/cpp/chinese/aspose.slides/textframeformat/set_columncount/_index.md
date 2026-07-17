---
title: set_ColumnCount()
second_title: Aspose.Slides for C++ API 参考
description: 设置文本区域中的列数。此值必须是正数。否则，值将被设置为零。值 0 表示未定义的值。写入 int32_t。
type: docs
weight: 261
url: /zh/aspose.slides/textframeformat/set_columncount/
---
## TextFrameFormat::set_ColumnCount(int32_t) 方法

设置文本区域中的列数。此值必须是正数。否则，值将被设置为零。值 0 表示未定义值。写入 **int32_t**。

```cpp
void Aspose::Slides::TextFrameFormat::set_ColumnCount(int32_t value) override
```

## 备注

以下示例代码展示了如何在 PowerPoint [Presentation](../../presentation/) 中的文本框添加列。

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

## 另请参见

* 类 [TextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)