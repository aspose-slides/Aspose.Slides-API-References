---
title: AddMathShape()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée une nouvelle forme auto rectangulaire pour contenir du contenu mathématique et l'ajoute à la fin de la collection de formes.
type: docs
weight: 365
url: /fr/aspose.slides/shapecollection/addmathshape/
---
## ShapeCollection::AddMathShape(float, float, float, float) méthode

Crée une nouvelle forme auto rectangulaire pour contenir du contenu mathématique et l'ajoute à la fin de la collection de formes.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddMathShape(float x, float y, float width, float height) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| x | **float** | La coordonnée x du cadre de la forme, en points. |
| y | **float** | La coordonnée y du cadre de la forme, en points. |
| width | **float** | La largeur du cadre de la forme, en points. |
| height | **float** | La hauteur du cadre de la forme, en points. |

### Valeur de retour

Le [IAutoShape](../../iautoshape/) nouvellement créé.

## Remarques

L'exemple suivant montre comment ajouter une équation mathématique dans PowerPoint [Presentation](../../presentation/).
```cpp
auto pres = System::MakeObject<Presentation>();

auto mathShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddMathShape(0.0f, 0.0f, 720.0f, 150.0f);
auto mathPortion = mathShape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0);
auto mathParagraph = (System::AsCast<MathPortion>(mathPortion))->get_MathParagraph();
auto fraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
mathParagraph->Add(System::MakeObject<MathBlock>(fraction));
auto a2 = System::MakeObject<MathematicalText>(u"a")->SetSuperscript(u"2");
auto b2 = System::MakeObject<MathematicalText>(u"b")->SetSuperscript(u"2");
auto c2 = System::MakeObject<MathematicalText>(u"c")->SetSuperscript(u"2");
auto mathBlock = c2->Join(u"=")->Join(a2)->Join(u"+")->Join(b2); // c^2 = a^2 + b^2
mathParagraph->Add(mathBlock);
pres->Save(u"math.pptx", SaveFormat::Pptx);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [ShapeCollection](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)