---
title: BasicSystemIOStreamBuf
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un tampon qui enveloppe des flux de type System::IO::Stream et permet de les utiliser comme tampon interne de flux de type std::iostream."
type: docs
weight: 40
url: /fr/system.io/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf classe

Représente un tampon qui enveloppe [System::IO::Stream](../stream/)-like streams et permet de les utiliser comme tampon interne de flux de type std::iostream.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamBuf : public std::basic_streambuf<Elem, std::char_traits<Elem>>
```

## Méthodes

| Method | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamBuf](./)\&&) | Utilisé dans le constructeur de déplacement et l'opérateur d'affectation de déplacement pour réinitialiser les pointeurs et appeler [swap()](./swap/). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)() | Construit une nouvelle instance de [BasicSystemIOStreamBuf](./). |
| explicit  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/), const std::locale\&) | Construit une nouvelle instance de [BasicSystemIOStreamBuf](./). |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)(const [BasicSystemIOStreamBuf](./)\&) | Constructeur de copie. Supprimé. |
|  [BasicSystemIOStreamBuf](./basicsystemiostreambuf/)([BasicSystemIOStreamBuf](./)\&&) | Constructeur de déplacement. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamBuf](./)\&) | Opérateur d'affectation de copie. Supprimé. |
| [BasicSystemIOStreamBuf](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamBuf](./)\&&) | Opérateur d'affectation de déplacement. |
| void [swap](./swap/)([BasicSystemIOStreamBuf](./)\&) | Appel à swap *this et right, s'ils ne sont pas égaux. |
|  [~BasicSystemIOStreamBuf](./~basicsystemiostreambuf/)() override | Destructeur. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mysb](./mysb/) |  |
| [int_type](./int_type/) |  |
| [pos_type](./pos_type/) |  |
| [off_type](./off_type/) |  |

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)