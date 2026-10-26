---
title: MulticastDelegate< ReturnType(ArgumentTypes...)>
second_title: Référence de l'API Aspose.Slides pour C++
description: "Représente une collection de délégués. Ce type doit être alloué sur la pile et transmis aux fonctions par valeur ou par référence. N'utilisez jamais System::SmartPtr classe pour gérer des objets de ce type."
type: docs
weight: 1080
url: /fr/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)> classe

Représente une collection de délégués. Ce type doit être alloué sur la pile et transmis aux fonctions par valeur ou par référence. N'utilisez jamais [System::SmartPtr](../smartptr/) classe pour gérer des objets de ce type.

```cpp
template<class ReturnType,class...>class MulticastDelegate< ReturnType(ArgumentTypes...)> : public System::Details::DelegateHoldingVariables
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| ReturnType | Type de retour des entités invoquables pointées par chaque délégué de la collection |
| ArgumentTypes | Liste d'arguments des entités invoquables pointées par chaque délégué de la collection |

## Méthodes

| Méthode | Description |
| --- | --- |
| [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\> [BeginInvoke](./begininvoke/)(ArgumentTypes..., const [AsyncCallback](../asynccallback/)\&, const CallbackArgumentType\&) | NON IMPLEMENTÉ. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([Callback](./callback/)) | Ajoute le délégué spécifié à la collection. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(std::function\<R(Args...)>) | Ajoute l'objet fonction spécifié à la collection de délégués. L'objet fonction est converti en type de délégué Callback avant d'être ajouté à la collection. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)([MulticastDelegate](./multicastdelegate/)\&) | Ajoute l'objet MulticastDelegate spécifié à la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, ClassType *) | Ajoute la méthode non statique spécifiée de l'objet spécifié à la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [connect](./connect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Ajoute la méthode non statique spécifiée de l'objet spécifié à la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([Callback](./callback/)) | Supprime le délégué spécifié de la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, ClassType *) | Supprime la méthode non statique spécifiée de l'objet spécifié de la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)(MemberType ClassType::*, const [SharedPtr](../sharedptr/)\<ClassType\>\&) | Supprime la méthode non statique spécifiée de l'objet spécifié de la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect](./disconnect/)([MulticastDelegate](./multicastdelegate/)\&) | Supprime l'objet MulticastDelegate spécifié de la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [disconnect_all_slots](./disconnect_all_slots/)() | Supprime tous les délégués de la collection de délégués. |
| **bool** [empty](./empty/)() const | Détermine si la collection de délégués est vide. |
| ReturnType [EndInvoke](./endinvoke/)(const [SharedPtr](../sharedptr/)\<[IAsyncResult](../iasyncresult/)\>\&) | NON IMPLEMENTÉ. |
| **bool** [Equals](./equals/)(const [MulticastDelegate](./multicastdelegate/)\&) |  |
| int [GetHashCode](./gethashcode/)() const |  |
| const [TypeInfo](../typeinfo/)\& [GetType](./gettype/)() const |  |
| ReturnType [invoke](./invoke/)(ArgumentTypes...) const | Invoque tous les délégués actuellement présents dans la collection de délégués. Les délégués sont invoqués dans le même ordre que celui dans lequel ils ont été ajoutés à la collection. La méthode bloque pendant l'exécution des délégués. |
| **bool** [IsNull](./isnull/)() const | Détermine si la collection de délégués est vide. |
|  [MulticastDelegate](./multicastdelegate/)() | Construit une collection vide. |
|  [MulticastDelegate](./multicastdelegate/)(std::nullptr_t) | Équivalent au constructeur par défaut. |
|  [MulticastDelegate](./multicastdelegate/)(const MulticastDelegate\&) | Effectue une copie superficielle de la collection de délégués. |
|  [MulticastDelegate](./multicastdelegate/)(MulticastDelegate\&&) | Constructeur de déplacement. |
|  [MulticastDelegate](./multicastdelegate/)([Callback](./callback/)\&&) | Construit une instance et ajoute le délégué spécifié à la collection de délégués. |
|  [MulticastDelegate](./multicastdelegate/)(T) | Construit une instance et ajoute la valeur spécifiée à la collection de délégués. |
|  [MulticastDelegate](./multicastdelegate/)(std::function\<ReturnType(ArgumentTypes...)>) | Construit une instance et ajoute la valeur spécifiée à la collection de délégués. |
| **bool** [operator!=](./operator_not_equal/)(const std::nullptr_t\&) const | Détermine si la collection de délégués n'est pas vide. |
| **bool** [operator!=](./operator_not_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Détermine si deux instances de MulticastDelegate - l'objet courant et l'objet spécifié - sont inégales. |
| ReturnType [operator()](./operator_call/)(ArgumentTypes...) const | Invoque tous les délégués actuellement présents dans la collection de délégués. Les délégués sont invoqués dans le même ordre que celui dans lequel ils ont été ajoutés à la collection. L'opérateur bloque pendant l'exécution des délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [operator+=](./operator_plus_equal/)([Callback](./callback/)) | Ajoute le délégué spécifié à la collection. |
| [MulticastDelegate](./multicastdelegate/)\& [operator-=](./operator_minus_equal/)([Callback](./callback/)) | Supprime le délégué spécifié de la collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) | Attribue la collection de délégués représentée par l'objet spécifié à l'objet courant. En conséquence, les deux objets pointent vers la même collection de délégués. |
| [MulticastDelegate](./multicastdelegate/)\& [operator=](./operator_equal/)([MulticastDelegate](./multicastdelegate/)\&&) | Opérateur d'affectation par déplacement. |
| **bool** [operator==](./operator_equal_equal/)(const std::nullptr_t\&) const | Détermine si la collection de délégués est vide. |
| **bool** [operator==](./operator_equal_equal/)(const [MulticastDelegate](./multicastdelegate/)\&) const | Détermine si deux instances de MulticastDelegate - l'objet courant et l'objet spécifié - sont égales. |
| void [remove_empty_callbacks](./remove_empty_callbacks/)() const | Nettoie les rappels contenus qui sont vides (sans réellement appeler quoi que ce soit). |
| [String](../string/) [ToString](./tostring/)() const |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Renvoie une référence à l'objet [TypeInfo](../typeinfo/) représentant les informations de type de la classe MulticastDelegate. |
|  [~MulticastDelegate](./~multicastdelegate/)() | Destructeur. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Callback](./callback/) | Le type des délégués représentés par la classe MulticastDelegate. |
| [Function](./function/) | Le type de la fonction lié à la signature du délégué. |

## Voir également

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)