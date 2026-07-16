---
title: SmartPtr
second_title: Reference API Aspose.Slides pour C++
description: "Classe de pointeur pour encapsuler les types alloues sur le tas. Utilisez-la pour gerer la memoire des classes heritant de Object. Ce type de pointeur suit la semantique des pointeurs intrusifs. Le compteur de references est stocke soit dans Object lui-meme, soit dans une structure de compteur etroitement liee a l'instance Object. Dans tous les cas, toutes les instances de SmartPtr forment un groupe de possession unique, quel que soit leur mode de creation, ce qui differe du comportement de la classe std::shared_ptr. Convertir un pointeur brut en SmartPtr est sur tant qu'il existe d'autres instances de SmartPtr detenant des references partagees vers le meme objet. Une instance de la classe SmartPtr peut etre dans l'un des deux etats: pointeur partage et pointeur faible. Pour maintenir l'objet en vie, le nombre de references partagees doit rester positif. Les pointeurs faibles et partages peuvent etre utilises pour acceder a l'objet pointe (pour appeler des methodes, lire ou ecrire des champs, etc.), mais les pointeurs faibles ne participent pas au comptage des references du pointeur partage. L'objet est supprime lorsque le dernier pointeur 'shared' SmartPtr qui y fait reference est detruit. Veillez donc a ce que cela ne se produise pas lorsqu'aucun autre pointeur SmartPtr partage n'existe, par exemple pendant la construction ou la destruction de l'objet. Utilisez les objets sentinelles System::Object::ThisProtector (dans le code C++) ou les attributs CppCTORSelfReference ou CppSelfReference (dans le code C# traduit) pour resoudre ce probleme. De meme, assurez-vous de rompre les references cycliques en utilisant la classe de pointeur System::WeakPtr ou le mode de pointeur System::SmartPtrMode::Weak (dans le code C++) ou l'attribut CppWeakPtr (dans le code C# traduit). Si deux objets ou plus se referent mutuellement a l'aide de pointeurs 'shared', ils ne seront jamais supprimes. Si le type de pointeur (faible ou partage) doit etre change a l'execution, utilisez la methode System::SmartPtr<T>::set_Mode() ou la classe System::DynamicWeakPtr. La classe SmartPtr ne contient aucune methode virtuelle. Vous ne devez l'heriter que si vous creez votre propre strategie de gestion de memoire. Ce type est un pointeur destine a gerer la suppression d'un autre objet. Il doit etre alloue sur la pile et transmis aux fonctions soit par valeur, soit par reference constante."
type: docs
weight: 1210
url: /fr/system/smartptr/
---
## SmartPtr classe

