---
title: Enter()
second_title: Aspose.Slides C++ API hivatkozása
description: Kizárólagos zárat szerez egy megadott objektumon.
type: docs
weight: 1
url: /hu/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) metódus

Kizárólagos zárat szerez egy megadott objektumon.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Az objektum, amelyen a monitorzárat fel kell venni. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) metódus

Kizárólagos zárat szerez a megadott objektumon, és atomikusan beállít egy értéket, amely jelzi, hogy a zárat megszerezték-e.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Object](../../../system/object/)
* Osztály [Monitor](../)
* Névtér [System::Threading](../../)
* Könyvtár [Aspose.Slides](../../../)