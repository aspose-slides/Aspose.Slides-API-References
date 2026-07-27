---
title: BasicSystemIStreamWrapper
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un envoltorio similar a std::istream que utiliza BasicSystemIOStreamBuf como búfer interno."
type: docs
weight: 66
url: /es/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper clase

Representa un envoltorio similar a std::istream que usa [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) como búfer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Usado en el constructor de movimiento y el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Construye una nueva instancia de [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Constructor de copia. Eliminado. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Constructor de movimiento. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Operador de asignación de copia. Eliminado. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Operador de asignación de movimiento. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Llamada a swap *this y **right**, si no son iguales. |

## Typedefs

| Typedef | Descripción |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)