---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 963
url: /de/system.testpredicates.typetraits/
---
## Strukturen

| Struct | Description |
| --- | --- |
| [has_data_method](./has_data_method/) | Überprüft, ob ein Typ die Methode data() hat. Falls ja, erbt std::true_type, andernfalls erbt std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Spezialisierung für den Typ BitArray, die einen boost-Typ bereitstellt, der dort nicht zugänglich ist. |
| [has_print_to_method](./has_print_to_method/) | Überprüft, ob eine Überladung der Funktion PrintTo existiert, die den angegebenen Typ als erstes Argument akzeptiert. Falls eine Überladung existiert, erbt std::true_type, andernfalls erbt std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Überprüft, ob ein bestimmter Typ ein STL-ähnlicher Container ist. Dazu wird geprüft, ob die Mitgliedstypen iterator und const_iterator existieren. Wenn beide existieren, erbt std::true_type, andernfalls erbt std::false_type. |
| [IsEnumerable](./isenumerable/) | Überprüft, ob ein Typ die [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)-Spezialisierung als Basistyp hat. Falls ja, wird das Mitglied value auf true gesetzt, sonst auf false. |
| [LargestFPType](./largestfptype/) | Stellt einen Alias für den längsten bereitgestellten Gleitkommatyp zur Verfügung. Ignoriert Nicht-Gleitkomma-Typen. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Überprüft, dass **T1** arithmetisch und **T2** ein Gleitkomma-Typ ist, oder umgekehrt. Falls ja, wird das Mitglied value auf true gesetzt, sonst ist es false. |
| [AnyOfDecimal](./anyofdecimal/) | Überprüft, dass mindestens einer der Typ-Argumente [System::Decimal](../system/decimal/) ist. Falls ja, wird das Mitglied value auf true gesetzt, sonst ist es false. |
| [IsArray](./isarray/) | Überprüft, ob ein Typ eine [System::Array](../system/array/)-Spezialisierung ist. Falls ja, wird das Mitglied value auf true gesetzt, sonst auf false. |
| [IsList](./islist/) | Überprüft, ob ein Typ eine [System::Collections::Generic::List](../system.collections.generic/list/)-Spezialisierung ist. Falls ja, wird das Mitglied value auf true gesetzt, sonst auf false. |
| [BothArrayOrList](./botharrayorlist/) | Überprüft, ob beide Typ-Argumente Arrays oder Listen sind. Falls ja, wird das Mitglied value auf true gesetzt, sonst auf false. |
| [BothEnumerable](./bothenumerable/) | Überprüft, ob beide Typ-Argumente IEnumerable sind. Falls ja, wird das Mitglied value auf true gesetzt, sonst auf false. |