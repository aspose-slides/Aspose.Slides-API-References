---
title: BasicSystemIOStreamWrapper
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un wrapper simile a std::iostream che utilizza BasicSystemIOStreamBuf come buffer interno."
type: docs
weight: 53
url: /it/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper classe

Rappresenta un wrapper simile a std::iostream che utilizza [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) come buffer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Utilizzato nel costruttore di spostamento e nell'operatore di assegnazione di spostamento per reimpostare i puntatori e chiamare [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Crea una nuova istanza di [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Costruttore di copia. Eliminato. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Costruttore di spostamento. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Operatore di assegnazione per copia. Eliminato. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Operatore di assegnazione per spostamento. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Chiamata per scambiare *this e **right**, se non sono uguali. |

## Typedef

| Typedef | Descrizione |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Vedi anche

* Namespace [System::IO](../)
* Libreria [Aspose.Slides](../../)