---
title: get_Size()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la taille du pinceau pour une ligne en points.
type: docs
weight: 27
url: /fr/aspose.slides.ink/inkbrush/get_size/
---
## InkBrush::get_Size() méthode


Obtient la taille du pinceau pour une ligne en points.

```cpp
System::Drawing::SizeF Aspose::Slides::Ink::InkBrush::get_Size() override
```

## Remarques


Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
System::Drawing::SizeF brushSize = brush->get_Size();
brush->set_Size(System::Drawing::SizeF(5.0f, 10.0f));
```

## Voir aussi

* Classe [SizeF](../../../system.drawing/sizef/)
* Classe [InkBrush](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Bibliothèque [Aspose.Slides](../../../)