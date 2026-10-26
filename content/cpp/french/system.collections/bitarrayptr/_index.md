---
title: BitArrayPtr
second_title: Référence de l'API Aspose.Slides pour C++
description: Pointeur vers BitArray. Ce type est un pointeur pour gérer la suppression d'un autre objet. Il doit être alloué sur la pile et passé aux fonctions soit par valeur, soit par référence constante.
type: docs
weight: 14
url: /fr/system.collections/bitarrayptr/
---
## BitArrayPtr classe


Pointeur vers [BitArray](../bitarray/). Ce type est un pointeur pour gérer la suppression d'un autre objet. Il doit être alloué sur la pile et passé aux fonctions soit par valeur, soit par référence constante.

```cpp
class BitArrayPtr : public System::SmartPtr<BitArray>
```

## Méthodes

| Method | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accesseur pour la méthode [begin()](../../system/smartptr/begin/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Accesseur pour la méthode [begin()](../../system/smartptr/begin/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../../system/smartptr/begin/). |
| [BitArrayPtr](./bitarrayptr/)() | Initialise un pointeur nul. |
| [BitArrayPtr](./bitarrayptr/)(const [SharedPtr](../../system/sharedptr/)\<[BitArray](../bitarray/)\>\&) | Constructeur de conversion. |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur en son propre type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur en type de base en utilisant static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur en type dérivé avec dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur en type dérivé avec dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accesseur pour la méthode [cbegin()](../../system/smartptr/cbegin/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Accesseur pour la méthode [cend()](../../system/smartptr/cend/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant const_cast sur l'objet pointé. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant dynamic_cast sur l'objet pointé. |
| auto [end](../../system/smartptr/end/)() | Accesseur pour la méthode [end()](../../system/smartptr/end/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Accesseur pour la méthode [end()](../../system/smartptr/end/) d'une collection sous-jacente. Ne compile que si SmartPtr_ est un type de spécialisation avec la méthode [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Obtient l'objet pointé. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Obtient le mode du pointeur. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Obtient l'objet pointé, mais vérifie que le pointeur est en mode partagé. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Obtient le nombre de pointeurs partagés existants vers l'objet référencé, y compris le courant. Vérifie que le pointeur actuel est en mode partagé. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Appelle [GetHashCode()](../../system/smartptr/gethashcode/) sur l'objet pointé. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Obtient l'objet référencé actuellement (le cas échéant) ou lance une exception. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Obtient l'objet pointé (le cas échéant) ou nullptr. Identique à [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Obtient l'objet référencé. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Obtient l'objet pointé (le cas échéant) ou nullptr. Identique à [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet pointé est d'un type spécifique ou d'un de ses types dérivés. Suit la sémantique 'is' de C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Vérifie si le pointeur pointe vers un autre objet que celui possédé (créé par un constructeur d'alias). |
| **bool** [IsNull](./isnull/)() const | Vérifie si la valeur spécifique est null. |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Vérifie si le pointeur est en mode partagé. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Vérifie si le pointeur est en mode faible. |
| explicit [operator bool](../../system/smartptr/operator_bool/)() const | Vérifie que le pointeur n'est pas null. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Vérifie que le pointeur est null. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Obtient une référence à l'objet pointé. Vérifie que le pointeur n'est pas null. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Permet d'accéder aux membres de l'objet référencé. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Assignation par déplacement de l'objet [SmartPtr](../../system/smartptr/). x devient inutilisable. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Assignation par copie de l'objet [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Assignation par copie de l'objet [SmartPtr](../../system/smartptr/). Effectue les conversions de type requises. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Assigne un pointeur brut à l'objet [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Définit la valeur du pointeur à nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Vérifie si le pointeur pointe vers nullptr. |
| **BitArray::Reference** [operator[]](./operator[]/)(int) const | Accesseur de bit. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Supprime l'alias (créé par un constructeur d'alias) du pointeur, s'assure qu'il gère (si partagé) ou suit (si faible) le même objet qu'il pointe. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Définit l'objet pointé. |
| void [reset](../../system/smartptr/reset/)() | Fait pointer le pointeur vers nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Définit le mode du pointeur. Peut modifier les comptes de référence de l'objet référencé. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Appelle la méthode SetTemplateWeakPtr() sur l'objet pointé (le cas échéant). |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Crée un objet [SmartPtr](../../system/smartptr/) avec le mode requis. |
| [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Crée un objet [SmartPtr](../../system/smartptr/) pointeur nul avec le mode requis. |
| [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Crée un [SmartPtr](../../system/smartptr/) pointant vers l'objet spécifié, ou convertit un pointeur brut en [SmartPtr](../../system/smartptr/). |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par copie l'objet [SmartPtr](../../system/smartptr/). Les deux pointeurs pointent alors vers le même objet. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par copie l'objet [SmartPtr](../../system/smartptr/). Les deux pointeurs pointent alors vers le même objet. Effectue la conversion de type si autorisée. |
| [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par déplacement l'objet [SmartPtr](../../system/smartptr/). Échange effectivement les deux pointeurs s'ils sont du même mode. x peut devenir inutilisable après l'appel. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Convertit le type du tableau référencé en créant un nouveau tableau d'un type différent. Utile si en C# il existe un cast de type de tableau non supporté en C++. |
| explicit [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialise un tableau vide. Utilisé pour traduire certains constructs de code C#. |
| [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construit un [SmartPtr](../../system/smartptr/) qui partage les informations de possession avec la valeur initiale de ptr, mais détient un pointeur non lié et non géré p. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant static_cast sur l'objet pointé. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Convertit tout type de pointeur en pointeur vers [Object](../../system/object/). Ne nécessite pas que le type Pointee_ soit complet. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Raccourci pour obtenir l'objet [System::TypeInfo](../../system/typeinfo/) pour le type Pointee_. |
| [~SmartPtr](../../system/smartptr/~smartptr/)() | Détruit l'objet [SmartPtr](../../system/smartptr/). Si nécessaire, diminue le compteur de références de l'objet pointé et supprime l'objet. |

## Voir aussi

* Classe [SmartPtr](../../system/smartptr/)
* Espace de noms [System::Collections](../)
* Bibliothèque [Aspose.Slides](../../)