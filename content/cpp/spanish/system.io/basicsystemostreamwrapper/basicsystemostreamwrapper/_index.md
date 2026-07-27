---
title: BasicSystemOStreamWrapper()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de BasicSystemOStreamWrapper.
type: docs
weight: 1
url: /es/system.io/basicsystemostreamwrapper/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor

Construye una nueva instancia de [BasicSystemOStreamWrapper](../).

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | El puntero al flujo |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modo de envoltura |

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper\&) constructor

Constructor de copia. Eliminado.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(const BasicSystemOStreamWrapper &)=delete
```

## BasicSystemOStreamWrapper::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper\&&) constructor

Constructor de movimiento.

```cpp
System::IO::BasicSystemOStreamWrapper<Elem, Traits>::BasicSystemOStreamWrapper(BasicSystemOStreamWrapper &&right) noexcept
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| right | [BasicSystemOStreamWrapper](../)\&& | [Object](../../../system/object/) a mover |

## Véase también

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../stream/)
* Clase [BasicSystemOStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)