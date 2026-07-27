---
title: BasicSystemIOStreamWrapper()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância do BasicSystemIOStreamWrapper.
type: docs
weight: 1
url: /pt/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) construtor


Constrói uma nova instância de [BasicSystemIOStreamWrapper](../).

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | O ponteiro para o stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modo de encapsulamento |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) construtor


Construtor de cópia. Excluído.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) construtor


Construtor de movimentação.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | [Object](../../../system/object/) a ser movido |

## Veja Também

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BasicSystemIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)