---
title: EventHandler
second_title: Справочник API Aspose.Slides для C++
description: "Представляет метод, который реагирует на событие и обрабатывает его. Этот тип должен быть размещён в стеке и передаваться функциям по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 3667
url: /ru/system/eventhandler/
---
## EventHandler typedef


Представляет метод, который реагирует на событие и обрабатывает его. Этот тип должен быть размещён в стеке и передаваться функциям по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```


## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)