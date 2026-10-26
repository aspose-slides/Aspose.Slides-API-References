---
title: BasicSystemOStreamWrapper
second_title: Référence API Aspose.Slides pour C++
description: "Représente un wrapper de type std::ostream qui utilise BasicSystemIOStreamBuf comme tampon interne."
type: docs
weight: 79
url: /fr/system.io/basicsystemostreamwrapper/
---
## BasicSystemOStreamWrapper classe

Represente un wrapper de type std::ostream qui utilise [BasicSystemIOStreamBuf](../basicsystemiostreambuf/) comme tampon interne.

```cpp
template<typename Elem,typename Traits>class BasicSystemOStreamWrapper : public std::basic_ostream<Elem, std::char_traits<Elem>>
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [AssignRV](./assignrv/)([BasicSystemOStreamWrapper](./)\&&) | Utilisé dans le constructeur de déplacement et l'opérateur d'affectation de déplacement pour réinitialiser les pointeurs et appeler [swap()](./swap/). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>, [SystemIOStreamWrappingMode](../systemiostreamwrappingmode/)) | Construit une nouvelle instance de [BasicSystemOStreamWrapper](./). |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)(const [BasicSystemOStreamWrapper](./)\&) | Constructeur de copie. Supprimé. |
|  [BasicSystemOStreamWrapper](./basicsystemostreamwrapper/)([BasicSystemOStreamWrapper](./)\&&) | Constructeur de déplacement. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)(const [BasicSystemOStreamWrapper](./)\&) | Opérateur d'affectation de copie. Supprimé. |
| [BasicSystemOStreamWrapper](./)\& [operator=](./operator_equal/)([BasicSystemOStreamWrapper](./)\&&) | Opérateur d'affectation de déplacement. |
| void [swap](./swap/)([BasicSystemOStreamWrapper](./)\&) | Appel à l'échange de *this et **right**, s'ils ne sont pas égaux. |

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