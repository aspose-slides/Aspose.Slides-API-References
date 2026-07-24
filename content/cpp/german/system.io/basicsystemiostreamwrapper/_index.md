---
title: BasicSystemIOStreamWrapper
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen std::iostream-ähnlichen Wrapper dar, der BasicSystemIOStreamBuf als internen Puffer verwendet."
type: docs
weight: 53
url: /de/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper Klasse

Stellt einen std::iostream-ähnlichen Wrapper dar, der [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) als internen Puffer verwendet.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Wird im Move-Konstruktor und Move-Zuweisungsoperator verwendet, um Zeiger zurückzusetzen und [swap()](./swap/) aufzurufen. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Erstellt eine neue Instanz von [BasicSystemIOStreamWrapper](./). |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Copy-Konstruktor. Gelöscht. |
| [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Move-Konstruktor. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Copy-Zuweisungsoperator. Gelöscht. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Move-Zuweisungsoperator. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Aufruf von swap *this und **right**, falls sie nicht gleich sind. |

## Typdefinitionen

| Typedef | Beschreibung |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Siehe Auch

* Namespace [System::IO](../)
* Bibliothek [Aspose.Slides](../../)