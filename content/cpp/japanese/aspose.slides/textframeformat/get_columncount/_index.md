---
title: get_ColumnCount()
second_title: Aspose.Slides for C++ API リファレンス
description: テキスト領域の列数を返します。この値は正の数である必要があります。そうでない場合、値は 0 に設定されます。値 0 は未定義の値を意味します。int32_t を読み取ります。
type: docs
weight: 248
url: /ja/aspose.slides/textframeformat/get_columncount/
---
## TextFrameFormat::get_ColumnCount() メソッド

テキスト領域の列数を返します。この値は正の数でなければなりません。そうでない場合、値は 0 に設定されます。値 0 は未定義の値を意味します。**int32_t** を読み取ります。

```cpp
int32_t Aspose::Slides::TextFrameFormat::get_ColumnCount() override
```

## 備考

次のサンプルコードは、PowerPoint [Presentation](../../presentation/) 内のテキストフレームに列を追加する方法を示しています。
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

## 参照

* クラス [TextFrameFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)