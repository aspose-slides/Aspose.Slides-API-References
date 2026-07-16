---
title: GetLinesCount()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtenir le nombre de lignes dans un paragraphe.
type: docs
weight: 105
url: /fr/aspose.slides/iparagraph/getlinescount/
---
## IParagraph::GetLinesCount() méthode

Obtenir le nombre de lignes dans un paragraphe.

```cpp
virtual int32_t Aspose::Slides::IParagraph::GetLinesCount()=0
```

### Valeur de retour

Nombre de lignes dans un paragraphe
## Remarques

Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ISlide> sld = pres->get_Slide(0);
System::SharedPtr<IAutoShape> ashp = sld->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 150.0f, 75.0f, 150.0f, 50.0f);
System::SharedPtr<IParagraph> para = ashp->get_TextFrame()->get_Paragraph(0);
System::SharedPtr<IPortion> portion = para->get_Portion(0);
portion->set_Text(u"Aspose Paragraph GetLinesCount() Example");
System::Console::WriteLine(u"Lines Count = {0}", para->GetLinesCount());
```

## Voir aussi

* Classe [IParagraph](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)