---
title: setter_decrement_wrap()
second_title: Aspose.Slides C++ API referencia
description: A fordító lefordítja a C# elődecrement kifejezéseit, amelyek egy setterrel és getterrel definiált osztálytulajdonságra vonatkoznak, a függvény meghívására.
type: docs
weight: 2861
url: /hu/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) function

A fordító lefordítja a C# elődecrement kifejezéseit, amelyek egy setterrel és getterrel definiált osztálytulajdonságra vonatkoznak, a függvény meghívására.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | A tulajdonság típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Függvénymutató, amely a tulajdonság getter szabad függvényére mutat |
| pSetter | void(*)(T) | Függvénymutató, amely a tulajdonság setter szabad függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function

A fordító lefordítja a C# elődecrement kifejezéseit, amelyek egy setterrel és getterrel definiált példánytulajdonságra vonatkoznak, a függvény meghívására (nem const getterhez tartozó overload).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | A tulajdonság típusa. |
| Host | - a módosítandó példány osztálya |
| HostGet | - Host maga, vagy annak bázistípusa, ahol a tulajdonság getter definiálva van |
| HostSet | - Host maga, vagy annak bázistípusa, ahol a tulajdonság setter definiálva van |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Az a példány, amelynek a gettereket és settereket hívja. |
| pGetter | T(HostGet::*)() | Függvénymutató, amely a tulajdonság getter függvényére mutat |
| pSetter | void(HostSet::*)(T) | Függvénymutató, amely a tulajdonság setter függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function

A fordító lefordítja a C# elődecrement kifejezéseit, amelyek egy setterrel és getterrel definiált példánytulajdonságra vonatkoznak, a függvény meghívására (const getterhez tartozó overload).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Sablon paraméterek

| Parameter | Description |
| --- | --- |
| T | A tulajdonság típusa. |
| Host | - a módosítandó példány osztálya |
| HostConstGet | - Host maga, vagy annak bázistípusa, ahol a tulajdonság getter definiálva van |
| HostSet | - Host maga, vagy annak bázistípusa, ahol a tulajdonság setter definiálva van |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Az a példány, amelynek a gettereket és settereket hívja. |
| pGetter | T(HostConstGet::*)() const | Függvénymutató, amely a tulajdonság getter függvényére mutat |
| pSetter | void(HostSet::*)(T) | Függvénymutató, amely a tulajdonság setter függvényére mutat |

### Visszatérési érték

A tulajdonság értéke a növelés előtt

## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)