---
title: Enter()
second_title: Referencia de API de Aspose.Slides para C++
description: Adquiere un bloqueo exclusivo en un objeto especificado.
type: docs
weight: 1
url: /es/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) método

Adquiere un bloqueo exclusivo en un objeto especificado.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | El objeto sobre el que se adquiere el bloqueo del monitor. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) método

Adquiere un bloqueo exclusivo en el objeto especificado y establece de forma atómica un valor que indica si se tomó el bloqueo.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Object](../../../system/object/)
* Clase [Monitor](../)
* Espacio de nombres [System::Threading](../../)
* Library [Aspose.Slides](../../../)