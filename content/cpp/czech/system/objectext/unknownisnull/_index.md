---
title: UnknownIsNull()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda je objekt neznámého typu nullptr. Přetížení pro neskalarové typy.
type: docs
weight: 144
url: /cs/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) metoda


Kontroluje, zda je objekt neznámého typu nullptr. Přetížení pro neskalarové typy.

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T | [Object](../../object/) ke kontrole. |

### Návratová hodnota

True pokud je 'obj == nullptr' pravda, false jinak.

## ObjectExt::UnknownIsNull(T) metoda


Kontroluje, zda je objekt neznámého typu nullptr. Přetížení pro skalární typy.

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | [Object](../../object/) typ. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | T | [Object](../../object/) ke kontrole. |

### Návratová hodnota

Vždy vrací false.

## Viz také

* Třída [ObjectExt](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)