---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides pro C++ referenci API
description: "Representuje obal podobný std::iostream, který použil BasicSystemIOStreamBuf jako vnitřní buffer."
type: docs
weight: 53
url: /cs/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper třída

Representuje obal podobný std::iostream, který použil [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) jako vnitřní buffer.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Metody

| Metoda | Popis |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Používá se v move konstruktoru a move přiřazovacím operátoru k resetování ukazatelů a volání [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Vytvoří novou instanci [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Kopírovací konstruktor. Odstraněno. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Move konstruktor. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Kopírovací přiřazovací operátor. Odstraněno. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Move přiřazovací operátor. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Volání swap *this a **right**, pokud nejsou stejné. |

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