---
title: BasicSystemIOStreamWrapper()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea una nuova istanza di BasicSystemIOStreamWrapper.
type: docs
weight: 1
url: /it/system.io/basicsystemiostreamwrapper/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) costruttore


Crea una nuova istanza di [BasicSystemIOStreamWrapper](../).

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | Il puntatore al flusso |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modalità di wrapping |

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper\&) costruttore


Costruttore di copia. Eliminato.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(const BasicSystemIOStreamWrapper &)=delete
```

## BasicSystemIOStreamWrapper::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper\&&) costruttore


Costruttore di spostamento.

```cpp
System::IO::BasicSystemIOStreamWrapper<Elem, Traits>::BasicSystemIOStreamWrapper(BasicSystemIOStreamWrapper &&right) noexcept
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| right | [BasicSystemIOStreamWrapper](../)\&& | [Object](../../../system/object/) da spostare |

## Vedi anche

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [Stream](../../stream/)
* classe [BasicSystemIOStreamWrapper](../)
* namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)