---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides C++ API hivatkozás
description: Létrehoz egy új példányt a BasicSystemIOStreamBuf osztályból.
type: docs
weight: 14
url: /hu/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() konstruktor

Létrehoz egy új példányt a(z) [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) konstruktor

Létrehoz egy új példányt a(z) [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Intelligens mutató a streamhez |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Becsomagolási mód |
| locale | const std::locale\& | [Stream](../../stream/) helyi beállítása |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) konstruktor

Másoló konstruktor. Törölve.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) konstruktor

Mozgató konstruktor.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) áthelyezésre |

## Lásd még

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [BasicSystemIOStreamBuf](../)
* Osztály [Stream](../../stream/)
* Névtér [System::IO](../../)
* Könyvtár [Aspose.Slides](../../../)