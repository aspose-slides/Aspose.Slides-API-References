---
title: ComparerType
second_title: Aspose.Slides для C++ справочника API
description: Сравнивает элементы, используя семантику 'less'.
type: docs
weight: 144
url: /ru/system.collections.generic.details/comparertype/
---
## ComparerType структура

Сравнивает элементы, используя семантику «less».

```cpp
template<typename T>class ComparerType
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип сравниваемых элементов. |

## Методы

| Метод | Описание |
| --- | --- |
| std::enable_if\<std::is_base_of\<[System::IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Сравнивает типы значений, реализующие интерфейс [IComparable](../../system/icomparable/). |
| std::enable_if<\!(std::is_base_of\<[IComparable](../../system/icomparable/)\<Q\>, Q\>::value||[has_method_compareto](../has_method_compareto/)\<Q\>::value)&&\!std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Сравнивает примитивные типы значений и объекты, не реализующие интерфейс [IComparable](../../system/icomparable/). |
| std::enable_if\<std::is_floating_point\<Q\>::value, **bool**\>::type [operator()](./operator_call/)(const Q\&, const Q\&) const | Сравнивает типы с плавающей точкой. |

## См. также

* Пространство имён [System::Collections::Generic::Details](../)
* Библиотека [Aspose.Slides](../../)