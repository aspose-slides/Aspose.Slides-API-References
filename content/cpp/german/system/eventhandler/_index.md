---
title: EventHandler
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt eine Methode dar, die auf ein Ereignis reagiert und es verarbeitet. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die System::SmartPtr Klasse, um Objekte dieses Typs zu verwalten."
type: docs
weight: 3706
url: /de/system/eventhandler/
---
## EventHandler typedef

Stellt eine Methode dar, die auf ein Ereignis reagiert und es verarbeitet. Dieser Typ sollte auf dem Stack alloziert und an Funktionen per Wert oder Referenz übergeben werden. Verwenden Sie niemals die [System::SmartPtr](../smartptr/) Klasse, um Objekte dieses Typs zu verwalten.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)