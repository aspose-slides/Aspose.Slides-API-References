---
title: BasicSystemIOStreamWrapper
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente un wrapper de type std::iostream qui utilise BasicSystemIOStreamBuf comme tampon interne."
type: docs
weight: 53
url: /fr/system.io/basicsystemiostreamwrapper/
---
## BasicSystemIOStreamWrapper classe

Représente un wrapper de type std::iostream qui utilise [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) comme tampon interne.

```cpp
template<typename Elem,typename Traits>class BasicSystemIOStreamWrapper : public std::basic_iostream<Elem, std::char_traits<Elem>>
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemIOStreamWrapper](./)\&&) | Utilisé dans le constructeur de déplacement et l'opérateur d'affectation de déplacement pour réinitialiser les pointeurs et appeler [swap()](./swap/). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Construit une nouvelle instance de [BasicSystemIOStreamWrapper](./). |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)(const [BasicSystemIOStreamWrapper](./)\&) | Constructeur de copie. Supprimé. |
|  [BasicSystemIOStreamWrapper](./basicsystemiostreamwrapper/)([BasicSystemIOStreamWrapper](./)\&&) | Constructeur de déplacement. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemIOStreamWrapper](./)\&) | Opérateur d'affectation de copie. Supprimé. |
| [BasicSystemIOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemIOStreamWrapper](./)\&&) | Opérateur d'affectation de déplacement. |
| void [swap](./swap/)([BasicSystemIOStreamWrapper](./)\&) | Appel à swap *this et **right**, s'ils ne sont pas égaux. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [char_type](./char_type/) |  |
| [traits_type](./traits_type/) |  |
| [Mybase](./mybase/) |  |
| [Mysb](./mysb/) |  |

## Voir aussi

* Espace de noms [System::IO](../)
* Bibliothèque [Aspose.Slides](../../)