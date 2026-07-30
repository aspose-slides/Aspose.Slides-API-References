---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 963
url: /cs/system.testpredicates.typetraits/
---
## Struktury

| Struct | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | Kontroluje, zda typ má metodu data(). Pokud ano, dědí std::true_type, jinak dědí std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Specializace pro typ BitArray, která poskytuje boost typ, který je tam nepřístupný. |
| [has_print_to_method](./has_print_to_method/) | Kontroluje přetížení funkce PrintTo, která přijímá daný typ jako první argument. Pokud přetížení existuje, dědí std::true_type, jinak dědí std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Kontroluje, zda je konkrétní typ kontejnerem ve stylu STL. K tomu kontroluje existenci členských typů iterator a const_iterator. Pokud oba existují, dědí std::true_type, jinak dědí std::false_type. |
| [IsEnumerable](./isenumerable/) | Kontroluje, zda typ má specializaci [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) jako základní typ. Pokud ano, člen value je nastaven na true, jinak je nastaven na false. |
| [LargestFPType](./largestfptype/) | Poskytuje alias pro nejdelší dostupný typ s plovoucí řádovou čárkou. Ignoruje typy bez plovoucí řádové čárky. |

## Typedefy

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Kontroluje, že **T1** je aritmetický a **T2** je typ s plovoucí řádovou čárkou, nebo naopak. Pokud ano, nastaví člen value na true, jinak je false. |
| [AnyOfDecimal](./anyofdecimal/) | Kontroluje, že alespoň jeden z typových argumentů je [System::Decimal](../system/decimal/). Pokud ano, nastaví člen value na true, jinak je false. |
| [IsArray](./isarray/) | Kontroluje, zda typ je specializací [System::Array](../system/array/). Pokud ano, člen value je nastaven na true, jinak je nastaven na false. |
| [IsList](./islist/) | Kontroluje, zda typ je specializací [System::Collections::Generic::List](../system.collections.generic/list/). Pokud ano, člen value je nastaven na true, jinak je nastaven na false. |
| [BothArrayOrList](./botharrayorlist/) | Kontroluje, zda oba typové argumenty jsou pole nebo seznamy. Pokud ano, člen value je nastaven na true, jinak je nastaven na false. |
| [BothEnumerable](./bothenumerable/) | Kontroluje, zda oba typové argumenty implementují IEnumerable. Pokud ano, člen value je nastaven na true, jinak je nastaven na false. |