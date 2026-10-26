---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides C++ API referenciája
description: Létrehoz egy új példányt a BasicSystemOStreamWrapper-ból.
type: docs
weight: 1
url: /hu/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) konstruktor

Létrehoz egy új példányt a [BasicSystemOStreamWrapper](../)-ból.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | A mutató a streamhez |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Becsomagolási mód |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) konstruktor

Másoló konstruktor. Törölve.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) konstruktor

Mozgató konstruktor.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) a mozgatáshoz |

## Lásd még

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Stream](../../stream/)
* Osztály [BasicSystemOStreamWrapper](../)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)