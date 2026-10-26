---
title: EventHandler
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Reprezentuje metodę, która reaguje na zdarzenie i je przetwarza. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy System::SmartPtr do zarządzania obiektami tego typu."
type: docs
weight: 3706
url: /pl/system/eventhandler/
---
## EventHandler typedef


Reprezentuje metodę, która reaguje na zdarzenie i przetwarza je. Ten typ powinien być przydzielany na stosie i przekazywany do funkcji przez wartość lub przez referencję. Nigdy nie używaj klasy [System::SmartPtr](../smartptr/) do zarządzania obiektami tego typu.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## Zobacz także

* Przestrzeń nazw [System](../)
* Biblioteka [Aspose.Slides](../../)