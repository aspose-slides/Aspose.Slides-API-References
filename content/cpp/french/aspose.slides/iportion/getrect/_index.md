---
title: GetRect()
second_title: Référence API Aspose.Slides pour C++
description: Obtenez les coordonnées du rectangle qui encadre la portion. Le rectangle comprend toutes les lignes de texte de la portion, y compris les lignes vides.
type: docs
weight: 79
url: /fr/aspose.slides/iportion/getrect/
---
## IPortion::GetRect() méthode

Obtenez les coordonnées du rectangle qui encadre la portion. Le rectangle inclut toutes les lignes de texte de la portion, y compris les lignes vides.

```cpp
virtual System::Drawing::RectangleF Aspose::Slides::IPortion::GetRect()=0
```

### Valeur de retour

Rectangle qui encadre la portion [System::Drawing::RectangleF](../../../system.drawing/rectanglef/)
## Remarques



Exemple:
```cpp
auto pres = System::MakeObject<Presentation>();

auto slide = pres->get_Slides()->idx_get(0);
auto shape = slide->get_Shapes()->AddAutoShape(Aspose::Slides::ShapeType::Rectangle, 50.0f, 50.0f, 200.0f, 50.0f);

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Clear();
auto portion0 = System::MakeObject<Portion>(u"Some text");
auto portion1 = System::MakeObject<Portion>(u"GetRect text");

shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion0);
shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->Add(portion1);

auto rect = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(1)->GetRect();
// ...
```

## Voir aussi

* Classe [RectangleF](../../../system.drawing/rectanglef/)
* Classe [IPortion](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)