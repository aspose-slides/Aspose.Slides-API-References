---
title: set_WrapText()
second_title: Aspose.Slides para C++ Referência da API
description: True se o texto for ajustado nas margens do TextFrame. Escreva NullableBool.
type: docs
weight: 131
url: /pt/aspose.slides/textframeformat/set_wraptext/
---
## TextFrameFormat::set_WrapText(NullableBool) método


**True** se o texto for ajustado nas margens de [TextFrame](../../textframe/). Escreva [NullableBool](../../nullablebool/).

```cpp
void Aspose::Slides::TextFrameFormat::set_WrapText(NullableBool value) override
```

## Observações


O código de exemplo a seguir demonstra como ajustar o texto em [Presentation](../../presentation/). 
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

## Veja também

* Enum [NullableBool](../../nullablebool/)
* Classe [TextFrameFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)