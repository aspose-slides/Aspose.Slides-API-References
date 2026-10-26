---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides für C++ API-Referenz
description: Setzt externen Hyperlink beim Klicken.
type: docs
weight: 1
url: /de/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) method


Setzt externen Hyperlink beim Klicken.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Anmerkungen



Der folgende Beispielcode zeigt, wie man ein Textfeld mit [Hyperlink](../../hyperlink/) hinzufügt. 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Ermittelt die erste Folie in der Präsentation
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Fügt ein AutoShape-Objekt mit dem Typ Rechteck hinzu
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Greift auf die ITextFrame-Eigenschaft zu, die dem AutoShape zugeordnet ist
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Fügt dem Rahmen etwas Text hinzu
portion->set_Text(u"Aspose.Slides");

// Setzt den Hyperlink für den Portion-Text
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Speichert die PPTX-Präsentation
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IHyperlink](../../ihyperlink/)
* Klasse [String](../../../system/string/)
* Klasse [HyperlinkManager](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)