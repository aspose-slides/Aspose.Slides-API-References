---
title: setter_increment_wrap()
second_title: Aspose.Slides C++ API referencia
description: A fordító a C#-ban lévő növelő kifejezéseket, amelyek egy setterrel és getterrel definiált osztálytulajdonságot céloznak, a függvény meghívásává alakítja.
type: docs
weight: 2835
url: /hu/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) függvény


A fordító a C#'s increment kifejezéseket, amelyek egy setterrel és getterrel definiált osztálytulajdonságot céloznak, a függvény meghívásává alakítja.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tulajdonság típusa |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pGetter | T(*)() | Függvénymutató, amely a tulajdonság getter szabad függvényére mutat |
| pSetter | void(*)(T) | Függvénymutató, amely a tulajdonság setter szabad függvényére mutat |

### Visszatérési érték

A tulajdonság növelt értéke

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) függvény


A fordító a C#'s increment kifejezéseket, amelyek egy setterrel és getterrel definiált osztálytulajdonságot céloznak, a függvény meghívásává alakítja.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Sablonparaméterek

| Parameter | Description |
| --- | --- |
| T | A tulajdonság típusa |
| Host | - a módosítandó példány osztálya |
| HostGet | - a Host maga, vagy annak alaptípusa, ahol a tulajdonság getter meghatározásra került |
| HostSet | - a Host maga, vagy annak alaptípusa, ahol a tulajdonság setter meghatározásra került |

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| host | Host *const | Egy mutató egy objektumra, amelynek a tulajdonságát növelni kell |
| pGetter | T(HostGet::*)() | Függvénymutató, amely a tulajdonság getter metódusára mutat |
| pSetter | void(HostSet::*)(T) | Függvénymutató, amely a tulajdonság setter metódusára mutat |

### Visszatérési érték

A tulajdonság növelt értéke

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)