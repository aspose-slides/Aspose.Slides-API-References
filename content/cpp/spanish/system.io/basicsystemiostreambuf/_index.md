---
title: BasicSystemIOStreamBuf
second_title: Referencia de API de Aspose.Slides para C++
description: "Representa un búfer que envuelve flujos similares a System::IO::Stream y permite que se utilicen como un búfer interno de flujos similares a std::iostream."
type: docs
weight: 40
url: /es/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf clase


Representa un búfer que envuelve flujos similares a [System::IO::Stream](../stream/) y permite que se utilicen como un búfer interno de flujos similares a std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Métodos

| Método | Descripción |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Usado en el constructor de movimiento y el operador de asignación de movimiento para restablecer punteros y llamar a [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Construye una nueva instancia de [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Construye una nueva instancia del [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Constructor de copia. Eliminado. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Constructor de movimiento. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Operador de asignación de copia. Eliminado. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Operador de asignación de movimiento. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Llamada para intercambiar *this y right, si no son iguales. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destructor. |

## Definiciones de tipos

| Typedef | Descripción |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Ver también

* Espacio de nombres [System::IO](../)
* Biblioteca [Aspose.Slides](../../)