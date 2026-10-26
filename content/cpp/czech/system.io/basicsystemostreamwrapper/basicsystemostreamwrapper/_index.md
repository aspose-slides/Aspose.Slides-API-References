---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides pro C++ API Reference
description: Vytváří novou instanci BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /cs/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) konstruktor


Vytvoří novou instanci [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Ukazatel na stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Režim zabalení |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) konstruktor


Kopírovací konstruktor. Smazáno.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) konstruktor


Konstruktor přesunu.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) k přesunu |

## Viz také

* Výčet [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../stream/)
* Třída [BasicSystemOStreamWrapper](../)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)