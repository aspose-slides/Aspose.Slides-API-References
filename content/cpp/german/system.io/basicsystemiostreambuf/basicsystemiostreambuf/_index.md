---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides für C++ API-Referenz
description: Erzeugt eine neue Instanz von BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /de/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() Konstruktor

Erzeugt eine neue Instanz von [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) Konstruktor

Erzeugt eine neue Instanz von [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Smart-Pointer auf den Stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Wrap-Modus |
| locale | const std::locale\& | Locale von [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) Konstruktor

Kopierkonstruktor. Gelöscht.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) Konstruktor

Move-Konstruktor.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) zum Verschieben |

## Siehe auch

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BasicSystemIOStreamBuf](../)
* Class [Stream](../../stream/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)