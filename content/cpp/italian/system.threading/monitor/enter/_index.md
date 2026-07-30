---
title: Enter()
second_title: Riferimento API di Aspose.Slides per C++
description: Acquisisce un lock esclusivo su un oggetto specificato.
type: docs
weight: 1
url: /it/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) metodo

Acquisisce un lock esclusivo su un oggetto specificato.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | L'oggetto su cui acquisire il lock del monitor. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) metodo

Acquisisce un lock esclusivo sull'oggetto specificato e imposta in modo atomico un valore che indica se il lock è stato acquisito.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Object](../../../system/object/)
* Classe [Monitor](../)
* Namespace [System::Threading](../../)
* Library [Aspose.Slides](../../../)