---
title: BasicSystemIStreamWrapper
second_title: Riferimento API di Aspose.Slides per C++
description: "Rappresenta un wrapper simile a std::istream che utilizza BasicSystemIOStreamBuf come buffer interno."
type: docs
weight: 66
url: /it/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper classe

Rappresenta un wrapper simile a std::istream che utilizza [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) come buffer interno.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Metodi

| Metodo | Descrizione |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Utilizzato nel costruttore di spostamento e nell'operatore di assegnazione di spostamento per reimpostare i puntatori e chiamare [swap()](./swap/). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Costruisce una nuova istanza di [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Costruttore di copia. Eliminato. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Costruttore di spostamento. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Operatore di assegnazione di copia. Eliminato. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Operatore di assegnazione di spostamento. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Chiamata a swap di *this e **right**, se non sono uguali. |

## Typedefs

| Typedef | Descrizione |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Vedi anche

* Spazio dei nomi [System::IO](../)
* Libreria [Aspose.Slides](../../)