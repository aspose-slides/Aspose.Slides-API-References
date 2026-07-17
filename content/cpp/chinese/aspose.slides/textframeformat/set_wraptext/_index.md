---
title: set_WrapText()
second_title: Aspose.Slides for C++ API 参考
description: True 表示如果文本在 TextFrame 的边距处换行。写入 NullableBool。
type: docs
weight: 131
url: /zh/aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) 方法

**True** 如果文本在 [TextFrame](../../textframe/) 的边距处换行。写入 [NullableBool](../../nullablebool/)。

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## 备注

以下示例代码演示了如何在 [Presentation](../../presentation/) 中换行文本。 
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

## 另请参见

* 枚举 [NullableBool](../../nullablebool/)
* 类 [TextFrameFormat](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)