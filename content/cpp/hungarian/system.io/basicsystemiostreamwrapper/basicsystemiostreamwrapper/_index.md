---
title: BasicSystemIOStreamWrapper()
second_title: Aspose.Slides C++ API referencia
description: Létrehoz egy új példányt a BasicSystemIOStreamWrapper osztályból.
type: docs
weight: 1
url: /hu/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor

Létrehoz egy új példányt a [BasicSystemIOStreamWrapper](../).

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | A stream mutatója |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Becsomagolási mód |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) constructor

Másoló konstruktor. Törölt.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) constructor

Mozgató konstruktor.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | [Object](../../../system/object/) mozgatandó |

## Lásd még

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BasicSystemIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)