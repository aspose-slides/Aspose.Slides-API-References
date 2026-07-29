---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides för C++ API-referens
description: Ställer in extern hyperlänk vid klick.
type: docs
weight: 1
url: /sv/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) metod

Ställ in extern hyperlänk vid klick.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |

## Anmärkningar

Följande exempelkod visar hur man lägger till en textruta med [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Hämtar den första bilden i presentationen
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Lägger till ett AutoShape-objekt med typen satt till rektangel
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Åtkommer ITextFrame-egenskapen som är associerad med AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Lägger till lite text i ramen
portion->set_Text(u"Aspose.Slides");

// Ställer in hyperlänken för textdelen
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Sparar PPTX-presentationen
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IHyperlink](../../ihyperlink/)
* Klass [String](../../../system/string/)
* Klass [HyperlinkManager](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)