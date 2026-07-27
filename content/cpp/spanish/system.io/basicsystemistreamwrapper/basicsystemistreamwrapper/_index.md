---
title: BasicSystemIStreamWrapper()
second_title: Referencia de API de Aspose.Slides para C++
description: Construye una nueva instancia de BasicSystemIStreamWrapper.
type: docs
weight: 1
url: /es/system.io/basicsystemistreamwrapper/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(SharedPtr\<Stream\>, SystemIOStreamWrappingMode) constructor


Construye una nueva instancia de [BasicSystemIStreamWrapper](../).

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(SharedPtr<Stream> str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\> | El puntero al flujo |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | Modo de envoltura |

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper\&) constructor


Constructor de copia. Eliminado.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(const BasicSystemIStreamWrapper &)=delete
```

## BasicSystemIStreamWrapper::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper\&&) constructor


Constructor de movimiento.

```cpp
System::IO::BasicSystemIStreamWrapper<Elem, Traits>::BasicSystemIStreamWrapper(BasicSystemIStreamWrapper &&right) noexcept
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| right | [BasicSystemIStreamWrapper](../)\&& | [Object](../../../system/object/) para mover |

## Ver también

* Enumeración [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [Stream](../../stream/)
* Clase [BasicSystemIStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)