---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides pro C++ API Reference
description: Vytvoří novou instanci BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /cs/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) konstruktor

Vytvoří novou instanci [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Ukazatel na stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Režim zapouzdření |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) konstruktor

Kopírovací konstruktor. Smazáno.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) konstruktor

Přesunovací konstruktor.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) k přesunu |

## Viz také

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Stream](../../stream/)
* Třída [BasicSystemIStreamWrapper](../)
* Obor názvů [System::IO](../../)
* Library [Aspose.Slides](../../../)