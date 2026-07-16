---
title: X509CertificateCollectionPtr
second_title: Référence de l'API Aspose.Slides pour C++
description: Pointeur vers une collection de certificats X509. Ce type est un pointeur pour gérer la suppression d'un autre objet. Il doit être alloué sur la pile et passé aux fonctions soit par valeur, soit par référence const.
type: docs
weight: 92
url: /fr/system.security.cryptography.x509certificates/x509certificatecollectionptr/
---
## X509CertificateCollectionPtr classe

Pointeur vers une collection de certificats X509. Ce type est un pointeur pour gérer la suppression d'un autre objet. Il doit être alloué sur la pile et passé aux fonctions soit par valeur, soit par référence const.

```cpp
class X509CertificateCollectionPtr : public System::SmartPtr<X509CertificateCollection>
```

## Méthodes

| Méthode | Description |
| --- | --- |
| auto [begin](../../system/smartptr/begin/)() | Accesseur de la méthode [begin()](../../system/smartptr/begin/) d'une collection sous-jacent. Compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../../system/smartptr/begin/). |
| auto [begin](../../system/smartptr/begin/)() const | Accesseur de la méthode [begin()](../../system/smartptr/begin/) d'une collection sous-jacent. Compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [begin()](../../system/smartptr/begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur vers son propre type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur vers le type de base en utilisant static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur vers le type dérivé en utilisant dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](../../system/smartptr/)\<Y\>\> [Cast](../../system/smartptr/cast/)() const | Convertit le pointeur vers le type dérivé en utilisant dynamic_cast. |
| auto [cbegin](../../system/smartptr/cbegin/)() const | Accesseur de la méthode [cbegin()](../../system/smartptr/cbegin/) d'une collection sous-jacent. Compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [cbegin()](../../system/smartptr/cbegin/). |
| auto [cend](../../system/smartptr/cend/)() const | Accesseur de la méthode [cend()](../../system/smartptr/cend/) d'une collection sous-jacent. Compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [cend()](../../system/smartptr/cend/). |
| [SmartPtr](../../system/smartptr/)\<Y\> [const_pointer_cast](../../system/smartptr/const_pointer_cast/)() const | Convertit le pointeur vers un type différent en utilisant const_cast sur l'objet pointé. |
| [SmartPtr](../../system/smartptr/)\<Y\> [dynamic_pointer_cast](../../system/smartptr/dynamic_pointer_cast/)() const | Convertit le pointeur vers un type différent en utilisant dynamic_cast sur l'objet pointé. |
| auto [end](../../system/smartptr/end/)() | Accesseur de la méthode [end()](../../system/smartptr/end/) d'une collection sous-jacent. Compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [end()](../../system/smartptr/end/). |
| auto [end](../../system/smartptr/end/)() const | Accesseur de la méthode [end()](../../system/smartptr/end/) d'une collection sous-jacent. Compile uniquement si SmartPtr_ est un type de spécialisation avec la méthode [end()](../../system/smartptr/end/). |
| [Pointee_](../../system/smartptr/pointee_/) * [get](../../system/smartptr/get/)() const | Obtient l'objet pointé. |
| [SmartPtrMode](../../system/smartptrmode/) [get_Mode](../../system/smartptr/get_mode/)() const | Obtient le mode du pointeur. |
| [Pointee_](../../system/smartptr/pointee_/) * [get_shared](../../system/smartptr/get_shared/)() const | Obtient l'objet pointé, mais affirme que le pointeur est en mode partagé. |
| int [get_shared_count](../../system/smartptr/get_shared_count/)() const | Obtient le nombre de pointeurs partagés existant vers l'objet référencé, y compris le présent. Affirme que le pointeur actuel est en mode partagé. |
| int [GetHashCode](../../system/smartptr/gethashcode/)() const | Appelle [GetHashCode()](../../system/smartptr/gethashcode/) sur l'objet pointé. |
| T * [GetObjectNotNull](../../system/smartptr/getobjectnotnull/)() const | Obtient l'objet actuellement référencé (s'il existe) ou lève une exception. |
| [Object](../../system/object/) * [GetObjectOrNull](../../system/smartptr/getobjectornull/)() const | Obtient l'objet pointé (s'il existe) ou nullptr. Identique à [get()](../../system/smartptr/get/). |
| [Object](../../system/object/) * [GetObjectOwner](../../system/smartptr/getobjectowner/)() const | Obtient l'objet référencé. |
| [Pointee_](../../system/smartptr/pointee_/) * [GetPointer](../../system/smartptr/getpointer/)() const | Obtient l'objet pointé (s'il existe) ou nullptr. Identique à [get()](../../system/smartptr/get/). |
| **bool** [Is](../../system/smartptr/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet pointé est d'un type spécifique ou d'un de ses types dérivés. Suit la sémantique 'is' de C#. |
| **bool** [IsAliasingPtr](../../system/smartptr/isaliasingptr/)() const | Vérifie si le pointeur pointe vers un autre objet que celui possédé (créé par un constructeur d'aliasing). |
| **bool** [IsShared](../../system/smartptr/isshared/)() const | Vérifie si le pointeur est en mode partagé. |
| **bool** [IsWeak](../../system/smartptr/isweak/)() const | Vérifie si le pointeur est en mode faible. |
| explicit  [operator bool](../../system/smartptr/operator_bool/)() const | Vérifie si le pointeur n'est pas nul. |
| **bool** [operator!](../../system/smartptr/operator_not/)() const | Vérifie si le pointeur est nul. |
| [Pointee_](../../system/smartptr/pointee_/)\& [operator*](../../system/smartptr/operator_star/)() const | Obtient une référence à l'objet pointé. Affirme que le pointeur n'est pas nul. |
| [Pointee_](../../system/smartptr/pointee_/) * [operator->](../../system/smartptr/operator_minus_greater/)() const | Permet d'accéder aux membres de l'objet référencé. |
| **bool** [operator<](../../system/smartptr/operator_less/)(Y *) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../../system/smartptr/). |
| **bool** [operator<](../../system/smartptr/operator_less/)([SmartPtr](../../system/smartptr/)\<Y\> const\&) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&) | Assigne par déplacement l'objet [SmartPtr](../../system/smartptr/). x devient inutilisable. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&) | Assigne par copie l'objet [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&) | Assigne par copie l'objet [SmartPtr](../../system/smartptr/). Effectue les conversions de type requises. |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)([Pointee_](../../system/smartptr/pointee_/) *) | Assigne le pointeur brut à l'objet [SmartPtr](../../system/smartptr/). |
| [SmartPtr_](../../system/smartptr/smartptr_/)\& [operator=](../../system/smartptr/operator_equal/)(std::nullptr_t) | Définit la valeur du pointeur à nullptr. |
| **bool** [operator==](../../system/smartptr/operator_equal_equal/)(std::nullptr_t) const | Vérifie si le pointeur pointe vers nullptr. |
| [SharedPtr](../../system/sharedptr/)\<[X509Certificate](../x509certificate/)\>\& [operator[]](./operator[]/)(int) const | Accesseur. |
| [SmartPtr_](../../system/smartptr/smartptr_/) [RemoveAliasing](../../system/smartptr/removealiasing/)() const | Supprime l'aliasing (créé par un constructeur d'aliasing) du pointeur, s'assure qu'il gère (si partagé) ou suit (si faible) le même objet vers lequel il pointe. |
| void [reset](../../system/smartptr/reset/)([Pointee_](../../system/smartptr/pointee_/) *) | Définit l'objet pointé. |
| void [reset](../../system/smartptr/reset/)() | Fait pointer le pointeur vers nullptr. |
| void [set_Mode](../../system/smartptr/set_mode/)([SmartPtrMode](../../system/smartptrmode/)) | Définit le mode du pointeur. Peut modifier les compteurs de référence de l'objet référencé. |
| void [SetContainedTemplateWeakPtr](../../system/smartptr/setcontainedtemplateweakptr/)(**uint32_t**) const | Appelle la méthode SetTemplateWeakPtr() sur l'objet pointé (s'il existe). |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtrMode](../../system/smartptrmode/)) | Crée un objet [SmartPtr](../../system/smartptr/) du mode requis. |
|  [SmartPtr](../../system/smartptr/smartptr/)(std::nullptr_t, [SmartPtrMode](../../system/smartptrmode/)) | Crée un objet [SmartPtr](../../system/smartptr/) pointeur nul du mode requis. |
|  [SmartPtr](../../system/smartptr/smartptr/)([Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Crée un [SmartPtr](../../system/smartptr/) pointant vers l'objet spécifié, ou convertit un pointeur brut en [SmartPtr](../../system/smartptr/). |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr_](../../system/smartptr/smartptr_/)\&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par copie un objet [SmartPtr](../../system/smartptr/). Les deux pointeurs pointent alors vers le même objet. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<Q\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par copie un objet [SmartPtr](../../system/smartptr/). Les deux pointeurs pointent alors vers le même objet. Effectue la conversion de type si autorisée. |
|  [SmartPtr](../../system/smartptr/smartptr/)([SmartPtr_](../../system/smartptr/smartptr_/)\&&, [SmartPtrMode](../../system/smartptrmode/)) | Construit par déplacement un objet [SmartPtr](../../system/smartptr/). En pratique, échange deux pointeurs s'ils sont du même mode. x peut devenir inutilisable après l'appel. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<[Array](../../system/array/)\<Y\>\>\&, [SmartPtrMode](../../system/smartptrmode/)) | Convertit le type du tableau référencé en créant un nouveau tableau d'un type différent. Utile si en C# il existe un cast de type de tableau qui n'est pas supporté en C++. |
| explicit  [SmartPtr](../../system/smartptr/smartptr/)(const Y\&) | Initialise un tableau vide. Utilisé pour traduire certaines constructions de code C#. |
|  [SmartPtr](../../system/smartptr/smartptr/)(const [SmartPtr](../../system/smartptr/)\<P\>\&, [Pointee_](../../system/smartptr/pointee_/) *, [SmartPtrMode](../../system/smartptrmode/)) | Construit un [SmartPtr](../../system/smartptr/) qui partage les informations de possession avec la valeur initiale de ptr, mais détient un pointeur p non lié et non géré. |
| [SmartPtr](../../system/smartptr/)\<Y\> [static_pointer_cast](../../system/smartptr/static_pointer_cast/)() const | Convertit le pointeur vers un type différent en utilisant static_cast sur l'objet pointé. |
| [SmartPtr](../../system/smartptr/)\<[Object](../../system/object/)\> [ToObjectPtr](../../system/smartptr/toobjectptr/)() const | Convertit n'importe quel type de pointeur en pointeur vers [Object](../../system/object/). Ne nécessite pas que le type Pointee_ soit complet. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/smartptr/type/)() | Raccourci pour obtenir l'objet [System::TypeInfo](../../system/typeinfo/) pour le type Pointee_. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)() | Constructeur de pointeur nul. |
|  [X509CertificateCollectionPtr](./x509certificatecollectionptr/)(const [SharedPtr](../../system/sharedptr/)\<[X509CertificateCollection](../x509certificatecollection/)\>\&) | Constructeur. |
|  [~SmartPtr](../../system/smartptr/~smartptr/)() | Détruit l'objet [SmartPtr](../../system/smartptr/). Si nécessaire, diminue le compteur de référence de l'objet pointé et supprime l'objet. |

## Voir aussi

* Classe [SmartPtr](../../system/smartptr/)
* Espace de noms [System::Security::Cryptography::X509Certificates](../)
* Bibliothèque [Aspose.Slides](../../)