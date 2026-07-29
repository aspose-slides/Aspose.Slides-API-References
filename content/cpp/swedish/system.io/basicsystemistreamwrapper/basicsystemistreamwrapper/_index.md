---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /sv/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) konstruktor


Skapar en ny instans av [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Pekaren till strömmen |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Inpakningsläge |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) konstruktor


Kopiekonstruktor. Borttagen.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) konstruktor


Flyttkonstruktor.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) att flyttas |

## Se också

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../stream/)
* Klass [BasicSystemIStreamWrapper](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)