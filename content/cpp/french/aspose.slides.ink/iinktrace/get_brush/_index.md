---
title: get_Brush()
second_title: Référence API Aspose.Slides pour C++
description: Obtient le Brush pour l'IInkLine IInkBrush Lecture seule.
type: docs
weight: 1
url: /fr/aspose.slides.ink/iinktrace/get_brush/
---
## IInkTrace::get_Brush() méthode


Obtient le Brush pour l'IInkLine [IInkBrush](../../iinkbrush/) Lecture seule.

```cpp
virtual System::SharedPtr<IInkBrush> Aspose::Slides::Ink::IInkTrace::get_Brush()=0
```

## Remarques


Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkBrush](../../iinkbrush/)
* Classe [IInkTrace](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Bibliothèque [Aspose.Slides](../../../)