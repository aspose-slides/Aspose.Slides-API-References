---
title: SortedDictionary
second_title: Référence API Aspose.Slides pour C++
description: Déclaration anticipée du type de dictionnaire trié.
type: docs
weight: 521
url: /fr/system.collections.generic/sorteddictionary/
---
## SortedDictionary classe

Sorted dictionary type forward declaration.

```cpp
template<typename TKey,typename TValue>class SortedDictionary : public System::Collections::Generic::BaseDictionary<std::map<TKey, TValue, ComparerAdapter<BasePointerType<TKey>::type>, ASPOSE_MAP_ALLOCATOR_TYPE(TKey, TValue)>>
```

### Paramètres du modèle

| Parameter | Description |
| --- | --- |
| TKey | Key type. |
| TValue | Value type. |

## Méthodes

| Method | Description |
| --- | --- |
| virtual void [Add](../idictionary/add/)(const TKey\&, const TValue\&) | Ajoute une paire clé-valeur dans le conteneur. |
| virtual void [Add](../icollection/add/)(const T\&) | Ajoute un élément à la collection. |
| [iterator](../ienumerable/iterator/) [begin](../ienumerable/begin/)() | Obtient un itérateur pointant sur le premier élément (le cas échéant) de la collection. Cet itérateur ne peut pas être utilisé pour modifier l'objet référencé car [GetEnumerator()](../ienumerable/getenumerator/) renvoie un objet copie de T. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../ienumerable/begin/)() const | Obtient un itérateur pointant sur le premier élément (le cas échéant) de l'instance const-qualifiée de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../ienumerable/cbegin/)() const | Obtient un itérateur pointant sur le premier élément const-qualifié (le cas échéant) de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../ienumerable/cend/)() const | Obtient un itérateur pointant juste après le dernier élément const-qualifié (le cas échéant) de la collection. |
| virtual void [Clear](../icollection/clear/)() | Supprime tous les éléments de la collection. |
| virtual **bool** [Contains](../icollection/contains/)(const T\&) const | Vérifie si l'élément est présent dans la collection. |
| virtual **bool** [ContainsKey](../idictionary/containskey/)(const TKey\&) const | Vérifie si le conteneur contient la clé. |
| void [CopyTo](../idictionary/copyto/)([ArrayPtr](../../system/arrayptr/)\<[KeyValuePair](../keyvaluepair/)\<TKey, TValue\>\>, int) override | Copie le contenu du dictionnaire dans les éléments d'un tableau existant. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Obtient un itérateur inverse vers le dernier élément const-qualifié de la collection (premier en sens inverse). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Obtient un itérateur inverse pour un élément const-qualifié inexistant avant le début de la collection. |
| [iterator](../ienumerable/iterator/) [end](../ienumerable/end/)() | Obtient un itérateur pointant juste après le dernier élément (le cas échéant) de la collection. Cet itérateur ne peut pas être utilisé pour modifier l'objet référencé car [GetEnumerator()](../ienumerable/getenumerator/) renvoie un objet copie de T. |
| [const_iterator](../ienumerable/const_iterator/) [end](../ienumerable/end/)() const | Obtient un itérateur pointant juste après le dernier élément (le cas échéant) de l'instance const-qualifiée de la collection. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison flottante de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, NaN n’est égal à aucune valeur, y compris NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<TKey\>\> [get_Comparer](./get_comparer/)() const | Obtient le IComparer<TKey> utilisé pour ordonner les éléments du SortedDictionary<TKey,TValue>. |
| virtual int [get_Count](../icollection/get_count/)() const | Obtient le nombre d'éléments dans la collection. |
| **bool** [get_IsFixedSize](../idictionary/get_isfixedsize/)() const | Vérifie si la taille de la collection est fixe. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Vérifie si la collection est en lecture seule. |
| **bool** [get_IsSynchronized](../idictionary/get_issynchronized/)() const | Vérifie si le conteneur est sûr pour les threads. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TKey\>\> [get_Keys](../idictionary/get_keys/)() const | Accède à la collection de clés. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtient l'objet avec lequel la collection est synchronisée. |
| virtual [SharedPtr](../../system/sharedptr/)\<[ICollection](../icollection/)\<TValue\>\> [get_Values](../idictionary/get_values/)() const | Accède à la collection de valeurs. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| static [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\> [GetDefaultKeyComparer](./getdefaultkeycomparer/)() | Fonction d'accès au singleton. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Obtient l'énumérateur pour itérer à travers le dictionnaire actuel. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../../system/object/gethashcode/). Permet le hachage d'objets personnalisés. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&) const | Retourne la valeur si trouvée ; sinon **Value()**. |
| virtual TValue [GetValueOrDefault](../idictionary/getvalueordefault/)(const TKey\&, const TValue\&) const | Retourne la valeur si trouvée ; sinon **defaultValue**. |
| virtual TValue [GetValueOrNull](../idictionary/getvalueornull/)(const TKey\&) const | Retourne la valeur si trouvée ; sinon **null**, ce qui n’a de sens que pour les types de référence. |
|  [ICollection](../icollection/icollection/)() | Constructeur par défaut. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Constructeur de copie. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Constructeur de déplacement. |
| virtual TValue [idx_get](../idictionary/idx_get/)(const TKey\&) const | Fonction d'accès (getter). |
| virtual void [idx_set](../idictionary/idx_set/)(const TKey\&, TValue) | Fonction de mutateur (setter). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur C# `is`. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applique une fonction accumulateur sur une séquence. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Détermine si tous les éléments d'une séquence satisfont une condition. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Détermine si une séquence contient des éléments. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Détermine si un élément d'une séquence existe ou satisfait une condition. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Convertit les éléments au type spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatène deux séquences. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Détermine si une séquence contient une valeur spécifiée. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Retourne le nombre d'éléments dans la séquence (calculé par comptage direct). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourne le nombre d'éléments dans la séquence qui satisfont la condition spécifiée. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Retourne l'élément à l'index spécifié dans une séquence. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Retourne l'élément à l'index spécifié dans une séquence. |
| T [LINQ_First](../ienumerable/linq_first/)() | Retourne le premier élément d'une séquence. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Retourne le premier élément d'une séquence qui satisfait la condition spécifiée. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Retourne le premier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Retourne le premier élément de la séquence qui satisfait une condition ou une valeur par défaut si aucun élément n'est trouvé. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Regroupe les éléments d'une séquence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Regroupe les éléments d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Retourne le dernier élément d'une séquence. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Retourne le dernier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque élément d'une séquence générique et renvoie la valeur maximale obtenue. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque élément d'une séquence générique et renvoie la valeur minimale obtenue. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Retourne un nombre spécifié d'éléments contigus depuis le début d'une séquence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Crée un tableau à partir d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Crée une List<T> à partir d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtre une séquence selon le prédicat spécifié. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, initialise simplement un nouvel objet et permet la construction de copies de sous-classes. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Opérateur d'affectation de déplacement. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Opérateur d'affectation de déplacement. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, initialise simplement un nouvel objet et permet la construction de copies de sous-classes. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Obtient un itérateur inverse vers le dernier élément de la collection (premier en sens inverse). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Obtient un itérateur inverse vers le dernier élément de la collection const-qualifiée (premier en sens inverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas des chaînes. |
| virtual **bool** [Remove](../idictionary/remove/)(const TKey\&) | Supprime la clé du conteneur. |
| virtual **bool** [Remove](../icollection/remove/)(const T\&) | Supprime l'élément de la collection. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre indiqué. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Obtient un itérateur inverse pour un élément inexistant avant le début de la collection. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Obtient un itérateur inverse pour un élément inexistant avant le début de la collection const-qualifiée. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le nième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et retourne le compteur de références partagées. Ne doit pas être appelé directement ; utilisez les pointeurs intelligents ou ThisProtector. |
|  [SortedDictionary](./sorteddictionary/)() | Construit un dictionnaire vide. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | Construit un dictionnaire vide. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&) | Constructeur de copie. |
|  [SortedDictionary](./sorteddictionary/)(const [SharedPtr](../../system/sharedptr/)\<[IDictionary](../idictionary/)\<TKey, TValue\>\>\&, const [SharedPtr](../../system/sharedptr/)\<[IComparer](../icomparer/)\<typename BasePointerType\<TKey\>::type\>\>\&) | Constructeur de copie. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../../system/object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| virtual **bool** [TryGetValue](../idictionary/trygetvalue/)(const TKey\&, TValue\&) const | Recherche la valeur et la récupère si trouvée. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginConstIterator](../ienumerable/virtualizebeginconstiterator/)() const | Obtient l'implémentation de l'itérateur const begin pour le conteneur actuel. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeBeginIterator](../ienumerable/virtualizebeginiterator/)() | Obtient l'implémentation de l'itérateur begin pour le conteneur actuel. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndConstIterator](../ienumerable/virtualizeendconstiterator/)() const | Obtient l'implémentation de l'itérateur const end pour le conteneur actuel. |
| virtual [virtualized_iterator](../ienumerable/virtualized_iterator/) * [virtualizeEndIterator](../ienumerable/virtualizeenditerator/)() | Obtient l'implémentation de l'itérateur end pour le conteneur actuel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez les pointeurs intelligents ou ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [KeyCollection](./keycollection/) | Key collection type. |
| [ValueCollection](./valuecollection/) | Value collection type. |
| [map_t](./map_t/) | Underlying data type. |
| [this_t](./this_t/) | Self type. |
| [Ptr](./ptr/) | Pointer type. |
| [KVPair](./kvpair/) | Key-value pair type. |
| [IEnumerablePtr](./ienumerableptr/) | Collection of same elements. |
| [IEnumeratorPtr](./ienumeratorptr/) | **Enumerator** type. |
| [iterator](./iterator/) | Iterator type. |
| [const_iterator](./const_iterator/) | Const iterator type. |
| [reverse_iterator](./reverse_iterator/) | Reverse iterator type. |
| [const_reverse_iterator](./const_reverse_iterator/) | Const reverse iterator type. |

## Remarques

Sorted dictionary class wrapping STL map. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

## Voir aussi

* Classe [BaseDictionary](../basedictionary/)
* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)