Classe de pointeur pour encapsuler les types alloués sur le tas. Utilisez-la pour gérer la mémoire des classes héritant de [Object](../object/). Ce type de pointeur suit la sémantique des pointeurs intrusifs. Le compteur de références est stocké soit dans [Object](../object/) lui-même, soit dans une structure de compteur étroitement liée à l’instance [Object](../object/). Dans tous les cas, toutes les instances [SmartPtr](./) forment un groupe de possession unique, quel que soit leur mode de création, ce qui diffère du comportement de la classe std::shared_ptr. Convertir un pointeur brut en [SmartPtr](./) est sûr tant qu’il existe d’autres instances [SmartPtr](./) détenant des références partagées vers le même objet. Une instance de la classe [SmartPtr](./) peut être dans l’un des deux états : pointeur partagé et pointeur faible. Pour maintenir l’objet en vie, le nombre de références partagées vers celui-ci doit être positif. Les pointeurs faibles et partagés peuvent être utilisés pour accéder à l’objet pointé (pour appeler des méthodes, lire ou écrire des champs, etc.), mais les pointeurs faibles ne participent pas au comptage des références du pointeur partagé. [Object](../object/) est supprimé lorsque le dernier pointeur 'shared' [SmartPtr](./) qui y fait référence est détruit. Ainsi, assurez-vous que cela ne se produise pas lorsqu’aucun autre pointeur [SmartPtr](./) partagé vers l’objet n’existe, par exemple pendant la construction ou la destruction de l’objet. Utilisez les objets sentinelle System::Object::ThisProtector (dans le code C++) ou les attributs CppCTORSelfReference ou CppSelfReference (dans le code C# traduit) pour résoudre ce problème. De même, assurez-vous de rompre les références cycliques en utilisant la classe de pointeur [System::WeakPtr](../weakptr/) ou le mode de pointeur [System::SmartPtrMode::Weak](../smartptrmode/) (dans le code C++) ou l’attribut CppWeakPtr (dans le code C# traduit). Si deux objets ou plus se référencent mutuellement à l’aide de pointeurs 'shared', ils ne seront jamais supprimés. Si le type de pointeur (faible ou partagé) doit être changé à l’exécution, utilisez la méthode [System::SmartPtr<T>::set_Mode()](./set_mode/) ou la classe [System::DynamicWeakPtr](../dynamicweakptr/). La classe [SmartPtr](./) ne contient aucune méthode virtuelle. Vous ne devez l’hériter que si vous créez votre propre stratégie de gestion de mémoire. Ce type est un pointeur destiné à gérer la suppression d’un autre objet. Il doit être alloué sur la pile et transmis aux fonctions soit par valeur, soit par référence constante.

```cpp
template<class T>class SmartPtr
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type de l’objet pointé. Doit être soit [System::Object](../object/) ou une sous-classe de celui-ci. |

## Méthodes

| Méthode | Description |
| --- | --- |
| auto [begin](./begin/)() | Accesseur de la méthode [begin()](./begin/) d’une collection sous-jacent. Ne compile que si SmartPtr_ est un type de spécialisation possédant la méthode [begin()](./begin/). |
| auto [begin](./begin/)() const | Accesseur de la méthode [begin()](./begin/) d’une collection sous-jacent. Ne compile que si SmartPtr_ est un type de spécialisation possédant la méthode [begin()](./begin/). |
| std::enable_if_t\<std::is_same\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convertit le pointeur en son propre type. |
| std::enable_if_t<\!std::is_same\<Y, T\>::value\&&std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convertit le pointeur en type de base en utilisant static_cast. |
| std::enable_if_t\<Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convertit le pointeur en type dérivé en utilisant dynamic_cast. |
| std::enable_if_t<\!Check::value\&&\!std::is_same\<Y, T\>::value\&&\!std::is_base_of\<Y, T\>::value, [SmartPtr](./)\<Y\>\> [Cast](./cast/)() const | Convertit le pointeur en type dérivé en utilisant dynamic_cast. |
| auto [cbegin](./cbegin/)() const | Accesseur de la méthode [cbegin()](./cbegin/) d’une collection sous-jacent. Ne compile que si SmartPtr_ est un type de spécialisation possédant la méthode [cbegin()](./cbegin/). |
| auto [cend](./cend/)() const | Accesseur de la méthode [cend()](./cend/) d’une collection sous-jacent. Ne compile que si SmartPtr_ est un type de spécialisation possédant la méthode [cend()](./cend/). |
| [SmartPtr](./)\<Y\> [const_pointer_cast](./const_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant const_cast sur l’objet pointé. |
| [SmartPtr](./)\<Y\> [dynamic_pointer_cast](./dynamic_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant dynamic_cast sur l’objet pointé. |
| auto [end](./end/)() | Accesseur de la méthode [end()](./end/) d’une collection sous-jacent. Ne compile que si SmartPtr_ est un type de spécialisation possédant la méthode [end()](./end/). |
| auto [end](./end/)() const | Accesseur de la méthode [end()](./end/) d’une collection sous-jacent. Ne compile que si SmartPtr_ est un type de spécialisation possédant la méthode [end()](./end/). |
| [Pointee_](./pointee_/) * [get](./get/)() const | Obtient l’objet pointé. |
| [SmartPtrMode](../smartptrmode/) [get_Mode](./get_mode/)() const | Obtient le mode du pointeur. |
| [Pointee_](./pointee_/) * [get_shared](./get_shared/)() const | Obtient l’objet pointé, mais affirme que le pointeur est en mode partagé. |
| int [get_shared_count](./get_shared_count/)() const | Obtient le nombre de pointeurs partagés existants vers l’objet référencé, y compris le actuel. Affirme que le pointeur actuel est en mode partagé. |
| int [GetHashCode](./gethashcode/)() const | Appelle [GetHashCode()](./gethashcode/) sur l’objet pointé. |
| T * [GetObjectNotNull](./getobjectnotnull/)() const | Obtient l’objet référencé actuellement (le cas échéant) ou lève une exception. |
| [Object](../object/) * [GetObjectOrNull](./getobjectornull/)() const | Obtient l’objet pointé (le cas échéant) ou nullptr. Identique à [get()](./get/). |
| [Object](../object/) * [GetObjectOwner](./getobjectowner/)() const | Obtient l’objet référencé. |
| [Pointee_](./pointee_/) * [GetPointer](./getpointer/)() const | Obtient l’objet pointé (le cas échéant) ou nullptr. Identique à [get()](./get/). |
| **bool** [Is](./is/)(const [System::TypeInfo](../typeinfo/)\&) const | Vérifie si l’objet pointé est d’un type spécifique ou d’un de ses sous-types. Suit la sémantique 'is' de C#. |
| **bool** [IsAliasingPtr](./isaliasingptr/)() const | Vérifie si le pointeur pointe vers un objet différent de celui possédé (créé par un constructeur d’alias). |
| **bool** [IsShared](./isshared/)() const | Vérifie si le pointeur est en mode partagé. |
| **bool** [IsWeak](./isweak/)() const | Vérifie si le pointeur est en mode faible. |
| explicit [operator bool](./operator_bool/)() const | Vérifie si le pointeur n’est pas nul. |
| **bool** [operator!](./operator_not/)() const | Vérifie si le pointeur est nul. |
| [Pointee_](./pointee_/)\& [operator*](./operator_star/)() const | Obtient une référence à l’objet pointé. Affirme que le pointeur n’est pas nul. |
| [Pointee_](./pointee_/) * [operator->](./operator_minus_greater/)() const | Permet d’accéder aux membres de l’objet référencé. |
| **bool** [operator<](./operator_less/)(Y *) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](./). |
| **bool** [operator<](./operator_less/)([SmartPtr](./)\<Y\> const\&) const | Fournit une sémantique de comparaison inférieure pour la classe [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([SmartPtr_](./smartptr_/)\&&) | Affecte-mouvement l’objet [SmartPtr](./). x devient inutilisable. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr_](./smartptr_/)\&) | Affecte-copie l’objet [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(const [SmartPtr](./)\<Q\>\&) | Affecte-copie l’objet [SmartPtr](./). Effectue les conversions de type requises. |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)([Pointee_](./pointee_/) *) | Assigne le pointeur brut à l’objet [SmartPtr](./). |
| [SmartPtr_](./smartptr_/)\& [operator=](./operator_equal/)(std::nullptr_t) | Définit la valeur du pointeur à nullptr. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Vérifie si le pointeur pointe vers nullptr. |
| [SmartPtr_](./smartptr_/) [RemoveAliasing](./removealiasing/)() const | Supprime l’alias (créé par un constructeur d’alias) du pointeur, assure qu’il gère (s’il est partagé) ou suit (s’il est faible) le même objet qu’il pointe. |
| void [reset](./reset/)([Pointee_](./pointee_/) *) | Définit l’objet pointé. |
| void [reset](./reset/)() | Fait pointer le pointeur vers nullptr. |
| void [set_Mode](./set_mode/)([SmartPtrMode](../smartptrmode/)) | Définit le mode du pointeur. Peut modifier les compteurs de références de l’objet référencé. |
| void [SetContainedTemplateWeakPtr](./setcontainedtemplateweakptr/)(**uint32_t**) const | Appelle la méthode SetTemplateWeakPtr() sur l’objet pointé (le cas échéant). |
| [SmartPtr](./smartptr/)([SmartPtrMode](../smartptrmode/)) | Crée un objet [SmartPtr](./) du mode requis. |
| [SmartPtr](./smartptr/)(std::nullptr_t, [SmartPtrMode](../smartptrmode/)) | Crée un objet [SmartPtr](./) pointeur nul du mode requis. |
| [SmartPtr](./smartptr/)([Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Crée un [SmartPtr](./) pointant vers l’objet spécifié, ou convertit un pointeur brut en [SmartPtr](./). |
| [SmartPtr](./smartptr/)(const [SmartPtr_](./smartptr_/)\&, [SmartPtrMode](../smartptrmode/)) | Construit par copie l’objet [SmartPtr](./). Les deux pointeurs pointent alors vers le même objet. |
| [SmartPtr](./smartptr/)(const [SmartPtr](./)\<Q\>\&, [SmartPtrMode](../smartptrmode/)) | Construit par copie l’objet [SmartPtr](./). Les deux pointeurs pointent alors vers le même objet. Effectue la conversion de type si autorisée. |
| [SmartPtr](./smartptr/)([SmartPtr_](./smartptr_/)\&&, [SmartPtrMode](../smartptrmode/)) | Construit par déplacement l’objet [SmartPtr](./). Effectivement, échange deux pointeurs s’ils sont tous deux du même mode. x peut devenir inutilisable après l’appel. |
| explicit [SmartPtr](./smartptr/)(const [SmartPtr](./)\<[Array](../array/)\<Y\>\>\&, [SmartPtrMode](../smartptrmode/)) | Convertit le type du tableau référencé en créant un nouveau tableau d’un type différent. Utile si en C# il existe un cast de type de tableau non supporté en C++. |
| explicit [SmartPtr](./smartptr/)(const Y\&) | Initialise un tableau vide. Utilisé pour traduire certaines constructions de code C#. |
| [SmartPtr](./smartptr/)(const [SmartPtr](./)\<P\>\&, [Pointee_](./pointee_/) *, [SmartPtrMode](../smartptrmode/)) | Construit un [SmartPtr](./) qui partage les informations de possession avec la valeur initiale de ptr, mais détient un pointeur p non lié et non géré. |
| [SmartPtr](./)\<Y\> [static_pointer_cast](./static_pointer_cast/)() const | Convertit le pointeur en un type différent en utilisant static_cast sur l’objet pointé. |
| [SmartPtr](./)\<[Object](../object/)\> [ToObjectPtr](./toobjectptr/)() const | Convertit n’importe quel type de pointeur en pointeur vers [Object](../object/). Ne nécessite pas que le type Pointee_ soit complet. |
| static const [System::TypeInfo](../typeinfo/)\& [Type](./type/)() | Raccourci pour obtenir l’objet [System::TypeInfo](../typeinfo/) du type Pointee_. |
| [~SmartPtr](./~smartptr/)() | Détruit l’objet [SmartPtr](./). Si nécessaire, décrémente le compteur de références de l’objet pointé et supprime l’objet. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [Pointee_](./pointee_/) | Type pointé. |
| [SmartPtr_](./smartptr_/) | Type de pointeur intelligent spécialisé. |
| [ArrayType](./arraytype/) | Identique à Pointee_, s’il s’agit d’une spécialisation de [System::Array](../array/), sinon void. |
| [ValueType](./valuetype/) | Type de stockage du tableau pointé. Signifiant uniquement si T est une spécialisation de [System::Array](../array/). |

## Voir aussi

* Espace de noms [System](../)
* Bibliothèque [Aspose.Slides](../../)