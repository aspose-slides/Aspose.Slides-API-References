---
title: BasicSTDOStreamWrapper()
second_title: Referencia de la API de Aspose.Slides para C++
description: Construye una nueva instancia de BasicSTDOStreamWrapper.
type: docs
weight: 14
url: /es/system.io/basicstdostreamwrapper/basicstdostreamwrapper/
---
## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) constructor

Construye una nueva instancia de [BasicSTDOStreamWrapper](../).

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(std::basic_ostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| str | std::basic_ostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | La referencia al flujo |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | Modo de envoltorio |

## BasicSTDOStreamWrapper::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper\&) constructor

Constructor de copia. Eliminado.

```cpp
System::IO::BasicSTDOStreamWrapper<T, typename>::BasicSTDOStreamWrapper(const BasicSTDOStreamWrapper &)=delete
```

## Ver también

* Enumeración [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Clase [BasicSTDOStreamWrapper](../)
* Espacio de nombres [System::IO](../../)
* Biblioteca [Aspose.Slides](../../../)