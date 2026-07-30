---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides pro C++ API Referenci
description: Vytvoří novou instanci BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /cs/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() konstruktor


Vytvoří novou instanci [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) konstruktor


Vytvoří novou instanci [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Chytrý ukazatel na stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Režim zabalení |
| locale | const std::locale\& | locale [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) konstruktor


Kopírovací konstruktor. Smazáno.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) konstruktor


Přesunovací konstruktor.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) k přesunu |

## Viz také

* Výčet [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [BasicSystemIOStreamBuf](../)
* Třída [Stream](../../stream/)
* Jmenný prostor [System::IO](../../)
* Knihovna [Aspose.Slides](../../../)