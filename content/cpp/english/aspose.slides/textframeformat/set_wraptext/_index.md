---
title: set_WrapText()
second_title: Aspose.Slides for C++ API Reference
description: True if text is wrapped at TextFrame's margins. Write NullableBool.
type: docs
weight: 131
url: /aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) method


**True** if text is wrapped at [TextFrame](../../textframe/)'s margins. Write [NullableBool](../../nullablebool/).

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## Remarks


The following sample code shows how to wrap text in [Presentation](../../presentation/). 
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

## See Also

* Enum [NullableBool](../../nullablebool/)
* Class [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)