---
title: EventHandler
second_title: Aspose.Slides pro C++ - reference API
description: "Reprezentuje metodu, která reaguje na událost a zpracovává ji. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu System::SmartPtr pro správu objektů tohoto typu."
type: docs
weight: 3706
url: /cs/system/eventhandler/
---
## EventHandler typedef

Reprezentuje metodu, která reaguje na událost a zpracovává ji. Tento typ by měl být alokován na zásobníku a předáván funkcím hodnotou nebo referencí. Nikdy nepoužívejte třídu [System::SmartPtr](../smartptr/) k správě objektů tohoto typu.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)