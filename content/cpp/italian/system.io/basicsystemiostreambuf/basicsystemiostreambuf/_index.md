---
title: BasicSystemIOStreamBuf()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza di BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /it/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() costruttore


Crea una nuova istanza di [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) costruttore


Crea una nuova istanza di [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Puntatore intelligente al flusso |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modalità di wrapping |
| locale | const std::locale\& | locale di [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) costruttore


Costruttore di copia. Eliminato.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) costruttore


Costruttore di spostamento.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) da spostare |

## Vedi anche

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [BasicSystemIOStreamBuf](../)
* Classe [Stream](../../stream/)
* Spazio dei nomi [System::IO](../../)
* Libreria [Aspose.Slides](../../../)