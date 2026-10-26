---
title: Array
second_title: Référence API Aspose.Slides pour C++
description: "Classe représentant une structure de données tableau. Les objets de cette classe ne doivent être alloués qu'en utilisant les fonctions System::MakeArray() et System::MakeObject(). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur System::SmartPtr et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument."
type: docs
weight: 14
url: /fr/system/array/
---
## Array classe

Classe représentant une structure de données tableau. Les objets de cette classe ne doivent être alloués qu'en utilisant les fonctions [System::MakeArray()](../makearray/) et [System::MakeObject()](../makeobject/). Ne créez jamais d'instance de ce type sur la pile ou en utilisant l'opérateur new, car cela entraînera des erreurs d'exécution et/ou des défauts d'assertion. Enveloppez toujours cette classe dans un pointeur [System::SmartPtr](../smartptr/) et utilisez ce pointeur pour le passer aux fonctions en tant qu'argument.

```cpp
template<typename T>class Array : public System::ArrayBase,
                                  public System::Collections::Generic::IList<T>
```

### Paramètres de modèle

| Paramètre | Description |
| --- | --- |
| T | Type des éléments d'un tableau |

## Méthodes

| Méthode | Description |
| --- | --- |
| void [Add](./add/)(const T\&) override | Non pris en charge car le tableau représenté par l'objet actuel est en lecture seule. |
| [Array](./array/)() | Construit un tableau vide. |
| [Array](./array/)(int, const T\&) | Constructeur de remplissage. |
| [Array](./array/)(typename std::enable_if\<std::is_arithmetic\<T\>::value\&&std::is_arithmetic\<[ValueType](./valuetype/)\>::value\&&std::is_convertible\<[ValueType](./valuetype/), T\>::value, int\>::type, [ValueType](./valuetype/)) | Constructeur de remplissage. |
| [Array](./array/)(int, const T) | Constructeur de remplissage. |
| [Array](./array/)(**vector_t**\&&) | Constructeur de déplacement. |
| [Array](./array/)(const **vector_t**\&) | Constructeur de copie. |
| [Array](./array/)(const std::vector\<Q\>\&) | Construit un objet [Array](./) et le remplit avec des valeurs copiées d'un objet std::vector dont le type des valeurs est le même que **T** mais différent de **UnderlyingType**. |
| [Array](./array/)(std::vector\<Q\>\&&) | Construit un objet [Array](./) et le remplit avec des valeurs déplacées d'un objet std::vector dont le type des valeurs est le même que **T** mais différent de **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<[UnderlyingType](./underlyingtype/)\>) | Construit un objet [Array](./) et le remplit avec des valeurs provenant de la liste d'initialisation spécifiée contenant des éléments de type **UnderlyingType**. |
| [Array](./array/)(const std::array\<[UnderlyingType](./underlyingtype/), InitArraySize\>\&) | Construit un objet [Array](./) et le remplit avec des valeurs provenant du tableau spécifié contenant des éléments de type **UnderlyingType**. |
| [Array](./array/)(std::initializer_list\<**bool**\>, int) | Construit un objet [Array](./) et le remplit avec des valeurs provenant de la liste d'initialisation spécifiée contenant des éléments de type bool. |
| static [SharedPtr](../sharedptr/)\<[Collections::ObjectModel::ReadOnlyCollection](../../system.collections.objectmodel/readonlycollection/)\<T\>\> [AsReadOnly](./asreadonly/)(const [SharedPtr](../sharedptr/)\<[Array](./)\<T\>\>\&) | Convertit le tableau en collection en lecture seule. |
| [iterator](./iterator/) [begin](./begin/)() | Renvoie un itérateur vers le premier élément du conteneur. Si le conteneur est vide, l'itérateur retourné sera égal à [end()](./end/). |
| [const_iterator](./const_iterator/) [begin](./begin/)() const | Renvoie un itérateur vers le premier élément du conteneur en lecture seule. Si le conteneur est vide, l'itérateur retourné sera égal à [end()](./end/). |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const T\&) | Effectue une recherche binaire dans le tableau trié. |
| static int [BinarySearch](./binarysearch/)([System::ArrayPtr](../arrayptr/)\<T\>, const Y\&, const [SharedPtr](../sharedptr/)\<[Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Z\>\>\&) | NON IMPLÉMENTÉ. |
| [const_iterator](./const_iterator/) [cbegin](./cbegin/)() const | Renvoie un itérateur vers le premier élément du conteneur qualifié const. Si le conteneur est vide, l'itérateur retourné sera égal à [cend()](./cend/). |
| [const_iterator](./const_iterator/) [cend](./cend/)() const | Renvoie un itérateur vers l'élément suivant le dernier élément du conteneur. Cet élément sert de marqueur ; y accéder entraîne un comportement indéfini. |
| void [Clear](./clear/)() override | Non pris en charge car le tableau représenté par l'objet actuel est en lecture seule. |
| static void [Clear](./clear/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Remplace **count** valeurs à partir de l'indice **startIndex** dans le tableau spécifié par des valeurs par défaut. |
| [ArrayPtr](../arrayptr/)\<T\> [Clone](./clone/)() | Clone le tableau. |
| static void [ConstrainedCopy](./constrainedcopy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copie une plage d'éléments à partir d'un [System.Array](./) à partir de la source spécifiée. |
| **bool** [Contains](./contains/)(const T\&) const override | Détermine si l'élément spécifié se trouve dans le tableau. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, [Converter](../converter/)\<InputType, OutputType\>) | Construit un nouvel objet [Array](./) et le remplit avec des éléments du tableau spécifié convertis en type **OutputType** à l'aide du délégué de conversion spécifié. |
| static [ArrayPtr](../arrayptr/)\<OutputType\> [ConvertAll](./convertall/)([ArrayPtr](../arrayptr/)\<InputType\>, std::function\<OutputType(InputType)>) | Construit un nouvel objet [Array](./) et le remplit avec des éléments du tableau spécifié convertis en type **OutputType** à l'aide de l'objet fonction de conversion spécifié. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copie le nombre spécifié d'éléments du tableau source vers le tableau de destination. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copie le nombre spécifié d'éléments de la vue de tableau source vers le tableau de destination. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::ArrayView\<DstType\>, **int64_t**) | Copie le nombre spécifié d'éléments du tableau source vers la vue de tableau de destination. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, System::Details::ArrayView\<DstType\>, **int64_t**) | Copie le nombre spécifié d'éléments de la vue de tableau source vers la vue de tableau de destination. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) | Copie le nombre spécifié d'éléments du tableau sur la pile source vers le tableau de destination. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, System::Details::StackArray\<DstType, N\>\&, **int64_t**) | Copie le nombre spécifié d'éléments du tableau source vers le tableau de destination sur la pile. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, System::Details::StackArray\<DstType, ND\>\&, **int64_t**) | Copie le nombre spécifié d'éléments du tableau sur la pile source vers le tableau sur la pile de destination. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments du tableau source à partir de l'index spécifié vers la position spécifiée du tableau de destination. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments de la vue de tableau source à partir de l'index spécifié vers la position spécifiée du tableau de destination. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments du tableau source à partir de l'index spécifié vers la position spécifiée de la vue de tableau de destination. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>, **int64_t**, System::Details::ArrayView\<DstType\>, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments de la vue de tableau source à partir de l'index spécifié vers la position spécifiée de la vue de tableau de destination. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, N\>\&, **int64_t**, const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments du tableau sur la pile source à partir de l'index spécifié vers la position spécifiée du tableau de destination. |
| static void [Copy](./copy/)(const [ArrayPtr](../arrayptr/)\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, N\>\&, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments du tableau source à partir de l'index spécifié vers la position spécifiée du tableau de destination sur la pile. |
| static void [Copy](./copy/)(System::Details::StackArray\<SrcType, NS\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments du tableau sur la pile source à partir de l'index spécifié vers la position spécifiée du tableau de destination sur la pile. |
| static void [Copy](./copy/)(System::Details::ArrayView\<SrcType\>\&, **int64_t**, System::Details::StackArray\<DstType, ND\>\&, **int64_t**, **int64_t**) | Copie un nombre spécifié d'éléments de la vue de tableau source à partir de l'index spécifié vers la position spécifiée du tableau de destination sur la pile. |
| void [CopyTo](./copyto/)([ArrayPtr](../arrayptr/)\<T\>, int) override | Copie tous les éléments du tableau actuel vers le tableau de destination spécifié. Les éléments sont insérés dans le tableau de destination à partir de l'index indiqué par l'argument **arrayIndex**. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**) const | Copie tous les éléments du tableau actuel vers le tableau de destination spécifié. Les éléments sont insérés dans le tableau de destination à partir de l'index indiqué par l'argument **dstIndex**. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**) const | Copie tous les éléments du tableau actuel vers la vue de tableau de destination spécifiée. Les éléments sont insérés dans la vue de destination à partir de l'index indiqué par **dstIndex**. |
| void [CopyTo](./copyto/)(const [ArrayPtr](../arrayptr/)\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copie un nombre spécifié d'éléments du tableau actuel à partir de la position spécifiée vers le tableau de destination spécifié. Les éléments sont insérés dans le tableau de destination à partir de l'index indiqué par **dstIndex**. |
| void [CopyTo](./copyto/)(const System::Details::ArrayView\<DstType\>\&, **int64_t**, **int64_t**, **int64_t**) const | Copie un nombre spécifié d'éléments du tableau actuel à partir de la position spécifiée vers la vue de tableau de destination spécifiée. Les éléments sont insérés dans la vue de destination à partir de l'index indiqué par **dstIndex**. |
| int [Count](./count/)() const | Renvoie un nombre représentant le nombre total d'éléments dans toutes les dimensions du tableau. |
| [const_reverse_iterator](./const_reverse_iterator/) [crbegin](./crbegin/)() const | Renvoie un itérateur inverse vers le premier élément du conteneur inversé. Il correspond au dernier élément du conteneur non inversé. Si le conteneur est vide, l'itérateur retourné est égal à [crend()](./crend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [crend](./crend/)() const | Renvoie un itérateur inverse vers l'élément suivant le dernier élément du conteneur inversé. Il correspond à l'élément précédant le premier élément du conteneur non inversé. Cet élément sert de marqueur ; y accéder entraîne un comportement indéfini. |
| **vector_t**\& [data](./data/)() | Renvoie une référence à la structure de données interne utilisée pour stocker les éléments du tableau. |
| const **vector_t**\& [data](./data/)() const | Renvoie une référence constante à la structure de données interne utilisée pour stocker les éléments du tableau. |
| vector_t::pointer [data_ptr](./data_ptr/)() | Renvoie un pointeur brut vers le début du tampon mémoire où les éléments du tableau sont stockés. |
| const [UnderlyingType](./underlyingtype/) * [data_ptr](./data_ptr/)() const | Renvoie un pointeur brut constant vers le début du tampon mémoire où les éléments du tableau sont stockés. |
| [iterator](./iterator/) [end](./end/)() | Renvoie un itérateur vers l'élément suivant le dernier élément du conteneur. Cet élément sert de marqueur ; y accéder entraîne un comportement indéfini. |
| [const_iterator](./const_iterator/) [end](./end/)() const | Renvoie un itérateur vers l'élément suivant le dernier élément du conteneur en lecture seule. Cet élément sert de marqueur ; y accéder entraîne un comportement indéfini. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Compare les objets en utilisant la sémantique C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type référence dans le style C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Compare les objets de type valeur dans le style C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que la norme IEC 60559 :1989 stipule que NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Émule la comparaison en virgule flottante de style C# où deux NaN sont considérés égaux bien que la norme IEC 60559 :1989 stipule que NaN n'est égal à aucune valeur, y compris NaN. |
| static **bool** [Exists](./exists/)([ArrayPtr](../arrayptr/)\<T\>, std::function\<**bool**(T)>) | Détermine si l'objet [Array](./) spécifié contient un élément qui satisfait les exigences du prédicat spécifié. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | À usage interne uniquement. |
| static T [Find](./find/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Recherche le premier élément du tableau spécifié qui satisfait les conditions du prédicat spécifié. |
| static [System::ArrayPtr](../arrayptr/)\<T\> [FindAll](./findall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Récupère tous les éléments qui correspondent aux conditions définies par le prédicat spécifié. |
| static int [FindIndex](./findindex/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Recherche le premier élément du tableau spécifié qui satisfait les conditions du prédicat spécifié. |
| static void [ForEach](./foreach/)(const [ArrayPtr](../arrayptr/)\<T\>\&, [System::Action](../action/)\<T\>) | Effectue l'action spécifiée sur chaque élément du tableau spécifié. |
| int [get_Count](./get_count/)() const override | Renvoie la taille du tableau. |
| **bool** [get_IsFixedSize](../../system.collections.generic/ilist/get_isfixedsize/)() | Vérifie si la collection a une taille fixe. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const override | Indique si le tableau est en lecture seule. |
| **int32_t** [get_Length](./get_length/)() const override | Renvoie un entier 32 bits représentant le nombre total d'éléments dans toutes les dimensions du tableau. |
| **int64_t** [get_LongLength](./get_longlength/)() const | Renvoie un entier 64 bits représentant le nombre total d'éléments dans toutes les dimensions du tableau. |
| **int32_t** [get_Rank](./get_rank/)() const | NON IMPLÉMENTÉ. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [get_SyncRoot](../../system.collections.generic/icollection/get_syncroot/)() const | Obtient l'objet avec lequel la collection est synchronisée. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Obtient la structure de données du compteur de références associée à l'objet. |
| [EnumeratorPtr](./enumeratorptr/) [GetEnumerator](./getenumerator/)() override | Renvoie un pointeur vers l'objet **Enumerator** qui fournit l'interface IEnumerator aux éléments du tableau représenté par l'objet actuel. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Analogue de la méthode C# [Object.GetHashCode()](../object/gethashcode/). Permet le hachage d'objets personnalisés. |
| int [GetLength](./getlength/)(int) | Renvoie le nombre d'éléments dans la dimension spécifiée. |
| **int64_t** [GetLongLength](./getlonglength/)(int) | Renvoie le nombre d'éléments dans la dimension spécifiée sous forme d'entier 64 bits. |
| int [GetLowerBound](./getlowerbound/)(int) const | Renvoie la borne inférieure de la dimension spécifiée. |
| size_t [GetSizeTLength](./getsizetlength/)() const | Renvoie une variable std::size_t représentant le nombre total d'éléments dans toutes les dimensions du tableau. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Obtient le type réel de l'objet. Analogue de l'appel C# [System.Object.GetType()](../object/gettype/). |
| int [GetUpperBound](./getupperbound/)(int) | Renvoie la borne supérieure de la dimension spécifiée. |
| [ICollection](../../system.collections.generic/icollection/icollection/)() | Constructeur par défaut. |
| [ICollection](../../system.collections.generic/icollection/icollection/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Constructeur de copie. |
| [ICollection](../../system.collections.generic/icollection/icollection/)([ICollection](../../system.collections.generic/icollection/)\&&) | Constructeur de déplacement. |
| T [idx_get](./idx_get/)(int) const override | Renvoie l'élément à l'index spécifié. |
| void [idx_set](./idx_set/)(int, T) override | Définit la valeur spécifiée comme élément du tableau à l'index indiqué. |
| int [IndexOf](./indexof/)(const T\&) const override | Détermine l'index de la première occurrence de l'élément spécifié dans le tableau. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Détermine l'index de la première occurrence de l'élément spécifié dans le tableau. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Détermine l'index de la première occurrence de l'élément spécifié dans le tableau à partir de l'index indiqué. |
| static int [IndexOf](./indexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Détermine l'index de la première occurrence de l'élément spécifié dans une plage d'éléments du tableau définie par l'index de début et le nombre d'éléments de la plage. |
| [ArrayPtr](../arrayptr/)\<T\> [Init](./init/)(const T) | Remplit le tableau représenté par l'objet actuel avec les valeurs du tableau spécifié. |
| void [Initialize](./initialize/)() | Remplit le tableau avec des objets construits par défaut du type **T**. |
| void [Insert](./insert/)(int, const T\&) override | Non pris en charge car le tableau représenté par l'objet actuel est en lecture seule. |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Vérifie si l'objet représente une instance du type décrit par **targetType**. Analogue de l'opérateur C# `is`. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int, int) | Détermine l'index de la dernière occurrence de l'élément spécifié dans une plage d'éléments du tableau définie par l'index de début et le nombre d'éléments de la plage. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&, int) | Détermine l'index de la dernière occurrence de l'élément spécifié dans le tableau à partir de l'index indiqué. |
| static int [LastIndexOf](./lastindexof/)(const [ArrayPtr](../arrayptr/)\<ArrayType\>\&, const [ValueType](./valuetype/)\&) | Détermine l'index de la dernière occurrence de l'élément spécifié dans le tableau. |
| T [LINQ_Aggregate](../../system.collections.generic/ienumerable/linq_aggregate/)(const [Func](../func/)\<T, T, T\>\&) | Applique une fonction d'accumulateur sur une séquence. |
| **bool** [LINQ_All](../../system.collections.generic/ienumerable/linq_all/)(std::function\<**bool**(T)>) | Détermine si tous les éléments d'une séquence satisfont une condition. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)() | Détermine si une séquence contient des éléments. |
| **bool** [LINQ_Any](../../system.collections.generic/ienumerable/linq_any/)(std::function\<**bool**(T)>) | Détermine si un élément quelconque d'une séquence existe ou satisfait une condition. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() | Convertit les éléments vers le type spécifié. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Cast](../../system.collections.generic/ienumerable/linq_cast/)() |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Concat](../../system.collections.generic/ienumerable/linq_concat/)([SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>) | Concatène deux séquences. |
| **bool** [LINQ_Contains](../../system.collections.generic/ienumerable/linq_contains/)(T) | Détermine si une séquence contient une valeur spécifiée. |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)() | Renvoie le nombre d'éléments dans la séquence (calculé par comptage direct). |
| int [LINQ_Count](../../system.collections.generic/ienumerable/linq_count/)(const [Func](../func/)\<T, **bool**\>\&) | Renvoie le nombre d'éléments dans la séquence qui satisfont la condition spécifiée. |
| T [LINQ_ElementAt](../../system.collections.generic/ienumerable/linq_elementat/)(int) | Renvoie l'élément à l'index spécifié dans une séquence. |
| T [LINQ_ElementAtOrDefault](../../system.collections.generic/ienumerable/linq_elementatordefault/)(int) | Renvoie l'élément à l'index spécifié dans une séquence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)() | Renvoie le premier élément d'une séquence. |
| T [LINQ_First](../../system.collections.generic/ienumerable/linq_first/)(const [Func](../func/)\<T, **bool**\>\&) | Renvoie le premier élément d'une séquence qui satisfait la condition spécifiée. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)() | Renvoie le premier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| T [LINQ_FirstOrDefault](../../system.collections.generic/ienumerable/linq_firstordefault/)(std::function\<**bool**(T)>) | Renvoie le premier élément de la séquence qui satisfait une condition ou une valeur par défaut si aucun élément ne correspond. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, T\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>) | Regroupe les éléments d'une séquence. |
| [System::SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[System::SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<T, Key\>, [System::Func](../func/)\<T, Element\>) | Regroupe les éléments d'une séquence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Source\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<[SharedPtr](../sharedptr/)\<[System::Linq::IGrouping](../../system.linq/igrouping/)\<Key, Element\>\>\>\> [LINQ_GroupBy](../../system.collections.generic/ienumerable/linq_groupby/)([System::Func](../func/)\<Source, Key\>, [System::Func](../func/)\<Source, Element\>) |  |
| T [LINQ_Last](../../system.collections.generic/ienumerable/linq_last/)() | Renvoie le dernier élément d'une séquence. |
| T [LINQ_LastOrDefault](../../system.collections.generic/ienumerable/linq_lastordefault/)() | Renvoie le dernier élément d'une séquence, ou une valeur par défaut si la séquence est vide. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<T, ResultType\>\&) | Appelle une fonction de transformation sur chaque élément d'une séquence générique et renvoie la valeur maximale obtenue. |
| ResultType [LINQ_Max](../../system.collections.generic/ienumerable/linq_max/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<T, ResultType\>\&) | Appelle une fonction de transformation sur chaque élément d'une séquence générique et renvoie la valeur minimale obtenue. |
| ResultType [LINQ_Min](../../system.collections.generic/ienumerable/linq_min/)(const [Func](../func/)\<Source, ResultType\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() | Filtre les éléments de la séquence selon le type spécifié. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_OfType](../../system.collections.generic/ienumerable/linq_oftype/)() |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<T, Key\>\&) | Trie les éléments d'une séquence en ordre croissant selon les valeurs de clé sélectionnées par **keySelector**. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderBy](../../system.collections.generic/ienumerable/linq_orderby/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<T\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<T, Key\>\&) | Trie les éléments d'une séquence en ordre décroissant selon les valeurs de clé sélectionnées par **keySelector**. |
| [SharedPtr](../sharedptr/)\<[Linq::IOrderedEnumerable](../../system.linq/iorderedenumerable/)\<Source\>\> [LINQ_OrderByDescending](../../system.collections.generic/ienumerable/linq_orderbydescending/)(const [Func](../func/)\<Source, Key\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Reverse](../../system.collections.generic/ienumerable/linq_reverse/)() | Inverse l'ordre des éléments d'une séquence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, ResultType\>\&) | Transforme les éléments d'une séquence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<T, **int32_t**, ResultType\>\&) | Transforme chaque élément d'une séquence en une nouvelle forme en incorporant l'indice de l'élément. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_Select](../../system.collections.generic/ienumerable/linq_select/)(const [Func](../func/)\<Source, **int32_t**, Result\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<T, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<ResultType\>\>\>\&) | Projette chaque élément d'une séquence et combine les séquences résultantes en une seule séquence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\> [LINQ_SelectMany](../../system.collections.generic/ienumerable/linq_selectmany/)(const [Func](../func/)\<Source, [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<Result\>\>\>\&) |  |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Take](../../system.collections.generic/ienumerable/linq_take/)(**int32_t**) | Renvoie un nombre spécifié d'éléments contigus depuis le début d'une séquence. |
| [System::ArrayPtr](../arrayptr/)\<T\> [LINQ_ToArray](../../system.collections.generic/ienumerable/linq_toarray/)() | Crée un tableau à partir d'une séquence. |
| [SharedPtr](../sharedptr/)\<[List](../../system.collections.generic/list/)\<T\>\> [LINQ_ToList](../../system.collections.generic/ienumerable/linq_tolist/)() | Crée une List<T> à partir d'une séquence. |
| [SharedPtr](../sharedptr/)\<[IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\> [LINQ_Where](../../system.collections.generic/ienumerable/linq_where/)(std::function\<**bool**(T)>) | Filtre une séquence selon le prédicat spécifié. |
| void [Lock](../object/lock/)() | Implémente le verrouillage de l'instruction C# `lock()` ; appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| [UnderlyingType](./underlyingtype/) [Max](./max/)() const | Trouve le plus grand élément du tableau en utilisant [operator<()](../operator_less/) pour comparer les éléments. |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Analogue de la méthode C# [Object.MemberwiseClone()](../object/memberwiseclone/). Permet le clonage de types personnalisés. |
| [UnderlyingType](./underlyingtype/) [Min](./min/)() const | Trouve le plus petit élément du tableau en utilisant [operator<()](../operator_less/) pour comparer les éléments. |
| [Object](../object/object/)() | Crée l'objet. Initialise toutes les structures de données internes. |
| [Object](../object/object/)([Object](../object/) const\&) | Constructeur de copie. Ne copie rien réellement, se contente d'initialiser le nouvel objet et de permettre la copie des sous-classes. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Opérateur d'affectation. Ne copie rien réellement, se contente d'initialiser le nouvel objet et de permettre la copie des sous-classes. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)([ICollection](../../system.collections.generic/icollection/)\&&) | Opérateur d'affectation par déplacement. |
| [ICollection](../../system.collections.generic/icollection/)\& [operator=](../../system.collections.generic/icollection/operator_equal/)(const [ICollection](../../system.collections.generic/icollection/)\&) | Opérateur d'affectation par déplacement. |
| [UnderlyingType](./underlyingtype/)\& [operator[]](./operator[]/)(int) | Renvoie un élément à l'index indiqué. |
| [UnderlyingType](./underlyingtype/) const\& [operator[]](./operator[]/)(int) const | Renvoie un élément à l'index indiqué. |
| void * [raw_data_ptr](./raw_data_ptr/)() override | Renvoie un pointeur vers le premier élément d'un tableau à une dimension. Pour les tableaux à plusieurs dimensions, le résultat est indéfini. |
| [reverse_iterator](./reverse_iterator/) [rbegin](./rbegin/)() | Renvoie un itérateur inverse vers le premier élément du conteneur inversé. Il correspond au dernier élément du conteneur non inversé. Si le conteneur est vide, l'itérateur retourné est égal à [rend()](./rend/). |
| [const_reverse_iterator](./const_reverse_iterator/) [rbegin](./rbegin/)() const | Renvoie un itérateur inverse vers le premier élément du conteneur inversé. Il correspond au dernier élément du conteneur non inversé. Si le conteneur est vide, l'itérateur retourné est égal à [rend()](./rend/). |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Compare les objets par référence. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Compare par référence un objet de type valeur avec nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas d'une chaîne et nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Spécialisation de [Object::ReferenceEquals](../object/referenceequals/) pour le cas de chaînes. |
| **bool** [Remove](./remove/)(const T\&) override | Non pris en charge car le tableau représenté par l'objet actuel est en lecture seule. |
| void [RemoveAt](./removeat/)(int) override | Non pris en charge car le tableau représenté par l'objet actuel est en lecture seule. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Diminue le compteur de références partagées du nombre indiqué. |
| [reverse_iterator](./reverse_iterator/) [rend](./rend/)() | Renvoie un itérateur inverse vers l'élément suivant le dernier élément du conteneur inversé. Il correspond à l'élément précédant le premier élément du conteneur non inversé. Cet élément sert de marqueur ; y accéder entraîne un comportement indéfini. |
| [const_reverse_iterator](./const_reverse_iterator/) [rend](./rend/)() const | Renvoie un itérateur inverse vers l'élément suivant le dernier élément du conteneur inversé. Il correspond à l'élément précédant le premier élément du conteneur non inversé. Cet élément sert de marqueur ; y accéder entraîne un comportement indéfini. |
| static void [Resize](./resize/)([ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int) | Modifie la taille du tableau spécifié à la valeur indiquée ou crée un nouveau tableau de la taille indiquée. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Inverse les éléments du tableau spécifié. |
| static void [Reverse](./reverse/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Inverse une plage d'éléments du tableau spécifié. |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | Force le tableau à traiter les pointeurs stockés comme faibles (le cas échéant). |
| void [SetValue](./setvalue/)(const T\&, int) | Définit la valeur de l'élément à l'index indiqué. |
| int [SharedCount](../object/sharedcount/)() const | Obtient la valeur actuelle du compteur de références partagées. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Incrémente le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou **ThisProtector**. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Décrémente et renvoie le compteur de références partagées. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou **ThisProtector**. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&) | Trie les éléments du tableau spécifié en utilisant le comparateur par défaut. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, int, int) | Trie une plage d'éléments du tableau spécifié en utilisant le comparateur par défaut. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<T\>\>\&) | Trie les éléments du tableau spécifié en utilisant le comparateur spécifié. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [SharedPtr](../sharedptr/)\<[System::Collections::Generic::IComparer](../../system.collections.generic/icomparer/)\<Y\>\>\&) | NON IMPLÉMENTÉ. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<[Type](../object/type/)\>\&, const [System::Comparison](../comparison/)\<T\>\&) | Trie les éléments du tableau spécifié en utilisant la comparaison spécifiée. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&) | Trie deux tableaux : l'un contenant les clés et l'autre les éléments correspondants, en fonction des valeurs du tableau de clés comparées avec l'opérateur `<`. |
| static void [Sort](./sort/)(const [ArrayPtr](../arrayptr/)\<TKey\>\&, const [ArrayPtr](../arrayptr/)\<TValue\>\&, int, int) | Trie deux tableaux : l'un contenant les clés et l'autre les éléments correspondants, en fonction des valeurs du tableau de clés comparées avec le comparateur par défaut. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Analogue de la méthode C# [Object.ToString()](../object/tostring/). Permet de convertir des objets personnalisés en chaîne. |
| static **bool** [TrueForAll](./trueforall/)([System::ArrayPtr](../arrayptr/)\<T\>, [System::Predicate](../predicate/)\<T\>) | Détermine si tous les éléments du tableau spécifié satisfont les conditions définies par le prédicat spécifié. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Implémente le construct C# `typeof([System.Object](../object/))`. |
| void [Unlock](../object/unlock/)() | Implémente le déverrouillage de l'instruction C# `lock()` ; appelez directement ou utilisez l'objet sentinelle [LockContext](../lockcontext/). |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginConstIterator](./virtualizebeginconstiterator/)() const override | Obtient l'implémentation de l'itérateur const `begin` pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeBeginIterator](./virtualizebeginiterator/)() override | Obtient l'implémentation de l'itérateur `begin` pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndConstIterator](./virtualizeendconstiterator/)() const override | Obtient l'implémentation de l'itérateur const `end` pour le conteneur actuel. |
| System::Details::VirtualizedIteratorBase\<T\> * [virtualizeEndIterator](./virtualizeenditerator/)() override | Obtient l'implémentation de l'itérateur `end` pour le conteneur actuel. |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Incrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou **ThisProtector**. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Décrémente le compteur de références faibles. Ne doit pas être appelé directement ; utilisez plutôt les pointeurs intelligents ou **ThisProtector**. |
| virtual [~ICollection](../../system.collections.generic/icollection/~icollection/)() | Destructeur. |
| virtual [~Object](../object/~object/)() | Détruit l'objet. Libère toutes les structures de données internes. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [ValueType](./valuetype/) | Alias du type des éléments du tableau. |
| [UnderlyingType](./underlyingtype/) | Alias du type utilisé pour représenter chaque élément du tableau. |
| [EnumerablePtr](./enumerableptr/) | Alias du type pointeur partagé vers un objet IEnumerable contenant des éléments de type **T**. |
| [EnumeratorPtr](./enumeratorptr/) | Alias du type pointeur partagé vers un objet IEnumerator contenant des éléments de type **T**. |
| [iterator](./iterator/) | Type d'itérateur. |
| [const_iterator](./const_iterator/) | Type d'itérateur constant. |
| [reverse_iterator](./reverse_iterator/) | Type d'itérateur inverse. |
| [const_reverse_iterator](./const_reverse_iterator/) | Type d'itérateur inverse constant. |

