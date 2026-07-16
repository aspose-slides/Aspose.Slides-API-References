---
title: SetExternalHyperlinkClick()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit le lien hypertexte externe au clic.
type: docs
weight: 1
url: /fr/aspose.slides/hyperlinkmanager/setexternalhyperlinkclick/
---
## HyperlinkManager::SetExternalHyperlinkClick(System::String) méthode

Définit le lien hypertexte externe au clic.

```cpp
System::SharedPtr<IHyperlink> Aspose::Slides::HyperlinkManager::SetExternalHyperlinkClick(System::String url) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| url | [System::String](../../../system/string/) | [Hyperlink](../../hyperlink/) URL. |
## Remarques

L'exemple de code suivant montre comment ajouter une zone de texte avec [Hyperlink](../../hyperlink/).
```cpp
auto pptxPresentation = System::MakeObject<Presentation>();
// Obtient la première diapositive de la présentation
auto slide = pptxPresentation->get_Slides()->idx_get(0);

// Ajoute un objet AutoShape avec le type défini comme Rectangle
auto pptxShape = slide->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 150.0f, 150.0f, 50.0f);
// Accède à la propriété ITextFrame associée à l'AutoShape
pptxShape->AddTextFrame(u"");
auto textFrame = pptxShape->get_TextFrame();
auto portion = textFrame->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);

// Ajoute du texte au cadre
portion->set_Text(u"Aspose.Slides");

// Définit le lien hypertexte pour le texte de la portion
auto hyperlinkManager = portion->get_PortionFormat()->get_HyperlinkManager();
hyperlinkManager->SetExternalHyperlinkClick(u"http://www.aspose.com");

// Saves the PPTX Presentation
pptxPresentation->Save(u"hLinkPPTX_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IHyperlink](../../ihyperlink/)
* Classe [String](../../../system/string/)
* Classe [HyperlinkManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)