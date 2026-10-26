---
title: BasicSystemIOStreamBuf()
second_title: Dokumentacja API Aspose.Slides dla C++
description: Tworzy nową instancję BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /pl/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() konstruktor


Tworzy nową instancję [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) konstruktor


Tworzy nową instancję [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Inteligentny wskaźnik do strumienia |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Tryb opakowywania |
| locale | const std::locale\& | [Stream](../../stream/)'s locale |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) konstruktor


Konstruktor kopiujący. Usunięty.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) konstruktor


Konstruktor przenoszący.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) do przeniesienia |

## Zobacz także

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [BasicSystemIOStreamBuf](../)
* Klasa [Stream](../../stream/)
* Przestrzeń nazw [System::IO](../../)
* Library [Aspose.Slides](../../../)