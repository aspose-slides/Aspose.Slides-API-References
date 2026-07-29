---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /sv/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) konstruktör


Skapar en ny instans av [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | The pointer to the stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Wrapping mode |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) konstruktör


Kopieringskonstruktor. Borttagen.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) konstruktör


Flyttkonstruktor.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) to be move |

## Se även

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Stream](../../stream/)
* Klass [BasicSystemOStreamWrapper](../)
* Namnrymd [System::IO](../../)
* Bibliotek [Aspose.Slides](../../../)