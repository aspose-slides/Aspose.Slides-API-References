---
title: EventHandler
second_title: Referência da API Aspose.Slides para C++
description: "Representa um método que reage e processa um evento. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe System::SmartPtr para gerenciar objetos desse tipo."
type: docs
weight: 3706
url: /pt/system/eventhandler/
---
## EventHandler typedef

Representa um método que reage e processa um evento. Este tipo deve ser alocado na pilha e passado para funções por valor ou por referência. Nunca use a classe [System::SmartPtr](../smartptr/) para gerenciar objetos desse tipo.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## Veja Também

* Espaço de nomes [System](../)
* Biblioteca [Aspose.Slides](../../)