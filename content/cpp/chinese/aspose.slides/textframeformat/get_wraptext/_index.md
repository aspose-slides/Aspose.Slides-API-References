---
title: get_WrapText()
second_title: Aspose.Slides C++ API 参考
description: 如果文本在 TextFrame 的边距处换行，则为 True。阅读 NullableBool.
type: docs
weight: 118
url: /zh/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() 方法

**True** 如果文本在 [TextFrame](../../textframe/) 的边距处换行。阅读 [NullableBool](../../nullablebool/).

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## 备注

以下示例代码展示了如何在 [Presentation](../../presentation/) 中换行文本。 
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

## 另见

* 枚举 [NullableBool](../../nullablebool/)
* 类 [TextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)