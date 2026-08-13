---
title: set_ColumnCount()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 텍스트 영역의 열 수를 설정합니다. 이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. 값 0은 정의되지 않은 값을 의미합니다. int32_t를 씁니다.
type: docs
weight: 261
url: /ko/aspose.slides/textframeformat/set_columncount/
---
## TextFrameFormat::set_ColumnCount(int32_t) 메서드


텍스트 영역의 열 수를 설정합니다. 이 값은 양수여야 합니다. 그렇지 않으면 값이 0으로 설정됩니다. 값 0은 정의되지 않은 값을 의미합니다. **int32_t**를 씁니다.

```cpp
void Aspose::Slides::TextFrameFormat::set_ColumnCount(int32_t value) override
```

## 비고


다음 샘플 코드는 PowerPoint [Presentation](../../presentation/) 내부의 텍스트 프레임에 열을 추가하는 방법을 보여줍니다.
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

## 관련 항목

* 클래스 [TextFrameFormat](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)