---
title: Enter()
second_title: Aspose.Slides pro C++ – reference API
description: Získá exkluzivní zámek na zadaném objektu.
type: docs
weight: 1
url: /cs/system.threading/monitor/enter/
---
## Monitor::Enter(const SharedPtr\<Object\>\&) metoda


Získá exkluzivní zámek na zadaném objektu.

```cpp
static void System::Threading::Monitor::Enter(const SharedPtr<Object> &obj)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Objekt, na kterém se má získat monitorovací zámek. |

## Monitor::Enter(const System::SharedPtr\<Object\>\&, bool\&) metoda


Získá exkluzivní zámek na zadaném objektu a atomicky nastaví hodnotu, která udává, zda byl zámek získán.

```cpp
static void System::Threading::Monitor::Enter(const System::SharedPtr<Object> &obj, bool &lockTaken)
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Object](../../../system/object/)
* Třída [Monitor](../)
* Jmenný prostor [System::Threading](../../)
* Knihovna [Aspose.Slides](../../../)