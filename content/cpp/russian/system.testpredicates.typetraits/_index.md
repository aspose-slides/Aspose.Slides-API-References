---
title: "System::TestPredicates::TypeTraits"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 963
url: /ru/system.testpredicates.typetraits/
---
## Structures

| Структура | Описание |
| --- | --- |
| [has_data_method](./has_data_method/) | Проверяет, имеет ли тип метод data(). Если да, наследует std::true_type, иначе наследует std::false_type. |
| [has_data_method< System::Collections::BitArray, void >](./has_data_method_tmpl_system_collections_bitarray__void__end_tmpl/) | Специализация для типа BitArray, который предоставляет тип boost, недоступный там. |
| [has_print_to_method](./has_print_to_method/) | Проверяет наличие перегрузки функции PrintTo, принимающей данный тип в качестве первого аргумента. Если перегрузка существует, наследует std::true_type, иначе наследует std::false_type. |
| [IsCppContainer](./iscppcontainer/) | Проверяет, является ли конкретный тип контейнером в стиле STL. Для этого проверяется наличие типов-членов iterator и const_iterator. Если оба существуют, наследует std::true_type, иначе наследует std::false_type. |
| [IsEnumerable](./isenumerable/) | Проверяет, имеет ли тип специализацию [System::Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/) в качестве базового типа. Если да, член value устанавливается в true, иначе — в false. |
| [LargestFPType](./largestfptype/) | Предоставляет псевдоним для самого длинного предоставленного типа с плавающей точкой. Игнорирует типы, не являющиеся плавающей точкой. |
## Типы

| Тип | Описание |
| --- | --- |
| [AreFPandArithmetic](./arefpandarithmetic/) | Проверяет, что **T1** является арифметическим, а **T2** — типом с плавающей точкой, или наоборот. Если да, устанавливает член value в true, иначе — false. |
| [AnyOfDecimal](./anyofdecimal/) | Проверяет, что хотя бы один из типовых аргументов является [System::Decimal](../system/decimal/). Если да, устанавливает член value в true, иначе — false. |
| [IsArray](./isarray/) | Проверяет, является ли тип специализацией [System::Array](../system/array/). Если да, член value устанавливается в true, иначе — в false. |
| [IsList](./islist/) | Проверяет, является ли тип специализацией [System::Collections::Generic::List](../system.collections.generic/list/). Если да, член value устанавливается в true, иначе — в false. |
| [BothArrayOrList](./botharrayorlist/) | Проверяет, являются ли оба типовых аргумента массивами или списками. Если да, член value устанавливается в true, иначе — в false. |
| [BothEnumerable](./bothenumerable/) | Проверяет, являются ли оба типовых аргумента IEnumerable. Если да, член value устанавливается в true, иначе — в false. |