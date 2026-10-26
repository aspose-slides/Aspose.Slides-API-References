---
title: EventHandler
second_title: Aspose.Slides per C++ Riferimento API
description: "Rappresenta un metodo che reagisce a e elabora un evento. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non usare la classe System::SmartPtr per gestire oggetti di questo tipo."
type: docs
weight: 3706
url: /it/system/eventhandler/
---
## typedef di EventHandler


Rappresenta un metodo che reagisce a e elabora un evento. Questo tipo dovrebbe essere allocato sullo stack e passato alle funzioni per valore o per riferimento. Non utilizzare la classe [System::SmartPtr](../smartptr/) per gestire oggetti di questo tipo.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Vedi anche

* Spazio dei nomi [System](../)
* Libreria [Aspose.Slides](../../)