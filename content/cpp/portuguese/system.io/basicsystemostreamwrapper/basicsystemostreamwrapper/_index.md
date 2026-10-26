---
title: BasicSystemOStreamWrapper()
second_title: Referência da API Aspose.Slides para C++
description: Constrói uma nova instância do BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /pt/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) construtor

Constrói uma nova instância de [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | O ponteiro para o fluxo |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modo de empacotamento |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) construtor

Construtor de cópia. Excluído.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) construtor

Construtor de movimentação.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) a ser movido |

## Ver também

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Stream](../../stream/)
* Classe [BasicSystemOStreamWrapper](../)
* Espaço de nomes [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)