---
title: get_Points()
second_title: Référence API Aspose.Slides pour C++
description: "Obtient les points pour le IInkLine System::Drawing::PointF en lecture seule."
type: docs
weight: 14
url: /fr/aspose.slides.ink/iinktrace/get_points/
---
## IInkTrace::get_Points() méthode


Obtient les points pour le IInkLine [System::Drawing::PointF](../../../system.drawing/pointf/) Lecture seule.

```cpp
virtual System::ArrayPtr<System::Drawing::PointF> Aspose::Slides::Ink::IInkTrace::get_Points()=0
```

## Remarques


Exemple: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::ArrayPtr<System::Drawing::PointF> points = traces[0]->get_Points();
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [PointF](../../../system.drawing/pointf/)
* Classe [IInkTrace](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Bibliothèque [Aspose.Slides](../../../)