---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides pro C++ API Reference
description: "Představuje buffer, který obaluje streamy podobné System::IO::Stream a umožňuje je použít jako interní buffer streamů podobných std::iostream."
type: docs
weight: 40
url: /cs/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf třída


Představuje buffer, který obaluje [System::IO::Stream](../stream/)-like streamy a umožňuje je použít jako interní buffer streamů podobných std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Používá se v přesunovacím konstruktoru a operátoru přiřazení přesunem k resetování ukazatelů a volání [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Vytvoří novou instanci [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Vytvoří novou instanci [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Kopírovací konstruktor. Odstraněno. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Přesunovací konstruktor. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Operátor přiřazení kopie. Odstraněno. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Operátor přiřazení přesunem. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Volá výměnu *this a right, pokud nejsou stejné. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destruktor. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Viz také

* jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)