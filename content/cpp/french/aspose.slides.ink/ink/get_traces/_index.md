---
title: get_Traces()
second_title: Référence de l'API Aspose.Slides pour C++
description: Récupère toutes les traces contenues dans l'élément IInk IInkTrace. Lecture seule.
type: docs
weight: 1
url: /fr/aspose.slides.ink/ink/get_traces/
---
## Ink::get_Traces() méthode


Récupère toutes les traces contenues dans l'élément [IInk](../../iink/) [IInkTrace](../../iinktrace/). Lecture seule.

```cpp
System::ArrayPtr<System::SharedPtr<IInkTrace>> Aspose::Slides::Ink::Ink::get_Traces() override
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
* Class [IInkTrace](../../iinktrace/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)