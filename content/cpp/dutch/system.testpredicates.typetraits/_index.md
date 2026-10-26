---
title: "System::TestPredicates::TypeTraits"
second_title: Aspose.Slides voor C++ API-referentie
description: 
type: docs
weight: 963
url: /nl/system.testpredicates.typetraits/
---
## Structuren

| Struct | Beschrijving |
| --- | --- |
| [has_data_method](./has_data_method/) | Controleert of een type de data()-methode heeft. Als dat het geval is, erft std::true_type, anders erft std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Specialisatie voor het BitArray-type die een boost-type levert dat daar niet toegankelijk is. |
| [has_print_to_method](./has_print_to_method/) | Controleert op een overload van de PrintTo-functie die het opgegeven type als eerste argument accepteert. Als een overload bestaat, erft std::true_type, anders erft std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Controleert of een specifiek type een STL-achtige container is. Daartoe wordt gecontroleerd of de lidtypen iterator en const_iterator bestaan. Als beide bestaan, erft std::true_type, anders erft std::false_type. |
| [IsEnumerable](./isenumerable/) | Controleert of een type een [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)-specialisatie heeft als basistype. Zo ja, wordt het value-lid op true gezet, anders op false. |
| [LargestFPType](./largestfptype/) | Biedt een alias voor het langste aanwezige floating-point-type. Negeert niet-floating-point-typen. |
## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Controleert of **T1** rekenkundig is en **T2** een floating-point-type, of omgekeerd. Zo ja, wordt het value-lid op true gezet, anders op false. |
| [AnyOfDecimal](./anyofdecimal/) | Controleert of ten minste één van de type-argumenten [System::Decimal](../system/decimal/) is. Zo ja, wordt het value-lid op true gezet, anders op false. |
| [IsArray](./isarray/) | Controleert of een type een [System::Array](../system/array/)-specialisatie is. Zo ja, wordt het value-lid op true gezet, anders op false. |
| [IsList](./islist/) | Controleert of een type een [System::Collections::Generic::List](../system.collections.generic/list/)-specialisatie is. Zo ja, wordt het value-lid op true gezet, anders op false. |
| [BothArrayOrList](./botharrayorlist/) | Controleert of beide type-argumenten arrays of lijsten zijn. Zo ja, wordt het value-lid op true gezet, anders op false. |
| [BothEnumerable](./bothenumerable/) | Controleert of beide type-argumenten IEnumerable zijn. Zo ja, wordt het value-lid op true gezet, anders op false. |