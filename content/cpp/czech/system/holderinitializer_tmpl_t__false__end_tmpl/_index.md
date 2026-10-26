---
title: HolderInitializer< T, false >
second_title: Aspose.Slides pro C++ – referenční příručka
description: Specializace HolderInitializer pro případ, kdy je T typ hodnoty. Kontext použití umožňuje vrátit odkaz na dočasné objekty, protože je zaručeno, že instance bude volajícím zkopírována. Tato specializace je tedy používána jen jako výplň a nic nedělá.
type: docs
weight: 1652
url: /cs/system/holderinitializer_tmpl_t__false__end_tmpl/
---
## HolderInitializer< T, false > struct


[HolderInitializer](../holderinitializer/) specializace pro případ, kdy je T typ hodnoty. Kontext použití umožňuje vrátit odkaz na dočasné objekty, protože je zaručeno, že instance bude volajícím zkopírována. Tato specializace je tedy používána jen jako výplň a nedělá nic.

```cpp
template<typename T>class HolderInitializer< T, false >
```

## Metody

| Metoda | Popis |
| --- | --- |
| const T\& [Hold](./hold/)(const T\&) |  |
|  [HolderInitializer](./holderinitializer/)(T\&) |  |
| const T\& [HoldIfTemporary](./holdiftemporary/)(const T\&) |  |
## Viz také

* Jmenný prostor [System](../)
* Knihovna [Aspose.Slides](../../)