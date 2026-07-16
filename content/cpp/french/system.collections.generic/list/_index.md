---
title: List
second_title: Référence API Aspose.Slides pour C++
description: Déclaration anticipée de List.
type: docs
weight: 430
url: /fr/system.collections.generic/list/
---
## Classe List


[List](./) déclaration anticipée.

```cpp
template<typename T>class List : public virtual System::Object,
                                 public System::Collections::Generic::IList<T>
```


### Paramètres du modèle

| Paramètre | Description |
| --- | --- |
| T | Type d'élément. |
## Méthodes

| Méthode | Description |
| --- | --- |
| void [_add_range](./_add_range/)(std::initializer_list\<T\>) | Spécifique à C++. |
| void [Add](./add/)(const T\&) override | Ajoute un element a la fin de la liste. |
| void [AddInitializer](./addinitializer/)(int, const T *) | Ajoute des elements a la liste; utilise lors de la traduction des initialiseurs. |
| void [AddRange](./addrange/)([IEnumerablePtr](./ienumerableptr/)) | Ajoute tous les elements de la collection (ou elle-meme) a la fin de la liste actuelle. |
| [SharedPtr](../../system/sharedptr/)\<[System::Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)() | Obtient une reference en lecture-seule a cette collection. |
| [iterator](../ienumerable/iterator/) [begin](./begin/)() | Obtient un iterateur vers le premier element de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [begin](./begin/)() const | Obtient un iterateur vers le premier element de la collection qualifiee const. |
| int [BinarySearch](./binarysearch/)(const T\&) const | Recherche un element dans une liste triee. |
| int [BinarySearch](./binarysearch/)(const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Recherche un element dans une liste triee. |
| int [BinarySearch](./binarysearch/)(int, int, const T\&, const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) const | Recherche un element dans une liste triee. |
| [const_iterator](../ienumerable/const_iterator/) [cbegin](./cbegin/)() const | Obtient un iterateur vers le premier element qualifie const de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [cend](./cend/)() const | Obtient un iterateur pour un element const-qualifie inexistant apres la fin de la collection. |
| void [Clear](./clear/)() override | Supprime tous les elements. |
| **bool** [Contains](./contains/)(const T\&) const override | Verifie si l'element est present dans la liste. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<OutputType\>\> [ConvertAll](./convertall/)([Converter](../../system/converter/)\<T, OutputType\>) | Cree une liste d'elements convertis en un type different. |
| void [CopyTo](./copyto/)([System::ArrayPtr](../../system/arrayptr/)\<T\>, int) override | Copie les elements de la liste dans des elements de tableau existants. |
| void [CopyTo](./copyto/)(const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&) | Copie tous les elements dans des elements de tableau existants. |
| void [CopyTo](./copyto/)(int, const [System::ArrayPtr](../../system/arrayptr/)\<T\>\&, int, int) | Copie les elements a partir de l'index specifie dans des elements de tableau existants. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Obtient un iterateur inverse vers le dernier element qualifie const de la collection (premier en sens inverse). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Obtient un iterateur inverse pour un element const-qualifie inexistant avant le debut de la collection. |
| [vector_t](./vector_t/)\& [data](./data/)() | Fonction d'acces a la structure de donnees sous-jacente. |
| const [vector_t](./vector_t/)\& [data](./data/)() const | Fonction d'acces a la structure de donnees sous-jacente. |
| [iterator](../ienumerable/iterator/) [end](./end/)() | Obtient un iterateur pour un element inexistant apres la fin de la collection. |
| [const_iterator](../ienumerable/const_iterator/) [end](./end/)() const | Obtient un iterateur pour un element inexistant apres la fin de la collection qualifiee const. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Compare les objets en utilisant la semantique [Object.Equals](../../system/object/equals/) de C#. |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type reference dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Emule la comparaison de nombres a virgule flottante de style C# où deux NaN sont considers egaux bien que selon IEC 60559:1989 le NaN ne soit egal a aucune valeur, y compris NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Emule la comparaison de nombres a virgule flottante de style C# où deux NaN sont considers egaux bien que selon IEC 60559:1989 le NaN ne soit egal a aucune valeur, y compris NaN. |
| **bool** [Exists](./exists/)([System::Predicate](../../system/predicate/)\<T\>) | Verifie si un element repondant a un predicat specifique existe dans la liste. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | A usage interne uniquement. |
| T [Find](./find/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche un element repondant a un predicat specifique. |
| [ListPtr](../listptr/)\<T\> [FindAll](./findall/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche des elements repondant a un predicat specifique. |
| int [FindIndex](./findindex/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche un element repondant a un predicat specifique. |
| int [FindIndex](./findindex/)(int, [System::Predicate](../../system/predicate/)\<T\>) | Recherche un element repondant a un predicat specifique. |
| int [FindIndex](./findindex/)(int, int, [System::Predicate](../../system/predicate/)\<T\>) | Recherche un element repondant a un predicat specifique. |
| T [FindLast](./findlast/)([System::Predicate](../../system/predicate/)\<T\>) | Recherche le dernier element repondant a un predicat specifique. |
| void [ForEach](./foreach/)([System::Action](../../system/action/)\<T\>) | Applique une action a tous les elements de la liste. |
| int [get_Capacity](./get_capacity/)() const | Obtient la capacite actuelle de la liste. |
| int [get_Count](./get_count/)() const override | Obtient le nombre d'elements dans la liste actuelle. |
| **bool** [get_IsFixedSize](../ilist/get_isfixedsize/)() | Verifie si la collection a une taille fixe. |
| virtual **bool** [get_IsReadOnly](../icollection/get_isreadonly/)() const | Verifie si la collection est en lecture seule. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [get_SyncRoot](../icollection/get_syncroot/)() const | Obtient l'objet par lequel la collection est synchronisee. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Obtient la structure de donnees du compteur de references associee a l'objet. |
| [IEnumeratorPtr](./ienumeratorptr/) [GetEnumerator](./getenumerator/)() override | Obtient un enumerateur pour parcourir les elements de la liste. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Analogue de la methode [Object.GetHashCode()](../../system/object/gethashcode/) de C#. Permet le hachage d'objets personnalises. |
| **ThisPtr** [GetRange](./getrange/)(int, int) | Cree une tranche de la liste. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Obtient le type reel de l'objet. Analogue de l'appel [System.Object.GetType()](../../system/object/gettype/) de C#. |
|  [ICollection](../icollection/icollection/)() | Constructeur par défaut. |
|  [ICollection](../icollection/icollection/)(const [ICollection](../icollection/)\&) | Constructeur de copie. |
|  [ICollection](../icollection/icollection/)([ICollection](../icollection/)\&&) | Constructeur de deplacement. |
| T [idx_get](./idx_get/)(int) const override | Obtient l'element a une position specifique. |
| void [idx_set](./idx_set/)(int, T) override | Definit l'element a une position specifique. |
| int [IndexOf](./indexof/)(const T\&) const override | Obtient le premier indice de l'element specifie. |
| int [IndexOf](./indexof/)(const T\&, int) const | Recherche un element specifique dans la liste. |
| void [Insert](./insert/)(int, const T\&) override | Insere l'element a la position specifiee. |
| void [InsertRange](./insertrange/)(int, [IEnumerablePtr](./ienumerableptr/)) | Insere une plage de donnees a une position specifique. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Verifie si l'objet represente une instance du type décrit par targetType. Analogue de l'operateur 'is' de C#. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&) const | Recherche l'objet specifie et renvoie l'indice de base zero de la derniere occurrence dans toute la liste. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**) const | Recherche l'objet specifie et renvoie l'indice de base zero de la derniere occurrence dans la plage d'elements du [List](./) qui s'etend du premier element a l'indice specifie. |
| **int32_t** [LastIndexOf](./lastindexof/)(const T\&, **int32_t**, **int32_t**) const | Recherche l'objet specifie et renvoie l'indice de base zero de la derniere occurrence dans la plage d'elements du [List](./) qui contient le nombre specifie d'elements et se termine a l'indice specifie. |
| T [LINQ_Aggregate](../ienumerable/linq_aggregate/)(const [Func](../../system/func/)\<T, T, T\>\&) | Applique une fonction d'accumulateur sur une sequence. |
| **bool** [LINQ_All](../ienumerable/linq_all/)(std::function\<**bool**(T)>) | Determine si tous les elements d'une sequence satisfont une condition. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)() | Determine si une sequence contient des elements. |
| **bool** [LINQ_Any](../ienumerable/linq_any/)(std::function\<**bool**(T)>) | Determine si n'importe quel element d'une sequence existe ou satisfait une condition. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Cast](../ienumerable/linq_cast/)() | Convertit les elements au type specifie. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Cast](../ienumerable/linq_cast/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Concat](../ienumerable/linq_concat/)([SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\>) | Concatene deux sequences. |
| **bool** [LINQ_Contains](../ienumerable/linq_contains/)(T) | Determine si une sequence contient une valeur specifiee. |
| int [LINQ_Count](../ienumerable/linq_count/)() | Renvoie le nombre d'elements dans la sequence (calcule par comptage direct). |
| int [LINQ_Count](../ienumerable/linq_count/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Renvoie le nombre d'elements de la sequence qui satisfont la condition specifiee. |
| T [LINQ_ElementAt](../ienumerable/linq_elementat/)(int) | Renvoie l'element a un indice specifie dans une sequence. |
| T [LINQ_ElementAtOrDefault](../ienumerable/linq_elementatordefault/)(int) | Renvoie l'element a un indice specifie dans une sequence. |
| T [LINQ_First](../ienumerable/linq_first/)() | Renvoie le premier element d'une sequence. |
| T [LINQ_First](../ienumerable/linq_first/)(const [Func](../../system/func/)\<T, **bool**\>\&) | Renvoie le premier element d'une sequence qui satisfait la condition specifiee. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)() | Renvoie le premier element d'une sequence, ou une valeur par defaut si la sequence est vide. |
| T [LINQ_FirstOrDefault](../ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Renvoie le premier element de la sequence qui satisfait une condition ou une valeur par defaut si aucun element n'est trouve. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>) | Regroupe les elements d'une sequence. |
| [System::SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[System::SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<T, Key\>, [System::Func](../../system/func/)\<T, Element\>) | Regroupe les elements d'une sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<[SharedPtr](../../system/sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../ienumerable/linq_groupby/)([System::Func](../../system/func/)\<Source, Key\>, [System::Func](../../system/func/)\<Source, Element\>) |  |
| T [LINQ_Last](../ienumerable/linq_last/)() | Renvoie le dernier element d'une sequence. |
| T [LINQ_LastOrDefault](../ienumerable/linq_lastordefault/)() | Renvoie le dernier element d'une sequence, ou une valeur par defaut si la sequence est vide. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque element d'une sequence generique et renvoie la valeur maximale resultante. |
| ResultType [LINQ_Max](../ienumerable/linq_max/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Invoque une fonction de transformation sur chaque element d'une sequence generique et renvoie la valeur minimale resultante. |
| ResultType [LINQ_Min](../ienumerable/linq_min/)(const [Func](../../system/func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() | Filtre les elements de la sequence selon le type specifie. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_OfType](../ienumerable/linq_oftype/)() |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<T, Key\>\&) | Trie les elements d'une sequence par ordre croissant selon les valeurs de cle selectionnees par keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../ienumerable/linq_orderby/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<T, Key\>\&) | Trie les elements d'une sequence par ordre decroissant selon les valeurs de cle selectionnees par keySelector. |
| [SharedPtr](../../system/sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../ienumerable/linq_orderbydescending/)(const [Func](../../system/func/)\<Source, Key\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Reverse](../ienumerable/linq_reverse/)() | Inverse l'ordre des elements d'une sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, ResultType\>\&) | Transforme les elements d'une sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<T, **int32_t**, ResultType\>\&) | Transforme chaque element d'une sequence en une nouvelle forme en incorporant l'indice de l'element. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_Select](../ienumerable/linq_select/)(const [Func](../../system/func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<T, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<ResultType\>\>\>\&) | Projette chaque element d'une sequence et combine les sequences resultant en une seule sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\> [LINQ_SelectMany](../ienumerable/linq_selectmany/)(const [Func](../../system/func/)\<Source, [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Take](../ienumerable/linq_take/)(**int32_t**) | Renvoie un nombre specifie d'elements contigus depuis le debut d'une sequence. |
| [System::ArrayPtr](../../system/arrayptr/)\<T\> [LINQ_ToArray](../ienumerable/linq_toarray/)() | Cree un tableau a partir d'une sequence. |
| [SharedPtr](../../system/sharedptr/)\<[List](./)\<T\>\> [LINQ_ToList](../ienumerable/linq_tolist/)() | Cree une List<T> a partir d'une sequence. |
| [SharedPtr](../../system/sharedptr/)\<[IEnumerable](../ienumerable/)\<T\>\> [LINQ_Where](../ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtre une sequence selon le predicat specifie. |
|  [List](./list/)() | Cree une liste vide. |
|  [List](./list/)(int) | Cree une liste avec une capacite predefinie. |
|  [List](./list/)([IEnumerablePtr](./ienumerableptr/)) | Constructeur de copie. |
| void [Lock](../../system/object/lock/)() | Implemente le verrouillage de l'instruction C# lock(). Appeler directement ou utiliser l'objet sentinelle [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Analogue de la methode [Object.MemberwiseClone()](../../system/object/memberwiseclone/) de C#. Permet le clonage de types personnalises. |
|  [Object](../../system/object/object/)() | Cree un objet. Initialise toutes les structures de donnees internes. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Constructeur de copie. Ne copie rien, en réalité, initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Operateur d'affectation. Ne copie rien, en realite, initialise simplement le nouvel objet et permet la copie des sous-classes. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)([ICollection](../icollection/)\&&) | Operateur d'affectation par deplacement. |
| [ICollection](../icollection/)\& [operator=](../icollection/operator_equal/)(const [ICollection](../icollection/)\&) | Operateur d'affectation par deplacement. |
| vector_t::reference [operator[]](./operator[]/)(int) | Fonction d'acces. |
| vector_t::const_reference [operator[]](./operator[]/)(int) const | Fonction d'acces. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Obtient un iterateur inverse vers le dernier element de la collection (premier en sens inverse). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Obtient un iterateur inverse vers le dernier element de la collection qualifiee const (premier en sens inverse). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Compare les objets par reference. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Compare par reference un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas d'une chaine et nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Specialisation de [Object::ReferenceEquals](../../system/object/referenceequals/) pour le cas de chaines. |
| **bool** [Remove](./remove/)(const T\&) override | Supprime la premiere occurrence d'un element specifique de la liste. |
| int [RemoveAll](./removeall/)([Predicate](../../system/predicate/)\<T\>) | Supprime tous les elements correspondant a un predicat specifique. |
| void [RemoveAt](./removeat/)(int) override | Supprime l'element a la position specifiee. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Diminue le compteur de references partagees du nombre specifie. |
| void [RemoveRange](./removerange/)(int, int) | Supprime une tranche de la liste. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Obtient un iterateur inverse pour un element inexistant avant le debut de la collection. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Obtient un iterateur inverse pour un element inexistant avant le debut de la collection qualifiee const. |
| void [Reverse](./reverse/)() | Inverse l'ordre des elements de toute la liste. |
| void [Reverse](./reverse/)(int, int) | Inverse l'ordre des elements de la tranche de liste. |
| void [set_Capacity](./set_capacity/)(int) | Definit la capacite de la liste. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Definit le n-ieme argument de modele comme pointeur faible (plutot que partage). Permet de basculer les pointeurs dans les conteneurs en mode faible. |
| int [SharedCount](../../system/object/sharedcount/)() const | Obtient la valeur actuelle du compteur de references partagees. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Incremente le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Decremente et renvoie le compteur de references partagees. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| void [Sort](./sort/)(const [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>\&) | Trie les elements de la liste. |
| void [Sort](./sort/)() | Trie les elements de la liste en utilisant le comparateur par defaut. |
| void [Sort](./sort/)(int, int, [SharedPtr](../../system/sharedptr/)\<[System::Collections::Generic::IComparer](../icomparer/)\<T\>\>) | Trie les elements de la tranche de liste. |
| void [Sort](./sort/)([Comparison](../../system/comparison/)\<T\>, **bool**) | Trie les elements de la liste. |
| [ArrayPtr](../../system/arrayptr/)\<T\> [ToArray](./toarray/)() const | Convertit la liste en tableau. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Analogue de la methode [Object.ToString()](../../system/object/tostring/) de C#. Permet de convertir des objets personnalises en chaine. |
| void [TrimExcess](./trimexcess/)() | Ajuste la capacite de la liste a sa taille. |
| **bool** [TrueForAll](./trueforall/)([System::Predicate](../../system/predicate/)\<T\>) | Determine si chaque element de la collection correspond aux conditions definies par le predicat specifie. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Implemente la construction C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Implemente le deverrouillage de l'instruction C# lock(). Appeler directement ou utiliser l'objet sentinelle [LockContext](../../system/lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtient l'implementation de l'iterateur const begin pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtient l'implementation de l'iterateur begin pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtient l'implementation de l'iterateur const end pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtient l'implementation de l'iterateur end pour le conteneur actuel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Incremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Decremente le compteur de references faibles. Ne doit pas etre appele directement; utilisez plutot les pointeurs intelligents ou ThisProtector. |
| virtual  [~ICollection](../icollection/~icollection/)() | Destructeur. |
| virtual  [~Object](../../system/object/~object/)() | Detruit l'objet. Libere toutes les structures de donnees internes. |
## Définitions de type

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | Ce type. |
| [BaseType](./basetype/) | Type d'interface. |
| [vector_t](./vector_t/) | Type de donnees sous-jacent. |
| [iterator](./iterator/) | Type d'iterateur. |
| [const_iterator](./const_iterator/) | Type d'iterateur const. |
| [reverse_iterator](./reverse_iterator/) | Type d'iterateur inverse. |
| [const_reverse_iterator](./const_reverse_iterator/) | Type d'iterateur inverse const. |
| [IEnumerablePtr](./ienumerableptr/) | Conteneur contenant des elements du meme type que nous. |
| [IEnumeratorPtr](./ienumeratorptr/) | type **Enumerator**. |
## Remarques


[List](./) - un wrapper autour de std::vector a utiliser dans le code traduit. Requiert que l'operateur == soit implmente pour le type d'element. Les objets de cette classe ne doivent etre alloues qu'en utilisant la fonction [System::MakeObject()](../../system/makeobject/). Ne creez jamais d'instance de ce type sur la pile ou en utilisant l'operateur new, car cela entrainera des erreurs d'execution et/ou des defauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../../system/smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
#include <system/collections/list.h>
#include <system/smart_ptr.h>

using namespace System;
using namespace System::Collections::Generic;

int main()
{
  // Crée la première liste.
  auto list1 = MakeObject<List<int>>();

  // Remplit la première liste.
  list1->Add(3);
  list1->Add(1);
  list1->Add(-5);
  list1->Add(8);

  // Trie la première liste.
  // Les éléments de la première liste seront: {-5, 1, 3, 8}
  list1->Sort();

  // Supprime l'élément à l'index 2.
  // Les éléments de la première liste seront: {-5, 1, 8}
  list1->RemoveAt(2);

  // Insère l'élément à l'index 1.
  // Les éléments de la première liste seront: {-5, 15, 1, 8}
  list1->Insert(1, 15);

  // Crée la deuxième liste.
  auto list2 = MakeObject<List<int>>();

  // Remplit la deuxième liste.
  list2->Add(10);
  list2->Add(20);
  list2->Add(30);

  // Ajoute les éléments de la deuxième liste à la première.
  list1->AddRange(list2);

  // Affiche les éléments de la première liste.
  for (const auto item: list1)
  {
    std::cout << item << ' ';
  }

  return 0;
}
/*
Cet exemple de code produit la sortie suivante:
- 5 15 1 8 10 20 30
*/
```

## Voir aussi

* Classe [Object](../../system/object/)
* Classe [IList](../ilist/)
* Espace de noms [System::Collections::Generic](../)
* Bibliotheque [Aspose.Slides](../../)