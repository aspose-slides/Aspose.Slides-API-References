---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides pro C++ API Reference
description: "Představuje obal podobný std::ostream, který používal BasicSystemIOStreamBuf jako vnitřní vyrovnávací paměť."
type: docs
weight: 79
url: /cs/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper třída

Představuje obal podobný std::ostream, který používá [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) jako vnitřní vyrovnávací paměť.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Používá se v move konstruktoru a move přiřazovacím operátoru k resetování ukazatelů a volání [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Vytvoří novou instanci [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Kopírovací konstruktor. Smazán. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Move konstruktor. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Kopírovací přiřazovací operátor. Smazán. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Move přiřazovací operátor. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Volá výměnu *this a **right**, pokud nejsou rovny. |

## Typedefy

| Typedef | Popis |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Viz také

* jmenný prostor [System::IO](../)
* Knihovna [Aspose.Slides](../../)