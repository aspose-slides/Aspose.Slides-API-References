---
title: BasicSystemIOStreamBuf
second_title: Aspose.Slides für C++ API-Referenz
description: "Stellt einen Puffer dar, der System::IO::Stream-ähnliche Streams einhüllt und es ermöglicht, sie als internen Puffer von std::iostream-ähnlichen Streams zu verwenden."
type: docs
weight: 40
url: /de/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf Klasse

Stellt einen Puffer dar, der [System::IO::Stream](../stream/)-ähnliche Streams einhüllt und es ermöglicht, sie als internen Puffer von std::iostream-ähnlichen Streams zu verwenden.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Wird im Move-Konstruktor und Move-Zuweisungsoperator verwendet, um Zeiger zurückzusetzen und [swap()](./swap/) aufzurufen. |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Konstruiert eine neue Instanz von [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Konstruiert eine neue Instanz von [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Copy-Konstruktor. Gelöscht. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Move-Konstruktor. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Kopierzuweisungsoperator. Gelöscht. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Move-Zuweisungsoperator. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Aufruf zum Tauschen von *this und right, falls sie nicht gleich sind. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destruktor. |

## Typdefinitionen

| Typdefinition | Beschreibung |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Siehe auch

* Namensraum [System::IO](../)
* Bibliothek [Aspose.Slides](../../)