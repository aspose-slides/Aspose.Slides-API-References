---
title: BasicSystemOStreamWrapper()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /nl/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor

Construeert een nieuw exemplaar van de [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | De pointer naar de stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Wrapper-modus |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) constructor

Copy-constructor. Verwijderd.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) constructor

Move-constructor.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) om te verplaatsen |

## Zie ook

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../stream/)
* Klasse [BasicSystemOStreamWrapper](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)