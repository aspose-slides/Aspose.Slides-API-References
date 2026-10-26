---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides a C++ API referenciája
description: 
type: docs
weight: 963
url: /hu/system.testpredicates.typetraits/
---
## Struktúrák

| Struktúra | Leírás |
| --- | --- |
| [has_data_method](./has_data_method/) | Ellenőrzi, hogy egy típus rendelkezik-e a data() metódussal. Ha igen, örökli a std::true_type-ot, ellenkező esetben a std::false_type-ot. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | A BitArray típusra specializáció, amely biztosítja a boost típust, amely ott nem érhető el. |
| [has_print_to_method](./has_print_to_method/) | Ellenőrzi a PrintTo függvény túlterhelését, amely a megadott típust első argumentumként fogadja. Ha létezik túlterhelés, örökli a std::true_type-ot, különben a std::false_type-ot. |
| [IsCppContainer](./iscppcontainer/) | Ellenőrzi, hogy a megadott típus STL-stílusú konténer-e. Ehhez ellenőrzi az iterator és const_iterator tag típusok létezését. Ha mindkettő létezik, örökli a std::true_type-ot, egyébként a std::false_type-ot. |
| [IsEnumerable](./isenumerable/) | Ellenőrzi, hogy a típus rendelkezik-e [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) specializációval alaptípusként. Ha igen, a value tag true értékre van állítva, ellenkező esetben false. |
| [LargestFPType](./largestfptype/) | Alias-t biztosít a leghosszabb lebegőpontos típusra. Figyelmen kívül hagyja a nem lebegőpontos típusokat. |
## Typedef-ek

| Typedef | Leírás |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Ellenőrzi, hogy **T1** aritmetikai típus és **T2** lebegőpontos típus, vagy fordítva. Ha igen, a value tag true értékre van állítva, különben false. |
| [AnyOfDecimal](./anyofdecimal/) | Ellenőrzi, hogy a típusargumentumok közül legalább egy [System::Decimal](../system/decimal/)-e. Ha igen, a value tag true értékre van állítva, különben false. |
| [IsArray](./isarray/) | Ellenőrzi, hogy a típus egy [System::Array](../system/array/) specializáció-e. Ha igen, a value tag true értékre van állítva, különben false. |
| [IsList](./islist/) | Ellenőrzi, hogy a típus egy [System::Collections::Generic::List](../system.collections.generic/list/) specializáció-e. Ha igen, a value tag true értékre van állítva, különben false. |
| [BothArrayOrList](./botharrayorlist/) | Ellenőrzi, hogy mindkét típusargumentum tömb vagy lista-e. Ha igen, a value tag true értékre van állítva, különben false. |
| [BothEnumerable](./bothenumerable/) | Ellenőrzi, hogy mindkét típusargumentum IEnumerable-e. Ha igen, a value tag true értékre van állítva, különben false. |