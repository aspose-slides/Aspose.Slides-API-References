---
title: SetExternalHyperlinkClick()
second_title: Referencja API Aspose.Slides dla C++
description: Ustaw zewnętrzny hiperłącze po kliknięciu.
type: docs
weight: 1
url: /pl/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) method

Ustaw zewnętrzny hiperłącze po kliknięciu.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Uwagi



Poniższy przykładowy kod pokazuje, jak dodać pole tekstowe przy użyciu [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Pobiera pierwszy slajd w prezentacji
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Dodaje obiekt AutoShape z typem ustawionym na prostokąt
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Uzyskuje dostęp do właściwości ITextFrame powiązanej z AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Dodaje tekst do ramki
portion->set_Text(u"Aspose.Slides");

// Ustawia hiperłącze dla tekstu części
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Zapisuje prezentację PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Zobacz też

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHyperlink](../../ihyperlink/)
* Class [String](../../../system/string/)
* Class [HyperlinkManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)