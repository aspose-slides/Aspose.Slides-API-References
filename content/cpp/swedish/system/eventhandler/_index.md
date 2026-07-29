---
title: EventHandler
second_title: Aspose.Slides för C++ API-referens
description: "Representerar en metod som reagerar på och bearbetar en händelse. Denna typ bör allokeras på stacken och skickas till funktioner per värde eller referens. Använd aldrig System::SmartPtr klass för att hantera objekt av denna typ."
type: docs
weight: 3706
url: /sv/system/eventhandler/
---
## EventHandler typedef

Representerar en metod som reagerar på och bearbetar en händelse. Denna typ bör allokeras på stacken och skickas till funktioner per värde eller referens. Använd aldrig [System::SmartPtr](../smartptr/) klass för att hantera objekt av denna typ.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)