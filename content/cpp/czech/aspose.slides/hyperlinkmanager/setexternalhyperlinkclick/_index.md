---
title: SetExternalHyperlinkClick()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Nastaví externí hypertextový odkaz při kliknutí.
type: docs
weight: 1
url: /cs/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) metoda


Nastaví externí hypertextový odkaz při kliknutí.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Poznámky



Následující ukázkový kód ukazuje, jak přidat textové pole s [Hyperlink](../../hyperlink/). 
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Získá první snímek v prezentaci
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Přidá objekt AutoShape s typem nastaveným na Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Přistupuje k vlastnosti ITextFrame spojené s AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Přidá nějaký text do rámce
portion->set_Text(u"Aspose.Slides");

// Nastaví Hyperlink pro text portion
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Uloží PPTX prezentaci
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [IHyperlink](../../ihyperlink/)
* třída [String](../../../system/string/)
* třída [HyperlinkManager](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)