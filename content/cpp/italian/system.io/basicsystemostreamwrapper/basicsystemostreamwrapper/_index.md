---
title: BasicSystemOStreamWrapper()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza di BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /it/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) costruttore

Crea una nuova istanza di [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Il puntatore al flusso |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modalità di wrapping |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) costruttore

Costruttore di copia. Eliminato.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) costruttore

Costruttore di spostamento.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) da spostare |

## Vedi anche

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../stream/)
* Class [BasicSystemOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)