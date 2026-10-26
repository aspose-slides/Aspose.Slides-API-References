---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 963
url: /sv/system.testpredicates.typetraits/
---
## Strukturer

| Struktur | Beskrivning |
| --- | --- |
| [has_data_method](./has_data_method/) | Kontrollerar om en typ har data()-metod. Om den har det, ärver std::true_type, annars ärver std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Specialisering för BitArray-typen som tillhandahåller boost-typ som är oåtkomlig där. |
| [has_print_to_method](./has_print_to_method/) | Kontrollerar om det finns en överlagring av PrintTo-funktionen som accepterar den givna typen som första argument. Om en överlagring finns, ärver std::true_type, annars ärver std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Kontrollerar om en specifik typ är en STL-liknande container. För att göra detta kontrolleras om medlems-typerna iterator och const_iterator finns. Om båda finns, ärver std::true_type, annars ärver std::false_type. |
| [IsEnumerable](./isenumerable/) | Kontrollerar om typen har [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)-specialisering som basklass. I så fall sätts värdemedlemmen till true, annars till false. |
| [LargestFPType](./largestfptype/) | Tillhandahåller ett alias för den längst möjliga flyttalstypen som finns. Ignorerar typer som inte är flyttal. |
## Typdefinitioner

| Typedef | Beskrivning |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Kontrollerar att **T1** är aritmetisk och **T2** är flyttal, eller tvärtom. I så fall sätts värdemedlemmen till true, annars är den false. |
| [AnyOfDecimal](./anyofdecimal/) | Kontrollerar att minst ett av typargumenten är [System::Decimal](../system/decimal/). I så fall sätts värdemedlemmen till true, annars är den false. |
| [IsArray](./isarray/) | Kontrollerar om typen är en [System::Array](../system/array/)-specialisering. I så fall sätts värdemedlemmen till true, annars till false. |
| [IsList](./islist/) | Kontrollerar om typen är en [System::Collections::Generic::List](../system.collections.generic/list/)-specialisering. I så fall sätts värdemedlemmen till true, annars till false. |
| [BothArrayOrList](./botharrayorlist/) | Kontrollerar om båda typargumenten är arrayer eller listor. I så fall sätts värdemedlemmen till true, annars till false. |
| [BothEnumerable](./bothenumerable/) | Kontrollerar om båda typargumenten är IEnumerable. I så fall sätts värdemedlemmen till true, annars till false. |