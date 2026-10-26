---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides dla C++ - dokumentacja API
description: 
type: docs
weight: 963
url: /pl/system.testpredicates.typetraits/
---
## Struktury

| Struktura | Opis |
| --- | --- |
| [has_data_method](./has_data_method/) | Sprawdza, czy typ ma metodę data(). Jeśli tak, dziedziczy po std::true_type, w przeciwnym razie dziedziczy po std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Specjalizacja dla typu BitArray, która zapewnia typ boost, który jest tam niedostępny. |
| [has_print_to_method](./has_print_to_method/) | Sprawdza przeciążenie funkcji PrintTo, które przyjmuje dany typ jako pierwszy argument. Jeśli istnieje przeciążenie, dziedziczy po std::true_type, w przeciwnym razie dziedziczy po std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Sprawdza, czy konkretny typ jest kontenerem w stylu STL. W tym celu sprawdza istnienie typów członkowskich iterator i const_iterator. Jeśli oba istnieją, dziedziczy po std::true_type, w przeciwnym razie dziedziczy po std::false_type. |
| [IsEnumerable](./isenumerable/) | Sprawdza, czy typ ma specjalizację [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) jako typ bazowy. Jeśli tak, członek value jest ustawiony na true, w przeciwnym razie jest ustawiony na false. |
| [LargestFPType](./largestfptype/) | Zapewnia alias dla najdłuższego dostępnego typu zmiennoprzecinkowego. Ignoruje typy niebędące zmiennoprzecinkowymi. |

## Definicje typów

| Definicja typu | Opis |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Sprawdza, czy **T1** jest typem arytmetycznym i **T2** jest typem zmiennoprzecinkowym, lub odwrotnie. Jeśli tak, ustawia członek value na true, w przeciwnym razie jest false. |
| [AnyOfDecimal](./anyofdecimal/) | Sprawdza, czy przynajmniej jeden z argumentów typu jest [System::Decimal](../system/decimal/). Jeśli tak, ustawia członek value na true, w przeciwnym razie jest false. |
| [IsArray](./isarray/) | Sprawdza, czy typ jest specjalizacją [System::Array](../system/array/). Jeśli tak, członek value jest ustawiony na true, w przeciwnym razie jest ustawiony na false. |
| [IsList](./islist/) | Sprawdza, czy typ jest specjalizacją [System::Collections::Generic::List](../system.collections.generic/list/). Jeśli tak, członek value jest ustawiony na true, w przeciwnym razie jest ustawiony na false. |
| [BothArrayOrList](./botharrayorlist/) | Sprawdza, czy oba argumenty typu są tablicami lub listami. Jeśli tak, członek value jest ustawiony na true, w przeciwnym razie jest ustawiony na false. |
| [BothEnumerable](./bothenumerable/) | Sprawdza, czy oba argumenty typu są IEnumerable. Jeśli tak, członek value jest ustawiony na true, w przeciwnym razie jest ustawiony na false. |