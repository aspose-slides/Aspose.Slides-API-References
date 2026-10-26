---
title: get_WrapText()
second_title: Aspose.Slides for C++ API リファレンス
description: テキストが TextFrame の余白で折り返されている場合は True です。NullableBool を参照してください。
type: docs
weight: 118
url: /ja/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() メソッド

[TextFrame](../../textframe/) の余白でテキストが折り返される場合は **True** です。[NullableBool](../../nullablebool/) を参照してください。

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## 備考

以下のサンプルコードは、[Presentation](../../presentation/) でテキストを折り返す方法を示しています。
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto autoShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 30.0f, 30.0f, 350.0f, 100.0f);
auto portion = System::MakeObject<Portion>(u"lorem ipsum...");
portion->get_PortionFormat()->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Black());
portion->get_PortionFormat()->get_FillFormat()->set_FillType(FillType::Solid);
autoShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion);
auto textFrameFormat = autoShape->get_TextFrame()->get_TextFrameFormat();
textFrameFormat->set_WrapText(NullableBool::True);
pres->Save(u"Output-presentation.pptx", SaveFormat::Pptx);
```

## 参照

* 列挙型 [NullableBool](../../nullablebool/)
* クラス [TextFrameFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)