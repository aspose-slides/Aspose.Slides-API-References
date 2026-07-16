---
title: get_WrapText()
second_title: Référence de l'API Aspose.Slides pour C++
description: Vrai si le texte est renvoyé aux marges de TextFrame. Lire NullableBool.
type: docs
weight: 118
url: /fr/aspose.slides/textframeformat/get_wraptext/
---
## TextFrameFormat::get_WrapText() méthode

**Vrai** si le texte est renvoyé aux marges de [TextFrame](../../textframe/). Lire [NullableBool](../../nullablebool/).

```cpp
NullableBool Aspose::Slides::TextFrameFormat::get_WrapText() override
```

## Remarques

Le code d'exemple suivant montre comment renvoyer le texte dans [Presentation](../../presentation/).
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

## Voir aussi

* Enum [NullableBool](../../nullablebool/)
* Classe [TextFrameFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)