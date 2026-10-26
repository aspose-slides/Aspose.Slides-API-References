---
title: DynamicWeakPtr
second_title: Référence de l'API Aspose.Slides pour C++
description: Classe de pointeur intelligent qui suit les modes des pointeurs des arguments de modèle de l'objet stocké et les met à jour après chaque affectation. Ce type est un pointeur permettant de gérer la suppression d'un autre objet. Il doit être alloué sur la pile et transmis aux fonctions soit par valeur, soit par référence constante.
type: docs
weight: 781
url: /fr/system/dynamicweakptr/
---
## DynamicWeakPtr classe

Classe de pointeur intelligent qui suit les modes des pointeurs des arguments de modèle de l'objet stocké et les met à jour après chaque affectation. Ce type est un pointeur pour gérer la suppression d'un autre objet. Il doit être alloué sur la pile et transmis aux fonctions soit par valeur, soit par référence constante.

```cpp
template<typename T,SmartPtrMode,unsigned int ...>class DynamicWeakPtr : public System::SmartPtr<T>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| Pointee | type. |
| trunkMode | Mode du pointeur intelligent lui-même, partagé ou faible. |
| weakLeafs | Indices des arguments de modèle du type stocké qui doivent être mis en mode pointeur faible. |

## Méthodes

| Méthode | Description |
| --- | --- |
| auto [begin](../smartptr/begin/)() | Accesseur de la méthode [begin()](../smartptr/begin/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../smartptr/begin/). |
| auto [begin](../smartptr/begin/)() const | Accesseur de la méthode [begin()](../smartptr/begin/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en son propre type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en type de base à l'aide de static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en type dérivé à l'aide de dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../smartptr/)\<Y\>\> [Cast](../smartptr/cast/)() const | Convertit le pointeur en type dérivé à l'aide de dynamic_cast. |
| auto [cbegin](../smartptr/cbegin/)() const | Accesseur de la méthode [cbegin()](../smartptr/cbegin/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [cbegin()](../smartptr/cbegin/). |
| auto [cend](../smartptr/cend/)() const | Accesseur de la méthode [cend()](../smartptr/cend/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [cend()](../smartptr/cend/). |
| [SmartPtr](../smartptr/)\<Y\> [const_pointer_cast](../smartptr/const_pointer_cast/)() const | Convertit le pointeur en un type différent à l'aide de const_cast sur l'objet pointé. |
| [SmartPtr](../smartptr/)\<Y\> [dynamic_pointer_cast](../smartptr/dynamic_pointer_cast/)() const | Convertit le pointeur en un type différent à l'aide de dynamic_cast sur l'objet pointé. |
|  [DynamicWeakPtr](./dynamicweakptr/)(std::nullptr_t) | Crée un pointeur intelligent nul. |
|  [DynamicWeakPtr](./dynamicweakptr/)([Pointee_](../smartptr/pointee_/) *) | Crée un pointeur intelligent pointant vers l'objet donné. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr_](./smartptr_/)\&) | Construit une copie du pointeur intelligent. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Construit une copie du pointeur intelligent. |
|  [DynamicWeakPtr](./dynamicweakptr/)(const [DynamicWeakPtr_](./dynamicweakptr_/)\&) | Construit une copie du pointeur intelligent. |
|  [DynamicWeakPtr](./dynamicweakptr/)([SmartPtr_](./smartptr_/)\&&) | Construit le pointeur intelligent par déplacement. |
| auto [end](../smartptr/end/)() | Accesseur de la méthode [end()](../smartptr/end/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [end()](../smartptr/end/). |
| auto [end](../smartptr/end/)() const | Accesseur de la méthode [end()](../smartptr/end/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [end()](../smartptr/end/). |
| [Pointee_](../smartptr/pointee_/) * [get](../smartptr/get/)() const | Obtient l'objet pointé. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](../smartptr/get_mode/)() const | Obtient le mode du pointeur. |
| [Pointee_](../smartptr/pointee_/) * [get_shared](../smartptr/get_shared/)() const | Obtient l'objet pointé, mais affirme que le pointeur est en mode partagé. |
| int [get_shared_count](../smartptr/get_shared_count/)() const | Obtient le nombre de pointeurs partagés existant vers l'objet référencé, y compris le pointeur actuel. Affirme que le pointeur actuel est en mode partagé. |
| int [GetHashCode](../smartptr/gethashcode/)() const | Appelle [GetHashCode()](../smartptr/gethashcode/) sur l'objet pointé. |
| T * [GetObjectNotNull](../smartptr/getobjectnotnull/)() const | Obtient l'objet actuellement référencé (s'il existe) ou lève une exception. |
| [Object](../object/) * [GetObjectOrNull](../smartptr/getobjectornull/)() const | Obtient l'objet pointé (s'il existe) ou nullptr. Identique à [get()](../smartptr/get/). |
| [Object](../object/) * [GetObjectOwner](../smartptr/getobjectowner/)() const | Obtient l'objet référencé. |
| [Pointee_](../smartptr/pointee_/) * [GetPointer](../smartptr/getpointer/)() const | Obtient l'objet pointé (s'il existe) ou nullptr. Identique à [get()](../smartptr/get/). |
| **bool** [Is](../smartptr/is/)(const [System::TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet pointé est d'un type spécifique ou d'un de ses sous-types. Suit la sémantique 'is' de C#. |
| **bool** [IsAliasingPtr](../smartptr/isaliasingptr/)() const | Vérifie si le pointeur pointe vers un autre objet que celui possédé (créé par un constructeur d'alias). |
| **bool** [IsShared](../smartptr/isshared/)() const | Vérifie si le pointeur est en mode partagé. |
| **bool** [IsWeak](../smartptr/isweak/)() const | Vérifie si le pointeur est en mode faible. |
| explicit  [operator bool](../smartptr/operator_bool/)() const | Vérifie si le pointeur n'est pas nul. |
| **bool** [operator!](../smartptr/operator_not/)() const | Vérifie si le pointeur est nul. |
| [Pointee_](../smartptr/pointee_/)\& [operator*](../smartptr/operator_star/)() const | Obtient une référence à l'objet pointé. Affirme que le pointeur n'est pas nul. |
| [Pointee_](../smartptr/pointee_/) * [operator->](../smartptr/operator_minus_greater/)() const | Permet d'accéder aux membres de l'objet référencé. |
| **bool** [operator<](../smartptr/operator_less/)(Y *) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../smartptr/). |
| **bool** [operator<](../smartptr/operator_less/)([SmartPtr](../smartptr/)\<Y\> const\&) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../smartptr/). |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Assigne le pointeur intelligent par déplacement. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Assigne le pointeur intelligent par copie. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](../smartptr/)\<Q\>\&) | Assigne le pointeur intelligent par copie. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(typename [SmartPtr_::Pointee_](../smartptr/pointee_/) *) | Assigne le pointeur intelligent. |
| [DynamicWeakPtr_](./dynamicweakptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Met le pointeur intelligent à nul. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vérifie si le pointeur intelligent est nul. |
| [SmartPtr_](../smartptr/smartptr_/) [RemoveAliasing](../smartptr/removealiasing/)() const | Supprime l'aliasage (créé par un constructeur d'alias) du pointeur, s'assure qu'il gère (si partagé) ou suit (si faible) le même objet qu'il pointe. |
| void [reset](../smartptr/reset/)([Pointee_](../smartptr/pointee_/) *) | Définit l'objet pointé. |
| void [reset](../smartptr/reset/)() | Fait pointer le pointeur vers nullptr. |
| void [set_Mode](../smartptr/set_mode/)([SmartPtrMode](../smartptrmode/)) | Définit le mode du pointeur. Peut modifier les comptes de référence de l'objet référencé. |
| void [SetContainedTemplateWeakPtr](../smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Appelle la méthode SetTemplateWeakPtr() sur l'objet pointé (s'il existe). |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtrMode](../smartptrmode/)) | Crée un objet [SmartPtr](../smartptr/) du mode requis. |
|  [SmartPtr](../smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crée un objet [SmartPtr](../smartptr/) nul du mode requis. |
|  [SmartPtr](../smartptr/smartptr/)([Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crée un [SmartPtr](../smartptr/) pointant vers l'objet spécifié, ou convertit un pointeur brut en [SmartPtr](../smartptr/). |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr_](../smartptr/smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Construit par copie un objet [SmartPtr](../smartptr/). Les deux pointeurs pointent ensuite vers le même objet. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Construit par copie un objet [SmartPtr](../smartptr/). Les deux pointeurs pointent ensuite vers le même objet. Effectue une conversion de type si autorisée. |
|  [SmartPtr](../smartptr/smartptr/)([SmartPtr_](../smartptr/smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Construit par déplacement un objet [SmartPtr](../smartptr/). En pratique, échange deux pointeurs s'ils sont du même mode. x peut être inutilisable après l'appel. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Convertit le type du tableau référencé en créant un nouveau tableau d'un type différent. Utile si en C# il existe un cast de type de tableau non supporté en C++. |
| explicit  [SmartPtr](../smartptr/smartptr/)(const Y\&) | Initialise un tableau vide. Utilisé pour traduire certaines constructions de code C#. |
|  [SmartPtr](../smartptr/smartptr/)(const [SmartPtr](../smartptr/)\<P\>\&, [Pointee_](../smartptr/pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construit un [SmartPtr](../smartptr/) qui partage les informations de propriété avec la valeur initiale de ptr, mais détient un pointeur p non lié et non géré. |
| [SmartPtr](../smartptr/)\<Y\> [static_pointer_cast](../smartptr/static_pointer_cast/)() const | Convertit le pointeur en un type différent à l'aide de static_cast sur l'objet pointé. |
| [SmartPtr](../smartptr/)\<[Object](../object/)\> [ToObjectPtr](../smartptr/toobjectptr/)() const | Convertit n'importe quel type de pointeur en pointeur vers [Object](../object/). Ne nécessite pas que le type Pointee_ soit complet. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](../smartptr/type/)() | Raccourci pour obtenir l'objet [System::TypeInfo](../typeinfo/) pour le type Pointee_. |
|  [~SmartPtr](../smartptr/~smartptr/)() | Détruit l'objet [SmartPtr](../smartptr/). Si nécessaire, diminue le compteur de références de l'objet pointé et supprime l'objet. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [SmartPtr_](./smartptr_/) | [SmartPtr](../smartptr/) alias de classe de base. |
| [DynamicWeakPtr_](./dynamicweakptr_/) | alias du type lui-même. |
| [Pointee_](./pointee_/) | type pointé. |

## Voir aussi

* Classe [SmartPtr](../smartptr/)
* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)