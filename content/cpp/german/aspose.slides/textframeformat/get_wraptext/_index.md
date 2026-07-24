---
title: get_WrapText()
second_title: Aspose.Slides für C++ API-Referenz
description: True, wenn der Text an den Rändern des TextFrames umbrochen wird. Lesen Sie NullableBool.
type: docs
weight: 118
url: /de/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() Methode

**True** wenn der Text an den Rändern von [TextFrame](../../textframe/) umbrochen wird. Lesen Sie [NullableBool](../../nullablebool/).

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## Hinweise

Der folgende Beispielcode zeigt, wie Text in [Presentation](../../presentation/) umbrochen wird.
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

## Siehe auch

* Aufzählung [NullableBool](../../nullablebool/)
* Klasse [TextFrameFormat](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)