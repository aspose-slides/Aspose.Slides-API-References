---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en ny instans av BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /sv/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() konstruktor

Skapar en ny instans av [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr<Stream>&, SystemIOStreamWrappingMode, const std::locale&) konstruktor

Skapar en ny instans av [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Smartpekare till strömmen |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Omslagsläge |
| locale | const std::locale\& | [Stream](../../stream/)'s locale |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf&) konstruktor

Kopieringskonstruktor. Borttagen.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf&&) konstruktor

Flyttkonstruktor.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) att flyttas |

## Se även

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [BasicSystemIOStreamBuf](../)
* Klass [Stream](../../stream/)
* Namnrymd [System::IO](../../)
* Library [Aspose.Slides](../../../)