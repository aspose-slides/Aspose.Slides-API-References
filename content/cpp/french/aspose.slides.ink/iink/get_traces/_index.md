---
title: get_Traces()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient toutes les traces contenues dans l'élément IInk IInkTrace. Lecture seule.
type: docs
weight: 1
url: /fr/aspose.slides.ink/iink/get_traces/
---
## IInk::get_Traces() méthode

Obtient toutes les traces contenues dans l'élément [IInk](../) [IInkTrace](../../iinktrace/). Lecture seule.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::IInk::get_Traces()=0
```

## Remarques

Exemple:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<IInk> ink = System::ExplicitCast<Aspose::Slides::Ink::IInk>(pres->get_Slide(0)->get_Shape(0));
System::ArrayPtr<System::SharedPtr<IInkTrace>> traces = ink->get_Traces();
```

## Voir aussi

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IInkTrace](../../iinktrace/)
* Classe [IInk](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Bibliothèque [Aspose.Slides](../../../)