## Remarques



```cpp
#include <system/array.h>
#include <system/smart_ptr.h>

using namespace System;

void Print(const SmartPtr<Array<int32_t>> &arrayPtr)
{
  for (auto item: arrayPtr)
  {
    std::cout << item << ' ';
  }
  std::cout << std::endl;
}

int main()
{
  // Crée et remplit le tableau.
  auto arrayPtr = MakeObject<Array<int32_t>>(5, 0);
  for (auto i = 0; i < arrayPtr->get_Length(); ++i)
  {
    arrayPtr[i] = 5 - i;
  }

  // Affiche les éléments du tableau.
  Print(arrayPtr);

  // Trie les éléments du tableau par ordre croissant.
  Array<int32_t>::Sort(arrayPtr);

  // Affiche les éléments du tableau.
  Print(arrayPtr);

  // Affiche le nombre d'éléments du tableau.
  std::cout << arrayPtr->get_Length() << std::endl;

  // Affiche l'indice de l'élément égal à 4.
  std::cout << arrayPtr->IndexOf(4) << std::endl;

  // Redimensionne le tableau.
  Array<int32_t>::Resize(arrayPtr, 3);

  // Affiche les éléments du tableau.
  Print(arrayPtr);

  return 0;
}
/*
Cet exemple de code produit la sortie suivante:
5 4 3 2 1
1 2 3 4 5
5
3
1 2 3
*/
```

## Voir aussi

* Class [ArrayBase](../arraybase/)
* Class [IList](../../system.collections.generic/ilist/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)