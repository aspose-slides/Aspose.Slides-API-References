---
title: ListPtr
second_title: Référence API Aspose.Slides pour C++
description: Pointeur de liste avec opérateurs d'accès. Ce type est un pointeur pour gérer la suppression d'autres objets. Il doit être alloué sur la pile et passé aux fonctions soit par valeur, soit par référence constante.
type: docs
weight: 456
url: /fr/system.collections.generic/listptr/
---
## ListPtr classe


[List](../list/) pointeur avec opérateurs d’accès. Ce type est un pointeur pour gérer la suppression d’autres objets. Il doit être alloué sur la pile et passé aux fonctions soit par valeur, soit par référence constante.

```cpp
template<typename T>class ListPtr : public System::SmartPtr<List<T>>
```

## Méthodes

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accesseur de la méthode [begin()](../../system/smartptr/begin/) d’une collection sous-jacente. Compile uniquement si SmartPtr_ est un type de spécialisation possédant la méthode [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Accesseur de la méthode [begin()](../../system/smartptr/begin/) d’une collection sous-jacente. Compile uniquement si SmartPtr_ est un type de spécialisation possédant la méthode [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur en son propre type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur au type de base en utilisant static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur au type dérivé en utilisant dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur au type dérivé en utilisant dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accesseur de la méthode [cbegin()](../../system/smartptr/cbegin/) d’une collection sous-jacente. Compile uniquement si SmartPtr_ est un type de spécialisation possédant la méthode [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Accesseur de la méthode [cend()](../../system/smartptr/cend/) d’une collection sous-jacente. Compile uniquement si SmartPtr_ est un type de spécialisation possédant la méthode [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant const_cast sur l’objet pointé. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant dynamic_cast sur l’objet pointé. |
| auto [end](../../system/smartptr/end/)() | Accesseur de la méthode [end()](../../system/smartptr/end/) d’une collection sous-jacente. Compile uniquement si SmartPtr_ est un type de spécialisation possédant la méthode [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Accesseur de la méthode [end()](../../system/smartptr/end/) d’une collection sous-jacente. Compile uniquement si SmartPtr_ est un type de spécialisation possédant la méthode [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Obtient l’objet pointé. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Obtient le mode du pointeur. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Obtient l’objet pointé, mais affirme que le pointeur est en mode partagé. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Obtient le nombre de pointeurs partagés existants vers l’objet référencé, y compris le présent. Affirme que le pointeur actuel est en mode partagé. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Appelle [GetHashCode()](../../system/smartptr/gethashcode/) sur l’objet pointé. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Obtient l’objet actuellement référencé (le cas échéant) ou lève une exception. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Obtient l’objet pointé (le cas échéant) ou nullptr. Identique à [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Obtient l’objet référencé. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Obtient l’objet pointé (le cas échéant) ou nullptr. Identique à [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l’objet pointé est d’un type spécifique ou d’un de ses sous-types. Suit la sémantique 'is' de C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Vérifie si le pointeur pointe vers un autre objet que celui possédé (créé par un constructeur d’alias). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Vérifie si le pointeur est en mode partagé. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Vérifie si le pointeur est en mode faible. |
|  [ListPtr](./listptr/)(std::nullptr_t) | Initialise un pointeur nul. |
|  [ListPtr](./listptr/)(const [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\>\&) | Initialise le pointeur vers la liste spécifiée. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Vérifie que le pointeur n’est pas nul. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Vérifie que le pointeur est nul. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Obtient une référence à l’objet pointé. Affirme que le pointeur n’est pas nul. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Permet d’accéder aux membres de l’objet référencé. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Assignation par déplacement de l’objet [SmartPtr](../../system/smartptr/). x devient inutilisable. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Assignation par copie de l’objet [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Assignation par copie de l’objet [SmartPtr](../../system/smartptr/). Effectue les conversions de type requises. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Assigne un pointeur brut à l’objet [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Définit la valeur du pointeur à nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vérifie si le pointeur [List](../list/) est nul. |
| std::vector\<T\>::reference [operator[]](./operator[]/)(int) | Accesseur. |
| std::vector\<T\>::const_reference [operator[]](./operator[]/)(int) const | Accesseur. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Supprime l’alias (créé par un constructeur d’alias) du pointeur, en s’assurant qu’il gère (si partagé) ou suit (si faible) le même objet vers lequel il pointe. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Définit l’objet pointé. |
| void [reset](../../system/smartptr/reset/)() | Fait pointer le pointeur vers nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Définit le mode du pointeur. Peut modifier les compteurs de références de l’objet référencé. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Appelle la méthode SetTemplateWeakPtr() sur l’objet pointé (le cas échéant). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Crée un objet [SmartPtr](../../system/smartptr/) du mode requis. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Crée un objet [SmartPtr](../../system/smartptr/) pointeur nul du mode requis. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Crée un [SmartPtr](../../system/smartptr/) pointant vers l’objet spécifié, ou convertit un pointeur brut en [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par copie un objet [SmartPtr](../../system/smartptr/). Les deux pointeurs pointent alors vers le même objet. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par copie un objet [SmartPtr](../../system/smartptr/). Les deux pointeurs pointent alors vers le même objet. Effectue la conversion de type si autorisée. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par déplacement un objet [SmartPtr](../../system/smartptr/). Effectivement, échange deux pointeurs s’ils sont du même mode. x peut devenir inutilisable après l’appel. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Convertit le type du tableau référencé en créant un nouveau tableau d’un type différent. Utile si en C# il existe un cast de type de tableau non supporté en C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialise un tableau vide. Utilisé pour traduire certaines constructions de code C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construit un [SmartPtr](../../system/smartptr/) qui partage les informations de propriété avec la valeur initiale de ptr, mais détient un pointeur p non lié et non géré. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant static_cast sur l’objet pointé. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Convertit tout type de pointeur en pointeur vers [Object](../../system/object/). N’exige pas que le type Pointee_ soit complet. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Raccourci pour obtenir l’objet [System::TypeInfo](../../system/typeinfo/) du type Pointee_. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Détruit l’objet [SmartPtr](../../system/smartptr/). Si nécessaire, diminue le compteur de références de l’objet pointé et supprime l’objet. |

## Voir aussi

* Classe [SmartPtr](../../system/smartptr/)
* Espace de noms [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)