---
title: EventHandler
second_title: Aspose.Slides voor C++ API-referentie
description: "Stelt een methode voor die reageert op en een gebeurtenis verwerkt. Dit type moet op de stack worden toegewezen en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit de System::SmartPtr klasse om objecten van dit type te beheren."
type: docs
weight: 3706
url: /nl/system/eventhandler/
---
## EventHandler typedef


Stelt een methode voor die reageert op en een gebeurtenis verwerkt. Dit type moet op de stack worden toegewezen en aan functies doorgegeven worden per waarde of per referentie. Gebruik nooit de [System::SmartPtr](../smartptr/) klasse om objecten van dit type te beheren.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)