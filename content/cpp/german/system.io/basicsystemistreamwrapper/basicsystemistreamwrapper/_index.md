---
title: BasicSystemIStreamWrapper()
second_title: Aspose.Slides für C++ API Referenz
description: Konstruiert eine neue Instanz des BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /de/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) Konstruktor


Konstruiert eine neue Instanz von [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Der Zeiger auf den Stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Einwicklungsmodus |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) Konstruktor


Kopierkonstruktor. Gelöscht.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) Konstruktor


Move-Konstruktor.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) zu verschieben |

## Siehe auch

* Aufzählung [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klasse [Stream](../../stream/)
* Klasse [BasicSystemIStreamWrapper](../)
* Namensraum [System::IO](../../)
* Bibliothek [Aspose.Slides](../../../)