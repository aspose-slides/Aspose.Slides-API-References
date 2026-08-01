---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides voor C++ API-referentie
description: Construeert een nieuw exemplaar van BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /nl/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() constructor

Construeert een nieuw exemplaar van [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) constructor

Construeert een nieuw exemplaar van [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Slimme pointer naar de stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Wrap-modus |
| locale | const std::locale\& | locale van [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) constructor

Copy-constructor. Verwijderd.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) constructor

Move-constructor.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) om te verplaatsen |

## Zie ook

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [BasicSystemIOStreamBuf](../)
* Klasse [Stream](../../stream/)
* Naamruimte [System::IO](../../)
* Bibliotheek [Aspose.Slides](../../../)