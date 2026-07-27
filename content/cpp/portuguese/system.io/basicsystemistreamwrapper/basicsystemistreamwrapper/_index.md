---
title: BasicSystemIStreamWrapper()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância do BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /pt/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) construtor


Constrói uma nova instância de [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | O ponteiro para o stream |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modo de empacotamento |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) construtor


Construtor de cópia. Excluído.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) construtor


Construtor de movimento.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) a ser movido |

## Veja Também

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BasicSystemIStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)