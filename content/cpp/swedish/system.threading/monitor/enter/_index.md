---
title: Enter()
second_title: Aspose.Slides för C++ API-referens
description: Erhåller ett exklusivt lås på ett specificerat objekt.
type: docs
weight: 1
url: /sv/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) metod

Erhåller ett exklusivt lås på ett specificerat objekt.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objektet som monitorlåset ska erhållas på. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) metod

Erhåller ett exklusivt lås på det specificerade objektet och sätter atomiskt ett värde som indikerar om låset togs.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [Monitor](../)
* Namnrymd [System::Threading](../../)
* Library [Aspose.Slides](../../../)