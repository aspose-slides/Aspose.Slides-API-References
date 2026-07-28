---
title: UnknownIsNull()
second_title: Aspose.Slides C++ API referencia
description: Ellenőrzi, hogy az ismeretlen típusú objektum nullptr-e. Nem skalár típusokhoz való túlterhelés.
type: docs
weight: 144
url: /hu/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) metódus


Ellenőrzi, hogy az ismeretlen típusú objektum nullptr-e. Túlterhelés nem skalár típusokhoz.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Sablon paraméterek

| Parameter | Leírás |
| --- | --- |
| T | [Object](../../object/) típus. |

### Argumentumok

| Parameter | Type | Leírás |
| --- | --- | --- |
| obj | T | [Object](../../object/) ellenőrzésre. |

### Visszatérési érték

True, ha az 'obj == nullptr' igaz, egyébként false.

## ObjectExt::UnknownIsNull(T) metódus


Ellenőrzi, hogy az ismeretlen típusú objektum nullptr-e. Túlterhelés skalár típusokhoz.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Sablon paraméterek

| Parameter | Leírás |
| --- | --- |
| T | [Object](../../object/) típus. |

### Argumentumok

| Parameter | Type | Leírás |
| --- | --- | --- |
| obj | T | [Object](../../object/) ellenőrzésre. |

### Visszatérési érték

Mindig false-t ad vissza.

## Lásd még

* Osztály [ObjectExt](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)