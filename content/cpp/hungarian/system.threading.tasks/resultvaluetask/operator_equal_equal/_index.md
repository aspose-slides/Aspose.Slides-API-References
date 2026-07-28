---
title: operator==()
second_title: Aspose.Slides C++ API referencia
description: Egyenlőség operátor a ResultValueTask számára.
type: docs
weight: 131
url: /hu/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const metódus

Egyenlőség operátor a [ResultValueTask](../) számára.

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | A másik [ResultValueTask](../), amelyet ehhez a példányhoz hasonlít. |

### Visszatérési érték

bool True, ha mindkét feladat ugyanazt az eredményértéket tartalmazza vagy ugyanarra az alapfeladatra hivatkozik; egyébként false.

## Megjegyzések

Ha bármelyik példány közvetlen eredményértéket tartalmaz, az eredményeket közvetlenül hasonlítja össze. Ellenkező esetben az alapfeladat mutatókat hasonlítja össze. 

## Lásd még

* Osztály [ResultValueTask](../)
* Névterület [System::Threading::Tasks](../../)
* Könyvtár [Aspose.Slides](../../../)