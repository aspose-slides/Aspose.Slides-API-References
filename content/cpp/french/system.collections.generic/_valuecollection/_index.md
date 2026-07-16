---
title: _ValueCollection
second_title: Aspose.Slides pour C++ – Référence de l'API
description: "Collection des valeurs du Dictionary. Référence une collection, ne copie rien. Les objets de cette classe doivent uniquement être alloués en utilisant la fonction System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des fautes d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en argument."
type: docs
weight: 27
url: /fr/system.collections.generic/_valuecollection/
---
## _ValueCollection classe

Collection des valeurs de [Dictionary](../dictionary/). Référence une collection, ne copie rien. Les objets de cette classe ne doivent être alloués qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des échecs d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en argument.

```cpp
template<typename Dict>class _ValueCollection : public System::Collections::Generic::BaseKVCollection<Dict, Dict::map_t::mapped_type>
```

## Méthodes

| Method | Description |
| --- | --- |
|  [_ValueCollection](./_valuecollection/)(const typename Dict::Ptr\&) | Initialise la collection en référant le dictionnaire spécifié. |
| void [Add](../ikvcollection/add/)(const T\&) override | Ajoute un élément au conteneur. |
|  [BaseKVCollection](../basekvcollection/basekvcollection/)(const typename Dict::Ptr\&) | Crée une collection. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Obtient un itérateur pointant vers le premier élément (s'il existe) de la collection. Cet itérateur ne peut pas être utilisé pour modifier un objet référencé car [GetEnumerator()](../ienumerable/getenumerator/) renvoie une copie de l'objet T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Obtient un itérateur pointant vers le premier élément (s'il existe) de l'instance de la collection qualifiée const. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Obtient un itérateur pointant vers le premier élément qualifié const (s'il existe) de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Obtient un itérateur pointant juste après le dernier élément qualifié const (s'il existe) de la collection. |
| void [Clear](../ikvcollection/clear/)() override | Supprime tous les éléments du conteneur. |
| **bool** [Contains](./contains/)(const [TValue](./tvalue/)\&) const override | Vérifie si l'élément est présent dans le conteneur. |
| void [CopyTo](../basekvcollection/copyto/)([ArrayPtr](../../system/arrayptr/)\<KV\>, int) override | Copie les données vers les éléments existants du tableau. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Obtient un itérateur pointant juste après le dernier élément (s'il existe) de la collection. Cet itérateur ne peut pas être utilisé pour modifier un objet référencé car [GetEnumerator()](../ienumerable/getenumerator/) renvoie une copie de l'objet T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Obtient un itérateur pointant juste après le dernier élément (s'il existe) de l'instance qualifiée const de la collection. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants à la C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres flottants à la C# où deux NaN sont considérés égaux bien que, selon IEC 60559:1989, NaN ne soit égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À des fins internes uniquement. |
| int [get_Count](../basekvcollection/get_count/)() const override | Obtient le nombre d'éléments. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Vérifie si la collection est de taille fixe. |
| **bool** [get_IsReadOnly](../ikvcollection/get_isreadonly/)() const override | Vérifie si le conteneur est en lecture seule. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtient l'objet par lequel la collection est synchronisée. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerator](../ienumerator/)\<[TValue](./tvalue/)\>\> [GetEnumerator](./getenumerator/)() override | Obtient l'énumérateur parcourant les valeurs. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICollection](../icollection/icollection/)() | Constructeur par défaut. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Constructeur de copie. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Constructeur de déplacement. |
| [TValue](./tvalue/) [idx_get](./idx_get/)(int) const override | Implémente la méthode [IList](../ilist/). Non pris en charge. |
| void [idx_set](../ikvcollection/idx_set/)(int, T) override | Fonction définisseur. |
| int [IndexOf](../ikvcollection/indexof/)(const T\&) const override | Obtient l'index de l'élément dans le conteneur. |
| void [Insert](../ikvcollection/insert/)(int, const T\&) override | Insère l'élément à la position spécifiée. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# 'is'. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applique une fonction d'accumulateur sur une séquence. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Détermine si tous les éléments d'une séquence satisfont une condition. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Détermine si une séquence contient des éléments. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Détermine si un élément d'une séquence existe ou satisfait une condition. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Convertit les éléments au type spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatène deux séquences. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Détermine si une séquence contient une valeur spécifiée. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Renvoie le nombre d'éléments dans la séquence (calculé par comptage direct). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Renvoie le nombre d'éléments de la séquence qui satisfont la condition spécifiée. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Renvoie l'élément à l'index spécifié dans une séquence. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Renvoie l'élément à l'index spécifié dans une séquence. |
| T [LINQ_First](../ienumerable/linq_first/)() | Renvoie le premier élément d'une séquence. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Renvoie le premier élément d'une séquence qui satisfait la condition spécifiée. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Renvoie le premier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Renvoie le premier élément de la séquence qui satisfait une condition ou une valeur par défaut si aucun élément n'est trouvé. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Regroupe les éléments d'une séquence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Regroupe les éléments d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Renvoie le dernier élément d'une séquence. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Renvoie le dernier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Applique une fonction de transformation à chaque élément d'une séquence générique et renvoie la valeur maximale résultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Applique une fonction de transformation à chaque élément d'une séquence générique et renvoie la valeur minimale résultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtre les éléments de la séquence selon le type spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Trie les éléments d'une séquence par ordre croissant selon les valeurs de clé sélectionnées par keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Trie les éléments d'une séquence par ordre décroissant selon les valeurs de clé sélectionnées par keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverse l'ordre des éléments d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforme les éléments d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforme chaque élément d'une séquence en une nouvelle forme en incorporant l'index de l'élément. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projette chaque élément d'une séquence et combine les séquences résultantes en une seule séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Renvoie un nombre spécifié d'éléments contigus depuis le début d'une séquence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crée un tableau à partir d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crée une List<T> à partir d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtre une séquence selon le prédicat spécifié. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Opérateur d'affectation de déplacement. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Opérateur d'affectation de déplacement. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, il initialise simplement le nouvel objet et permet la construction par copie des sous-classes. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| **bool** [Remove](../ikvcollection/remove/)(const T\&) override | Supprime l'élément du conteneur. |
| void [RemoveAt](../ikvcollection/removeat/)(int) override | Supprime l'élément à la position spécifiée. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [SetTemplateWeakPtr](../basekvcollection/settemplateweakptr/)(**uint32_t**) override | Autorise la compilation, mais ne fait rien car cette structure ne possède pas de données. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente le construct typeof([System.Object](../../system/object/)) de C#. |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtient l'implémentation de l'itérateur const begin pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtient l'implémentation de l'itérateur begin pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtient l'implémentation de l'itérateur const end pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<[TValue](./tvalue/)\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtient l'implémentation de l'itérateur end pour le conteneur actuel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt des pointeurs intelligents ou ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [TValue](./tvalue/) | Type de valeur. |

## Voir aussi

* Class [BaseKVCollection](../basekvcollection/)
* Namespace [System::Collections::Generic](../)
* Library [Aspose.Slides](../../)