---
title: BasicSystemIStreamWrapper
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen std::istream-ähnlichen Wrapper dar, der BasicSystemIOStreamBuf als internen Puffer verwendet."
type: docs
weight: 66
url: /de/system.io/basicsystemistreamwrapper/
---
## BasicSystemIStreamWrapper Klasse

Stellt einen std::istream-ähnlichen Wrapper dar, der [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) als internen Puffer verwendet.

```cpp
template<typename Elem,typename Traits>class BasicSystemIStreamWrapper : public std::basic_istream<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIStreamWrapper](./)\&&) | Wird im Move-Konstruktor und Move-Zuweisungsoperator verwendet, um Zeiger zurückzusetzen und [swap()](./swap/) aufzurufen. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Erstellt eine neue Instanz von [BasicSystemIStreamWrapper](./). |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)(const [BasicSystemIStreamWrapper](./)\&) | Copy-Konstruktor. Gelöscht. |
|  [BasicSystemIStreamWrapper](./basicsystemistreamwrapper/)([BasicSystemIStreamWrapper](./)\&&) | Move-Konstruktor. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIStreamWrapper](./)\&) | Copy-Zuweisungsoperator. Gelöscht. |
| [BasicSystemIStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIStreamWrapper](./)\&&) | Move-Zuweisungsoperator. |
| void [swap](./swap/)([BasicSystemIStreamWrapper](./)\&) | Aufruf von swap *this und **right**, falls sie nicht gleich sind. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Siehe auch

* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)