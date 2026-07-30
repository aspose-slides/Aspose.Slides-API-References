---
title: BasicSystemIOStreamBuf
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un buffer che avvolge flussi simili a System::IO::Stream e consente di usarli come buffer interno di flussi simili a std::iostream."
type: docs
weight: 40
url: /it/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf classe

Rappresenta un buffer che avvolge flussi simili a [System::IO::Stream](../stream/) e consente di usarli come buffer interno di flussi simili a std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Usato nel costruttore di spostamento e nell'operatore di assegnazione di spostamento per reimpostare i puntatori e chiamare [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Crea una nuova istanza di [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Crea una nuova istanza di [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Costruttore di copia. Eliminato. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Costruttore di spostamento. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Operatore di assegnazione di copia. Eliminato. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Operatore di assegnazione di spostamento. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Chiamata per scambiare *this e right, se non sono uguali. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Distruttore. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Vedi anche

* Namespace [System::IO](../)
* Libreria [Aspose.Slides](../../)