---
title: EventHandler
second_title: Référence API Aspose.Slides pour C++
description: "Représente une méthode qui réagit à un événement et le traite. Ce type doit être alloué sur la pile et transmis aux fonctions par valeur ou par référence. N'utilisez jamais la classe System::SmartPtr pour gérer les objets de ce type."
type: docs
weight: 3667
url: /fr/system/eventhandler/
---
## EventHandler typedef


Représente une méthode qui réagit à un événement et le traite. Ce type doit être alloué sur la pile et transmis aux fonctions par valeur ou par référence. N'utilisez jamais la classe [System::SmartPtr](../smartptr/) pour gérer les objets de ce type.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)