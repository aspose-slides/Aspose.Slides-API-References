---
title: BasicSystemOStreamWrapper
second_title: Aspose.Slides für C++ API Referenz
description: "Stellt einen std::ostream-ähnlichen Wrapper dar, der BasicSystemIOStreamBuf als internen Puffer verwendet."
type: docs
weight: 79
url: /de/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper Klasse

Stellt einen std::ostream-ähnlichen Wrapper dar, der [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) als internen Puffer verwendet.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Wird im Move-Konstruktor und Move-Zuweisungsoperator verwendet, um Zeiger zurückzusetzen und [swap()](./swap/) aufzurufen. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Erstellt eine neue Instanz von [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Copy-Konstruktor. Gelöscht. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Move-Konstruktor. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Copy-Zuweisungsoperator. Gelöscht. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Move-Zuweisungsoperator. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Aufruf zum Tauschen von *this und **right**, wenn sie nicht gleich sind. |

## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Siehe auch

* Namespace [System::IO](../)
* Bibliothek [Aspose.Slides](../../)