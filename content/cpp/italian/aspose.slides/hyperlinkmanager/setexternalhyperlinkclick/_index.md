---
title: SetExternalHyperlinkClick()
second_title: Riferimento API di Aspose.Slides per C++
description: Imposta un collegamento ipertestuale esterno al clic.
type: docs
weight: 1
url: /it/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) metodo

Imposta un collegamento ipertestuale esterno al clic.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Note

Il seguente codice di esempio mostra come aggiungere una Text Box con [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Ottiene la prima diapositiva nella presentazione
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Aggiunge un oggetto AutoShape con tipo impostato a Rettangolo
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Accede alla proprietà ITextFrame associata all'AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Aggiunge del testo al riquadro
portion->set_Text(u"Aspose.Slides");

// Imposta il collegamento ipertestuale per il testo della porzione
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Salva la presentazione PPTX
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHyperlink](../../ihyperlink/)
* Classe [String](../../../system/string/)
* Classe [HyperlinkManager](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)