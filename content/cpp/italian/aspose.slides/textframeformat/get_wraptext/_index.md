---
title: get_WrapText()
second_title: Riferimento API di Aspose.Slides per C++
description: True se il testo è avvolto ai margini di TextFrame. Leggi NullableBool.
type: docs
weight: 118
url: /it/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() metodo

**True** se il testo è avvolto ai margini di [TextFrame](../../textframe/). Leggi [NullableBool](../../nullablebool/).

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## Osservazioni

Il seguente codice di esempio mostra come avvolgere il testo in [Presentation](../../presentation/).
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

## Vedi anche

* Enum [NullableBool](../../nullablebool/)
* Classe [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)