---
title: BasicSystemIOStreamWrapper
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un envoltorio similar a std::iostream que usa BasicSystemIOStreamBuf como búfer interno."
type: docs
weight: 53
url: /es/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper clase

Representa un envoltorio similar a std::iostream que usa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como búfer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Usado en el constructor de movimiento y en el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Construye una nueva instancia del [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Constructor de copia. Eliminado. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Constructor de movimiento. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Operador de asignación de copia. Eliminado. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Operador de asignación de movimiento. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Llamada para intercambiar *this y **right**, si no son iguales. |

## Definiciones de tipo

| Typedef | Descripción |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Véase también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)