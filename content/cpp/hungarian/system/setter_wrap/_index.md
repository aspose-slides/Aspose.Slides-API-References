---
title: setter_wrap()
second_title: Aspose.Slides C++ API referencia
description: Túlterhelés statikus setter függvényekhez típuskonverzióval.
type: docs
weight: 2822
url: /hu/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) függvény

Statikus setter függvények típuskonverzióval történő túlterhelése.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus. |
| T2 | A setter függvény által elvárt típus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pSetter | void(*)(T2) | Statikus setter függvény referenciája. |
| value | T | Beállítandó érték. |

### Visszatérési érték

beállított érték.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) függvény

Példány setter függvények típuskonverzióval történő túlterhelése.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Értéktípus. |
| T2 | A setter függvény által elvárt típus. |
| Host | Példány típusa. |
| HostSet | - A host maga, vagy annak az alaptípusa, ahol a tulajdonság setter-je definiálva van. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | Host *const | [Object](../object/) a setter függvény meghívásához. |
| pSetter | void(HostSet::*)(T2) | Setter függvény referenciája. |
| value | T | Beállítandó érték. |

### Visszatérési érték

beállított érték.

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)