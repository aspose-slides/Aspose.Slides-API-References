---
title: "System::BoxedValueDetail"
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 287
url: /ru/system.boxedvaluedetail/
---
## Классы

| Класс | Описание |
| --- | --- |
| [Comparable](./comparable/) | Простая реализация IComparable<> |
| [NonComparable](./noncomparable/) | Фиктивный базовый тип для упакованных типов, которые не реализуют IComparable<> |

## Структуры

| Структура | Описание |
| --- | --- |
| [ImplementsInterface](./implementsinterface/) | Шаблонный предикат, проверяющий, должен ли упакованный объект самостоятельно реализовать заданный интерфейс. |
| [ImplementsInterface< String, IComparable< String > >](./implementsinterface_tmpl_string__icomparable_tmpl_string__end_tmpl__end_tmpl/) | [String](../system/string/) реализует [IComparable](../system/icomparable/). |
| [ImplementsInterface< T, IComparable< T > >](./implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/) | Шаблонный предикат, проверяющий, должен ли упакованный объект самостоятельно реализовать интерфейс [IComparable](../system/icomparable/). |

## Функции

| Функция | Описание |
| --- | --- |
| std::enable_if\<detail::has_operator_equal\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Определяет равенство указанного значения с использованием [operator==()](../system/operator_equal_equal/). |
| std::enable_if\<detail::has_only_method_equals\<T\>::value, **bool**\>::type [Equals](./equals/)(T, T) | Определяет равенство указанного значения с использованием метода [System::Object::Equals()](../system/object/equals/). |
| **bool** [Equals< float >](./equals_less_float__greater/)(**float**, **float**) | Сравнивает два значения одинарной точности с плавающей запятой. |
| **bool** [Equals< double >](./equals_less_double__greater/)(**double**, **double**) | Сравнивает два значения двойной точности с плавающей запятой. |