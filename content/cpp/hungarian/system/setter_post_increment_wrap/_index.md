---
title: setter_post_increment_wrap()
second_title: Aspose.Slides C++ API Referencia
description: A fordító lefordítja a C# posztnövelő kifejezéseket, amelyek egy setterrel és getterrel definiált osztálytulajdonságot céloznak, ennek a függvénynek a meghívásává.
type: docs
weight: 2848
url: /hu/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) függvény

A fordító a C# posztnövelő kifejezéseket, amelyek egy setterrel és getterrel definiált osztálytulajdonságot céloznak, ebbe a függvénybe hívja meg.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tulajdonság típusa |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pGetter | T(*)() | Függvénymutató, amely a tulajdonság getter szabad függvényére mutat |
| pSetter | void(*)(T) | Függvénymutató, amely a tulajdonság setter szabad függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) függvény

A fordító a C# posztnövelő kifejezéseket, amelyek egy setterrel és getterrel definiált példánytulajdonságot céloznak, ebbe a függvénybe hívja meg (túlterhelés nem const getterhez).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tulajdonság típusa. |
| Host | - a módosítandó példány osztálya |
| HostGet | - a Host maga, vagy annak bázistípusja, ahol a tulajdonság getter definiálva van |
| HostSet | - a Host maga, vagy annak bázistípusja, ahol a tulajdonság setter definiálva van |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | Host *const | A példány, amelynek a getter és setter függvényeit hívni kell. |
| pGetter | T(HostGet::*)() | Függvénymutató, amely a tulajdonság getter függvényére mutat |
| pSetter | void(HostSet::*)(T) | Függvénymutató, amely a tulajdonság setter függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) függvény

A fordító a C# posztnövelő kifejezéseket, amelyek egy setterrel és getterrel definiált példánytulajdonságot céloznak, ebbe a függvénybe hívja meg (túlterhelés const getterhez).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tulajdonság típusa. |
| Host | - a módosítandó példány osztálya |
| HostConstGet | - a Host maga, vagy annak bázistípusja, ahol a tulajdonság getter definiálva van |
| HostSet | - a Host maga, vagy annak bázistípusja, ahol a tulajdonság setter definiálva van |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | Host *const | A példány, amelynek a getter és setter függvényeit hívni kell. |
| pGetter | T(HostConstGet::*)() const | Függvénymutató, amely a tulajdonság getter függvényére mutat |
| pSetter | void(HostSet::*)(T) | Függvénymutató, amely a tulajdonság setter függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)