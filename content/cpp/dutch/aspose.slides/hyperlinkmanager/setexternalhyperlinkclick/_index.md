---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides voor C++ API-referentie
description: Stel externe hyperlink in bij klikken.
type: docs
weight: 1
url: /nl/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) methode


Stel een externe hyperlink in bij klikken.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Opmerkingen



De volgende voorbeeldcode toont hoe u een Text Box kunt toevoegen met [Hyperlink](../../hyperlink/). 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Haalt de eerste dia op in de presentatie
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Voegt een AutoShape-object toe met het type ingesteld op Rechthoek
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Toegang tot de ITextFrame-eigenschap die aan de AutoShape is gekoppeld
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Voegt wat tekst toe aan het kader
portion->set_Text(u"Aspose.Slides");

// Stelt de hyperlink in voor de portion-tekst
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Slaat de PPTX-presentatie op
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHyperlink](../../ihyperlink/)
* Klasse [String](../../../system/string/)
* Klasse [HyperlinkManager](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)