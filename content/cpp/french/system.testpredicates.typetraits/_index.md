---
title: "System::TestPredicates::TypeTraits"
second_title: Référence de l'API Aspose.Slides pour C++
description: 
type: docs
weight: 963
url: /fr/system.testpredicates.typetraits/
---
## Structures

| Structure | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | Vérifie si un type possède la méthode data(). Si c'est le cas, hérite de std::true_type, sinon il hérite de std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Spécialisation pour le type BitArray qui fournit le type boost qui y est inaccessible. |
| [has_print_to_method](./has_print_to_method/) | Vérifie la surcharge de la fonction PrintTo qui accepte le type donné comme premier argument. Si une surcharge existe, hérite de std::true_type, sinon il hérite de std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Vérifie si un type spécifique est un conteneur de style STL. Pour ce faire, vérifie l'existence des types membres iterator et const_iterator. Si les deux existent, hérite de std::true_type, sinon il hérite de std::false_type. |
| [IsEnumerable](./isenumerable/) | Vérifie si le type possède la spécialisation [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) comme type de base. Si c'est le cas, le membre value est défini sur true, sinon il est défini sur false. |
| [LargestFPType](./largestfptype/) | Fournit un alias pour le type à virgule flottante le plus long fourni. Ignore les types non à virgule flottante. |

## Typedefs

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Vérifie que **T1** est arithmétique et **T2** est à virgule flottante, ou l'inverse. Si c'est le cas, le membre value est mis à true, sinon il est false. |
| [AnyOfDecimal](./anyofdecimal/) | Vérifie qu'au moins un des arguments de type est [System::Decimal](../system/decimal/). Si c'est le cas, le membre value est mis à true, sinon il est false. |
| [IsArray](./isarray/) | Vérifie si le type est une spécialisation [System::Array](../system/array/). Si c'est le cas, le membre value est défini sur true, sinon il est défini sur false. |
| [IsList](./islist/) | Vérifie si le type est une spécialisation [System::Collections::Generic::List](../system.collections.generic/list/). Si c'est le cas, le membre value est défini sur true, sinon il est défini sur false. |
| [BothArrayOrList](./botharrayorlist/) | Vérifie si les deux arguments de type sont des tableaux ou des listes. Si c'est le cas, le membre value est défini sur true, sinon il est défini sur false. |
| [BothEnumerable](./bothenumerable/) | Vérifie si les deux arguments de type sont IEnumerable. Si c'est le cas, le membre value est défini sur true, sinon il est défini sur false. |