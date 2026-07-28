---
title: setter_post_decrement_wrap()
second_title: Aspose.Slides a C++ API-referencia
description: A fordító lefordítja a C# posztdekrement kifejezéseit, amelyek egy setterrel és getterrel definiált osztálytulajdonságra irányulnak, ennek a függvénynek a meghívására.
type: docs
weight: 2874
url: /hu/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) függvény


A fordító lefordítja a C# posztdekrement kifejezéseit, amelyek egy setterrel és getterrel definiált osztálytulajdonságra irányulnak, ennek a függvénynek a meghívására.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
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

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) függvény


A fordító lefordítja a C# posztdekrement kifejezéseit, amelyek egy setterrel és getterrel definiált példánytulajdonságra irányulnak, ennek a függvénynek a meghívására (túlterhelés a nem-const getterhez).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tulajdonság típusa. |
| Host | – a módosítandó példány osztálya |
| HostGet | – a Host vagy annak bázistípusú osztálya, ahol a tulajdonság getter definiált |
| HostSet | – a Host vagy annak bázistípusú osztálya, ahol a tulajdonság setter definiált |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | Host *const | A példány, amelynek a getterei és setterei hívódnak. |
| pGetter | T(HostGet::*)() | Függvénymutató, amely a tulajdonság getter függvényére mutat |
| pSetter | void(HostSet::*)(T) | Függvénymutató, amely a tulajdonság setter függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) függvény


A fordító lefordítja a C# posztdekrement kifejezéseit, amelyek egy setterrel és getterrel definiált példánytulajdonságra irányulnak, ennek a függvénynek a meghívására (túlterhelés a const getterhez).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A tulajdonság típusa. |
| Host | – a módosítandó példány osztálya |
| HostConstGet | – a Host vagy annak bázistípusú osztálya, ahol a tulajdonság getter definiált |
| HostSet | – a Host vagy annak bázistípusú osztálya, ahol a tulajdonság setter definiált |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | Host *const | A példány, amelynek a getterei és setterei hívódnak. |
| pGetter | T(HostConstGet::*)() const | Függvénymutató, amely a tulajdonság getter függvényére mutat |
| pSetter | void(HostSet::*)(T) | Függvénymutató, amely a tulajdonság setter függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)