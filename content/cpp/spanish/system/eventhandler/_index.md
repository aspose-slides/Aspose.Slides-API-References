---
title: EventHandler
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un método que reacciona y procesa un evento. Este tipo debe asignarse en la pila y pasarse a las funciones por valor o por referencia. Nunca use la clase System::SmartPtr para gestionar objetos de este tipo."
type: docs
weight: 3706
url: /es/system/eventhandler/
---
## EventHandler typedef

Representa un método que reacciona y procesa un evento. Este tipo debe ser asignado en la pila y pasado a funciones por valor o por referencia. Nunca utilice la clase [System::SmartPtr](../smartptr/) para gestionar objetos de este tipo.

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## Ver también

* Espacio de nombres [System](../)
* Biblioteca [Aspose.Slides](../../)