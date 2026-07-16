---
title: ListExt
second_title: Référence de l'API Aspose.Slides pour C++
description: classe générique List qui implémente l'interface IListWrapper
type: docs
weight: 443
url: /fr/system.collections.generic/listext/
---
## ListExt classe

classe générique [List](../list/) qui implémente l'interface [IListWrapper](../../system.collections/ilistwrapper/)

```cpp
template<typename T>class ListExt : public System::Collections::Generic::List<T>,
                                    public System::Collections::IListWrapper
```

## Méthodes

| Méthode | Description |
| --- | --- |
| void [_add_range](../list/_add_range/)(std::initializer_list\<T\>) | Spécifique à C++. |
| void [Add](../list/add/)(const T\&) override | Ajoute un élément à la fin de la liste. |
| void [AddInitializer](../list/addinitializer/)(int, const T *) | Ajoute des éléments à la liste ; utilisé lors de la traduction des initialiseurs. |
| void [AddRange](../list/addrange/)([IEnumerablePtr](../list/ienumerableptr/)) | Ajoute tous les éléments de la collection (ou d'elle-même) à la fin de la liste actuelle. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](../list/asreadonly/)() | Obtient une référence en lecture-seule à cette collection. |
| [iterator](../ienumerable/iterator/) [begin](../list/begin/)() | Obtient un itérateur vers le premier élément de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [begin](../list/begin/)() const | Obtient un itérateur vers le premier élément de la collection qualifiée const. |
| int [BinarySearch](../list/binarysearch/)(const T\&) const | Recherche un élément dans une liste triée. |
| int [BinarySearch](../list/binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Recherche un élément dans une liste triée. |
| int [BinarySearch](../list/binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Recherche un élément dans une liste triée. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](../list/cbegin/)() const | Obtient un itérateur vers le premier élément qualifié const de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [cend](../list/cend/)() const | Obtient un itérateur pour un élément const non-existant situé après la fin de la collection. |
| void [Clear](../list/clear/)() override | Supprime tous les éléments. |
| **bool** [Contains](../list/contains/)(const T\&) const override | Vérifie si l'élément est présent dans la liste. |
| [SharedPtr](../../system/sharedptr/)\<[List](../list/)\<OutputType\>\> [ConvertAll](../list/convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Crée une liste d'éléments convertis en un type différent. |
| void [CopyTo](../list/copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copie les éléments de la liste dans des éléments de tableau existants. |
| void [CopyTo](../list/copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copie tous les éléments dans des éléments de tableau existants. |
| void [CopyTo](../list/copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copie les éléments à partir de l'index spécifié dans des éléments de tableau existants. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crbegin](../list/crbegin/)() const | Obtient un itérateur inverse vers le dernier élément qualifié const de la collection (premier en sens inverse). |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\> [CreateIListWrapper](./createilistwrapper/)() override | implémentation de l'interface [IListWrapper](../../system.collections/ilistwrapper/). |
| std::enable_if\<[System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) assistant d'implémentation pour les types référence. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[System::IsBoxable](../../system/isboxable/)\<T1\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) assistant d'implémentation pour les types valeur. |
| std::enable_if<\![System::IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![System::IsBoxable](../../system/isboxable/)\<T\>::value, [System::SharedPtr](../../system/sharedptr/)\<[System::Collections::IList](../../system.collections/ilist/)\>\>::type [CreateIListWrapperImpl](./createilistwrapperimpl/)() | [IListWrapper](../../system.collections/ilistwrapper/) assistant d'implémentation pour d'autres types. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [crend](../list/crend/)() const | Obtient un itérateur inverse pour un élément const non-existant situé avant le début de la collection. |
| [vector_t](../list/vector_t/)\& [data](../list/data/)() | Fonction d'accès à la structure de données sous-jacente. |
| const [vector_t](../list/vector_t/)\& [data](../list/data/)() const | Fonction d'accès à la structure de données sous-jacente. |
| [iterator](../ienumerable/iterator/) [end](../list/end/)() | Obtient un itérateur pour un élément non-existant situé après la fin de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [end](../list/end/)() const | Obtient un itérateur pour un élément non-existant situé après la fin de la collection qualifiée const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la sémantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison de nombres flottants de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, un NaN n'est égal à aucune valeur, y compris un NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison de nombres flottants de style C# où deux NaN sont considérés égaux même si, selon IEC 60559:1989, un NaN n'est égal à aucune valeur, y compris un NaN. |
| **bool** [Exists](../list/exists/)([System::Predicate](../../system/predicate/)\<T\>) | Vérifie si un élément répondant à un prédicat spécifique existe dans la liste. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| T [Find](../list/find/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche un élément répondant à un prédicat spécifique. |
| [ListPtr](../listptr/)\<T\> [FindAll](../list/findall/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche des éléments répondant à un prédicat spécifique. |
| int [FindIndex](../list/findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche un élément répondant à un prédicat spécifique. |
| int [FindIndex](../list/findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Recherche un élément répondant à un prédicat spécifique. |
| int [FindIndex](../list/findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Recherche un élément répondant à un prédicat spécifique. |
| T [FindLast](../list/findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche le dernier élément répondant à un prédicat spécifique. |
| void [ForEach](../list/foreach/)([System::Action](../../system/action/)\<T\>) | Applique une action à tous les éléments de la liste. |
| int [get_Capacity](../list/get_capacity/)() const | Obtient la capacité actuelle de la liste. |
| int [get_Count](../list/get_count/)() const override | Obtient le nombre d'éléments dans la liste actuelle. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Vérifie si la collection a une taille fixe. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Vérifie si la collection est en lecture seule. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtient l'objet à travers lequel la collection est synchronisée. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [IEnumeratorPtr](../list/ienumeratorptr/) [GetEnumerator](../list/getenumerator/)() override | Obtient un énumérateur pour parcourir les éléments de la liste. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la méthode [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permet le hachage d'objets personnalisés. |
| **ThisPtr** [GetRange](../list/getrange/)(int, int) | Crée une tranche de la liste. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel [System.Object.GetType()](../../system/object/gettype/) de C#. |
|  [ICollection](../icollection/icollection/)() | Constructeur par défaut. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Constructeur de copie. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Constructeur de déplacement. |
| T [idx_get](../list/idx_get/)(int) const override | Obtient l'élément à la position spécifiée. |
| void [idx_set](../list/idx_set/)(int, T) override | Définit l'élément à la position spécifiée. |
| int [IndexOf](../list/indexof/)(const T\&) const override | Obtient le premier indice de l'élément spécifié. |
| int [IndexOf](../list/indexof/)(const T\&, int) const | Recherche l'élément spécifié dans la liste. |
| void [Insert](../list/insert/)(int, const T\&) override | Insère l'élément à la position spécifiée. |
| void [InsertRange](../list/insertrange/)(int, [IEnumerablePtr](../list/ienumerableptr/)) | Insère une plage de données à la position spécifiée. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par targetType. Analogue de l'opérateur 'is' de C#. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&) const | Recherche l'objet spécifié et renvoie l'indice basé sur zéro de la dernière occurrence dans toute la liste. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**) const | Recherche l'objet spécifié et renvoie l'indice basé sur zéro de la dernière occurrence dans la plage d'éléments du [List](../list/) qui s'étend du premier élément jusqu'à l'indice spécifié. |
| **int32_t** [LastIndexOf](../list/lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Recherche l'objet spécifié et renvoie l'indice basé sur zéro de la dernière occurrence dans la plage d'éléments du [List](../list/) qui contient le nombre d'éléments spécifié et se termine à l'indice donné. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applique une fonction accumulateur sur une séquence. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Détermine si tous les éléments d'une séquence satisfont une condition. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Détermine si une séquence contient des éléments. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Détermine si un élément d'une séquence existe ou satisfait une condition. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Convertit les éléments au type spécifié. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatène deux séquences. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Détermine si une séquence contient une valeur spécifiée. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Renvoie le nombre d'éléments dans la séquence (calculé par comptage direct). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Renvoie le nombre d'éléments dans la séquence qui satisfont la condition spécifiée. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Renvoie l'élément à l'indice spécifié dans une séquence. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Renvoie l'élément à l'indice spécifié dans une séquence. |
| T [LINQ_First](../ienumerable/linq_first/)() | Renvoie le premier élément d'une séquence. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Renvoie le premier élément d'une séquence qui satisfait la condition spécifiée. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Renvoie le premier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Renvoie le premier élément de la séquence qui satisfait une condition ou une valeur par défaut si aucun élément ne correspond. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Regroupe les éléments d'une séquence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Regroupe les éléments d'une séquence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Renvoie le dernier élément d'une séquence. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Renvoie le dernier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque élément d'une séquence générique et renvoie la valeur maximale résultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque élément d'une séquence générique et renvoie la valeur minimale résultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtre les éléments de la séquence en fonction du type spécifié. |
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
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtre une séquence en fonction du prédicat spécifié. |
|  [List](../list/list/)() | Crée une liste vide. |
|  [List](../list/list/)(int) | Crée une liste avec une capacité pré-définie. |
|  [List](../list/list/)([IEnumerablePtr](../list/ienumerableptr/)) | Constructeur de copie. |
| void [Lock](../../system/object/lock/)() | Implémente le verrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la méthode [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permet le clonage de types personnalisés. |
|  [Object](../../system/object/object/)() | Crée un objet. Initialise toutes les structures de données internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Opérateur d'affectation. Ne copie rien, il initialise simplement un nouvel objet et permet la construction par copie des sous-classes. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Opérateur d'affectation par déplacement. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Opérateur d'affectation par déplacement. |
| vector_t::reference [operator[]](../list/operator[]/)(int) | Fonction d'accès. |
| vector_t::const_reference [operator[]](../list/operator[]/)(int) const | Fonction d'accès. |
| [reverse_iterator](../list/reverse_iterator/) [rbegin](../list/rbegin/)() | Obtient un itérateur inverse vers le dernier élément de la collection (premier en sens inverse). |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rbegin](../list/rbegin/)() const | Obtient un itérateur inverse vers le dernier élément de la collection qualifiée const (premier en sens inverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Spécialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaînes. |
| **bool** [Remove](../list/remove/)(const T\&) override | Supprime la première occurrence d'un élément spécifique de la liste. |
| int [RemoveAll](../list/removeall/)([Predicate](../../system/predicate/)\<T\>) | Supprime tous les éléments correspondant au prédicat spécifié. |
| void [RemoveAt](../list/removeat/)(int) override | Supprime l'élément à la position spécifiée. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de références partagées de la valeur spécifiée. |
| void [RemoveRange](../list/removerange/)(int, int) | Supprime une tranche de la liste. |
| [reverse_iterator](../list/reverse_iterator/) [rend](../list/rend/)() | Obtient un itérateur inverse pour un élément non-existant situé avant le début de la collection. |
| [const_reverse_iterator](../list/const_reverse_iterator/) [rend](../list/rend/)() const | Obtient un itérateur inverse pour un élément non-existant situé avant le début de la collection qualifiée const. |
| void [Reverse](../list/reverse/)() | Inverse l'ordre des éléments de la liste entière. |
| void [Reverse](../list/reverse/)(int, int) | Inverse l'ordre des éléments de la tranche de liste. |
| void [set_Capacity](../list/set_capacity/)(int) | Définit la capacité de la liste. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Définit le n-ième argument de modèle comme pointeur faible (plutôt que partagé). Permet de passer les pointeurs des conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [Sort](../list/sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Trie les éléments de la liste. |
| void [Sort](../list/sort/)() | Trie les éléments de la liste en utilisant le comparateur par défaut. |
| void [Sort](../list/sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Trie les éléments de la tranche de liste. |
| void [Sort](../list/sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Trie les éléments de la liste. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](../list/toarray/)() const | Convertit la liste en tableau. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la méthode [Object.ToString()](../../system/object/tostring/) de C#. Permet de convertir des objets personnalisés en chaîne. |
| void [TrimExcess](../list/trimexcess/)() | Ajuste la capacité de la liste à sa taille. |
| **bool** [TrueForAll](../list/trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Détermine si chaque élément de la collection satisfait les conditions définies par le prédicat spécifié. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implémente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implémente le déverrouillage de l'instruction C# lock(). Appelez directement ou utilisez l'objet sentinelle [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](../list/virtualizebeginconstiterator/)() const override | Obtient l'implémentation de l'itérateur const begin pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](../list/virtualizebeginiterator/)() override | Obtient l'implémentation de l'itérateur begin pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](../list/virtualizeendconstiterator/)() const override | Obtient l'implémentation de l'itérateur const end pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](../list/virtualizeenditerator/)() override | Obtient l'implémentation de l'itérateur end pour le conteneur actuel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Alias de type

| Typedef | Description |
| --- | --- |
| [ThisType](./thistype/) |  |
| [ListType](./listtype/) |  |
| [BaseTypes](./basetypes/) |  |
| [ValueType](./valuetype/) |  |
| [BaseType](./basetype/) |  |

## Voir aussi

* Classe [List](../list/)
* Classe [IListWrapper](../../system.collections/ilistwrapper/)
* Espace de noms [System::Collections::Generic](../)
* Bibliothèque [Aspose.Slides](../../)