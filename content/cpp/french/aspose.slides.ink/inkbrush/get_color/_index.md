---
title: get_Color()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la couleur du pinceau pour une ligne.
type: docs
weight: 1
url: /fr/aspose.slides.ink/inkbrush/get_color/
---
## InkBrush::get_Color() méthode

Obtient la couleur du pinceau pour une ligne.

```cpp
System::Drawing::Color Aspose::Slides::Ink::InkBrush::get_Color() override
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::Color brushColor = brush->get_Color();
brush->set_Color(System::Drawing::Color::get_Red());
```

## Voir aussi

* Classe [Color](../../../system.drawing/color/)
* Classe [InkBrush](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Bibliothèque [Aspose.Slides](../../../)