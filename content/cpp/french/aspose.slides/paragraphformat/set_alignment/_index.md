---
title: set_Alignment()
second_title: Référence de l'API Aspose.Slides pour C++
description: Définit l'alignement du texte dans un paragraphe sans héritage. Écrivez TextAlignment.
type: docs
weight: 14
url: /fr/aspose.slides/paragraphformat/set_alignment/
---
## ParagraphFormat::set_Alignment(TextAlignment) méthode


Définit l'alignement du texte dans un paragraphe sans héritage. Écrivez [TextAlignment](../../textalignment/).

```cpp
void Aspose::Slides::ParagraphFormat::set_Alignment(TextAlignment value) override
```

## Remarques


Le code d'exemple suivant montre comment aligner les paragraphes de texte dans PowerPoint [Presentation](../../presentation/). 
```cpp
auto pres = System::MakeObject<Presentation>(u"ParagraphsAlignment.pptx");

// Accessing first slide
auto slide = pres->get_Slides()->idx_get(0);
// Accessing the first and second placeholder in the slide and typecasting it as AutoShape
System::SharedPtr<ITextFrame> tf1 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(0)))->get_TextFrame();
System::SharedPtr<ITextFrame> tf2 = (System::ExplicitCast<IAutoShape>(slide->get_Shapes()->idx_get(1)))->get_TextFrame();
// Change the text in both placeholders
tf1->set_Text(u"Center Align by Aspose");
tf2->set_Text(u"Center Align by Aspose");
// Getting the first paragraph of the placeholders
System::SharedPtr<IParagraph> para1 = tf1->get_Paragraphs()->idx_get(0);
System::SharedPtr<IParagraph> para2 = tf2->get_Paragraphs()->idx_get(0);
// Aligning the text paragraph to center
para1->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
para2->get_ParagraphFormat()->set_Alignment(TextAlignment::Center);
//Writing the presentation as a PPTX file
pres->Save(u"Centeralign_out.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Énum [TextAlignment](../../textalignment/)
* Classe [ParagraphFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)