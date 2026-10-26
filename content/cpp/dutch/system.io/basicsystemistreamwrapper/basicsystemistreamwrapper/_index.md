---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van de BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /nl/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor


Construeert een nieuw exemplaar van de [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | De pointer naar de stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Omvulmodus |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper&) constructor


Kopieerconstructor. Verwijderd.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) constructor


Move-constructor.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) te verplaatsen |

## Zie ook

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../stream/)
* Klasse [BasicSystemIStreamWrapper](../)
* Namespace [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)