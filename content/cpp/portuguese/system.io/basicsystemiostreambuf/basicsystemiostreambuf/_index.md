---
title: BasicSystemIOStreamBuf()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância do BasicSystemIOStreamBuf.
type: docs
weight: 14
url: /pt/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() construtor


Constrói uma nova instância de [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) construtor


Constrói uma nova instância de [BasicSystemIOStreamBuf](../).

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | Ponteiro inteligente para o fluxo |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modo de encapsulamento |
| locale | const std::locale\& | local de [Stream](../../stream/) |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) construtor


Construtor de cópia. Excluído.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) construtor


Construtor de movimentação.

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) a ser movido |

## Veja também

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [BasicSystemIOStreamBuf](../)
* Classe [Stream](../../stream/)
* Namespace [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)