---
title: BasicSystemOStreamWrapper
second_title: Referencia API de Aspose.Slides para C++
description: "Representa un contenedor similar a std::ostream que usa BasicSystemIOStreamBuf como búfer interno."
type: docs
weight: 79
url: /es/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper clase

Representa un contenedor similar a std::ostream que usa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como búfer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Usado en el constructor de movimiento y el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Construye una nueva instancia de [BasicSystemOStreamWrapper](./). |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Constructor de copia. Eliminado. |
| [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Constructor de movimiento. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Operador de asignación de copia. Eliminado. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Operador de asignación de movimiento. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Llamada a intercambiar *this y **right**, si no son iguales. |

## Definiciones de tipos

| Typedef | Descripción |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)