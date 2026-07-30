---
title: BasicSystemIOStreamWrapper()
second_title: Aspose.Slides pro C++ - reference API
description: Vytvoří novou instanci BasicSystemIOStreamWrapper.
type: docs
weight: 1
url: /cs/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) konstruktor

Vytvoří novou instanci [BasicSystemIOStreamWrapper](../).

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Ukazatel na proud |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Mód zapouzdření |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) konstruktor

Kopírovací konstruktor. Odstraněno.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) konstruktor

Přesunovací konstruktor.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | [Object](../../../system/object/) k přesunu |

## Viz také

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BasicSystemIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)