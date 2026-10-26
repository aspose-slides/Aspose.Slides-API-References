---
title: WeakPtr
second_title: Référence de l'API Aspose.Slides pour C++
description: "Sous-classe de System::SmartPtr qui se place en mode faible lors de la construction. Veuillez noter que cette classe ne garantit pas que son instance restera toujours en mode faible puisque set_Mode() est toujours accessible. Ce type est un pointeur destiné à gérer la suppression d'autres objets. Il doit être alloué sur la pile et transmis aux fonctions soit par valeur, soit par référence constante."
type: docs
weight: 1470
url: /fr/system/weakptr/
---
## WeakPtr classe

Sous-classe de [System::SmartPtr](../smartptr/) qui se place en mode faible lors de la construction. Veuillez noter que cette classe ne garantit pas que son instance restera toujours en mode faible puisque [set_Mode()](../smartptr/set_mode/) reste accessible. Ce type est un pointeur destiné à gérer la suppression d'autres objets. Il doit être alloué sur la pile et transmis aux fonctions soit par valeur, soit par référence constante.

```cpp
template<class T>class WeakPtr : public System::SmartPtr<T>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | type pointé. |
## Méthodes

| Méthode | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accesseur pour la méthode [begin()](../smartptr/begin/) d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Accesseur pour la méthode [begin()](../smartptr/begin/) d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en son propre type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en type de base à l'aide de static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en type dérivé à l'aide de dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en type dérivé à l'aide de dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accesseur pour la méthode [cbegin()](../smartptr/cbegin/) d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Accesseur pour la méthode [cend()](../smartptr/cend/) d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Convertit le pointeur vers un type différent en utilisant const_cast sur l'objet pointé. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Convertit le pointeur vers un type différent en utilisant dynamic_cast sur l'objet pointé. |
| auto [end](../smartptr/end/)() | Accesseur pour la méthode [end()](../smartptr/end/) d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Accesseur pour la méthode [end()](../smartptr/end/) d'une collection sous-jacente. Se compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [end()](../smartptr/end/). |
| **bool** [expired](./expired/)() const | Vérifie si l'objet référencé a déjà été supprimé. |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Obtient l'objet pointé. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Obtient le mode du pointeur. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Obtient l'objet pointé, mais affirme que le pointeur est en mode partagé. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Obtient le nombre de pointeurs partagés existants vers l'objet référencé, y compris le présent. Affirme que le pointeur actuel est en mode partagé. |
| [Object](../object/) * [get_weak](./get_weak/)() const | Obtient l'objet référencé. Affirme que le pointeur est en mode faible. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Appelle [GetHashCode()](../smartptr/gethashcode/) sur l'objet pointé. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Obtient l'objet actuellement référencé (le cas échéant) ou lance une exception. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Obtient l'objet pointé (le cas échéant) ou nullptr. Identique à [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Obtient l'objet référencé. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Obtient l'objet pointé (le cas échéant) ou nullptr. Identique à [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet pointé est d'un type spécifique ou de son type dérivé. Suit la sémantique 'is' de C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Vérifie si le pointeur pointe vers un autre objet que celui possédé (créé par un constructeur d'alias). |
| **bool** [IsShared](../smartptr/isshared/)() const | Vérifie si le pointeur est en mode partagé. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Vérifie si le pointeur est en mode faible. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Vérifie si le pointeur n'est pas nul. |
| **bool** [operator!](../smartptr/operator_not/)() const | Vérifie si le pointeur est nul. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Obtient une référence à l'objet pointé. Affirme que le pointeur n'est pas nul. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Permet d'accéder aux membres de l'objet référencé. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../smartptr/). |
| [WeakPtr](./)\& [operator=](./operator_equal/)(Q\&&) | Attribue une valeur au pointeur faible. Appelle l'opérateur d'assignation spécifique de SmartPtr_. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Assigne par déplacement l'objet [SmartPtr](../smartptr/). x devient inutilisable. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Assigne par copie l'objet [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Assigne par copie l'objet [SmartPtr](../smartptr/). Effectue les conversions de type requises. |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)([Pointee_](../smartptr/pointee_/) *) | Attribue un pointeur brut à l'objet [SmartPtr](../smartptr/). |
| [SmartPtr_](../smartptr/smartptr_/)\& [operator=](../smartptr/operator_equal/)(std::nullptr_t) | Définit la valeur du pointeur à nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vérifie si le pointeur faible est nul. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Supprime l'aliasage (créé par un constructeur d'alias) du pointeur, s'assure qu'il gère (si partagé) ou suit (si faible) le même objet qu'il pointe. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Définit l'objet pointé. |
| void [reset](../smartptr/reset/)() | Fait pointer le pointeur vers nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Définit le mode du pointeur. Peut modifier les compteurs de référence de l'objet référencé. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Appelle la méthode SetTemplateWeakPtr() sur l'objet pointé (le cas échéant). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Crée un objet [SmartPtr](../smartptr/) du mode requis. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crée un objet [SmartPtr](../smartptr/) nul du mode requis. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crée un [SmartPtr](../smartptr/) pointant vers l'objet spécifié, ou convertit un pointeur brut en [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Construit par copie un objet [SmartPtr](../smartptr/). Les deux pointeurs pointent ensuite vers le même objet. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Construit par copie un objet [SmartPtr](../smartptr/). Les deux pointeurs pointent ensuite vers le même objet. Effectue la conversion de type si autorisée. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Construit par déplacement un objet [SmartPtr](../smartptr/). Effectivement, échange deux pointeurs s'ils sont du même mode. x peut être inutilisable après l'appel. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Convertit le type du tableau référencé en créant un nouveau tableau d'un type différent. Utile lorsqu'en C# il existe un cast de type tableau qui n'est pas supporté en C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initialise un tableau vide. Utilisé pour traduire certaines constructions de code C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construit un [SmartPtr](../smartptr/) qui partage les informations de possession avec la valeur initiale de ptr, mais contient un pointeur p non lié et non géré. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Convertit le pointeur vers un type différent en utilisant static_cast sur l'objet pointé. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Convertit n'importe quel type de pointeur en pointeur vers [Object](../object/). Ne nécessite pas que le type Pointee_ soit complet. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Raccourci pour obtenir l'objet [System::TypeInfo](../typeinfo/) pour le type Pointee_. |
|  [WeakPtr](./weakptr/)(std::nullptr_t) | Crée un pointeur nul. |
|  [WeakPtr](./weakptr/)([Pointee_](../smartptr/pointee_/) *) | Crée un pointeur faible vers l'objet donné. |
|  [WeakPtr](./weakptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&) | Crée un pointeur faible référant le même pointeur que ptr pointe. |
|  [WeakPtr](./weakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Crée un pointeur faible référant le même pointeur que x pointe. |
|  [WeakPtr](./weakptr/)(const [WeakPtr_](./weakptr_/)\&) | Construit par copie un pointeur faible. |
|  [WeakPtr](./weakptr/)(const [WeakPtr](./)\<Q\>\&) | Construit par copie un pointeur faible. |
|  [WeakPtr](./weakptr/)([SmartPtr_](../smartptr/smartptr_/)\&&) | Construit par déplacement un pointeur faible. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Détruit l'objet [SmartPtr](../smartptr/). Si nécessaire, décrémente le compteur de référence de l'objet pointé et supprime l'objet. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | Alias pour la classe [SmartPtr](../smartptr/) correspondante. |
| [WeakPtr_](./weakptr_/) | Alias pour le type lui-même. |
| [Pointee_](./pointee_/) | Type pointé. |
## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)