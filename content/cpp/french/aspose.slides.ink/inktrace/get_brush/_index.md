---
title: get_Brush()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient le Brush pour l'IInkLine IInkBrush en lecture seule.
type: docs
weight: 1
url: /fr/aspose.slides.ink/inktrace/get_brush/
---
## InkTrace::get_Brush() méthode

Obtient le Brush pour l'IInkLine [IInkBrush](../../iinkbrush/) en lecture seule.

```cpp
System::SharedPtr<IInkBrush> Aspose::Slides::Ink::InkTrace::get_Brush() override
```

## Remarques


Exemple :
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
System::SharedPtr<IInkBrush> brush = traces[0]->get_Brush();
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkBrush](../../iinkbrush/)
* Classe [InkTrace](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Bibliothèque [Aspose.Slides](../../../)