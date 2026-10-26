---
title: get_WrapText()
second_title: Aspose.Slides C++ API 參考
description: True 表示文字在 TextFrame 的邊緣自動換行。請閱讀 NullableBool。
type: docs
weight: 118
url: /zh-hant/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() 方法


**True** 如果文字在 [TextFrame](../../textframe/) 的邊緣。閱讀 [NullableBool](../../nullablebool/).

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## 備註


以下範例程式碼示範如何在 [Presentation](../../presentation/) 中自動換行文字。
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

## 參見

* 列舉 [NullableBool](../../nullablebool/)
* 類別 [TextFrameFormat](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)