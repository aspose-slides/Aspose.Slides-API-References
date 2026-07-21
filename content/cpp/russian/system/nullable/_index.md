---
title: Nullable
second_title: Справочник API Aspose.Slides для C++
description: Объявление вперёд.
type: docs
weight: 1093
url: /ru/system/nullable/
---
## Nullable класс

Forward declaration.

```cpp
template<typename T>class Nullable
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип базового значения, который расширяется классом [Nullable](./) |

## Методы

| Метод | Описание |
| --- | --- |
| std::enable_if\<[IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [Equals](./equals/)(const T1\&) const | Определяет, равна ли величина, представляемая текущим объектом, величине, представляемой указанным объектом [Nullable](./). |
| **bool** [get_HasValue](./get_hasvalue/)() const | Определяет, представляет ли текущий объект какое-либо значение. |
| T [get_Value](./get_value/)() const | Возвращает копию значения, представленного текущим объектом. |
| int [GetHashCode](./gethashcode/)() const | Возвращает хеш-код текущего объекта. |
| T [GetValueOrDefault](./getvalueordefault/)(T) | Возвращает значение, представляемое текущим объектом, либо указанное значение, если значение, представляемое текущим объектом, равно null. |
| T [GetValueOrDefault](./getvalueordefault/)() |  |
| **bool** [IsNull](./isnull/)() const | Определяет, представляет ли текущий объект значение null. |
| [Nullable](./nullable/)() | Создаёт экземпляр, представляющий значение null. |
| [Nullable](./nullable/)(std::nullptr_t) | Создаёт экземпляр, представляющий null. |
| [Nullable](./nullable/)(const T1\&) | Создаёт экземпляр класса [Nullable](./), представляющий указанное значение, преобразованное (при необходимости) к типу базового значения T. |
| [Nullable](./nullable/)(const [Nullable](./)\<T1\>\&) | Создаёт экземпляр, представляющий значение, которое представлено указанным объектом [Nullable](./). Указанный nullable-объект может представлять значение другого типа, отличного от базового типа создаваемого экземпляра; в этом случае представляемое значение преобразуется к типу T. |
| **bool** [NullableBoolHelper](./nullableboolhelper/)(const T1\&, const std::function\<**bool**()>\&, **bool**) const | Вспомогательная функция для проверки, что **this** и **other** оба не null, и вызова лямбда-функции в этом случае. Используется в реализации. |
| [operator const T &](./operator_const_t__and/)() const | Возвращает константную ссылку на значение, представленное текущим объектом. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Определяет, не равно ли значение, представленное текущим объектом, null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator!=](./operator_not_equal/)(const T1\&) const | Определяет, не равно ли значение, представленное текущим объектом, указанному значению. |
| **bool** [operator!=](./operator_not_equal/)(const [Nullable](./)\<T1\>\&) const | Определяет, не равно ли значение, представленное текущим объектом, значению, представленному указанным объектом [Nullable](./). |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator&=](./operator_and_equal/)(**bool**) | Применяет [operator&=()](./operator_and_equal/) к значению, представленному текущим объектом, используя указанное значение в качестве аргумента справа. |
| [Nullable](./)\<T\> [operator+](./operator_plus/)(std::nullptr_t) const | Возвращает экземпляр класса Nullable<T>, созданный конструктором по умолчанию. |
| auto [operator+](./operator_plus/)(const T1\&) const | Суммирует nullable-и обычные значения. |
| auto [operator+](./operator_plus/)(const [Nullable](./)\<T1\>\&) const | Суммирует nullable-значения. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(std::nullptr_t) | Сбрасывает текущий объект, чтобы он представлял значение null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator+=](./operator_plus_equal/)(const T1\&) | Применяет [operator+=()](./operator_plus_equal/) к значению, представленному текущим объектом, используя указанное значение в качестве аргумента справа. |
| [Nullable](./)\<T\> [operator+=](./operator_plus_equal/)(const [Nullable](./)\<T1\>\&) | Применяет [operator+=()](./operator_plus_equal/) к значению, представленному текущим объектом, используя значение, представленное указанным объектом [Nullable](./), в качестве аргумента справа. |
| [Nullable](./)\<T\> [operator-](./operator_minus/)(T1) const | Вычитает nullable-значения и значения, указывающие на null. |
| auto [operator-](./operator_minus/)(const T1\&) const | Вычитает nullable-и обычные значения. |
| auto [operator-](./operator_minus/)(const [Nullable](./)\<T1\>\&) const | Вычитает nullable-значения. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(T1) | Возвращает экземпляр класса [Nullable](./), представляющий значение null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, [Nullable](./)\<T\>\>::type [operator-=](./operator_minus_equal/)(const T1\&) | Применяет [operator-=()](./operator_minus_equal/) к значению, представленному текущим объектом, используя указанное значение в качестве аргумента справа. |
| [Nullable](./)\<T\> [operator-=](./operator_minus_equal/)(const [Nullable](./)\<T1\>\&) | Применяет [operator-=()](./operator_minus_equal/) к значению, представленному текущим объектом, используя значение, представленное указанным объектом [Nullable](./), в качестве аргумента справа. |
| **bool** [operator<](./operator_less/)(std::nullptr_t) const | Всегда возвращает false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<](./operator_less/)(const T1\&) const | Определяет, меньше ли значение, представленное текущим объектом, указанного значения, применяя [operator<()](./operator_less/) к этим значениям. |
| **bool** [operator<](./operator_less/)(const [Nullable](./)\<T1\>\&) const | Определяет, меньше ли значение, представленное текущим объектом, значение, представленное указанным объектом [Nullable](./), применяя [operator<()](./operator_less/) к этим значениям. |
| **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const | Всегда возвращает false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator<=](./operator_less_equal/)(const T1\&) const | Определяет, меньше ли или равно значение, представленное текущим объектом, указанному значению, применяя [operator<=()](./operator_less_equal/) к этим значениям. |
| **bool** [operator<=](./operator_less_equal/)(const [Nullable](./)\<T1\>\&) const | Определяет, меньше ли или равно значение, представленное текущим объектом, значение, представленное указанным объектом [Nullable](./), применяя [operator<=()](./operator_less_equal/) к этим значениям. |
| [Nullable](./)\<T\> [operator=](./operator_equal/)(std::nullptr_t) | Присваивает null текущему объекту. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value\&&\!std::is_null_pointer\<T1\>::value, [Nullable](./)\<T\>\&\>::type [operator=](./operator_equal/)(const T1\&) | Заменяет текущее представленное объектом значение указанным значением. |
| [Nullable](./)\<T\>\& [operator=](./operator_equal/)(const [Nullable](./)\<T1\>\&) | Заменяет текущее представленное объектом значение указанным значением. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Определяет, равно ли значение, представленное текущим объектом, null. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator==](./operator_equal_equal/)(const T1\&) const | Определяет, равно ли значение, представленное текущим объектом, указанному значению. |
| **bool** [operator==](./operator_equal_equal/)(const [Nullable](./)\<T1\>\&) const | Определяет, равно ли значение, представленное текущим объектом, значению, представленному указанным объектом [Nullable](./). |
| **bool** [operator>](./operator_greater/)(std::nullptr_t) const | Всегда возвращает false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>](./operator_greater/)(const T1\&) const | Определяет, больше ли значение, представленное текущим объектом, указанного значения, применяя [operator>()](./operator_greater/) к этим значениям. |
| **bool** [operator>](./operator_greater/)(const [Nullable](./)\<T1\>\&) const | Определяет, больше ли значение, представленное текущим объектом, значение, представленное указанным объектом [Nullable](./), применяя [operator>()](./operator_greater/) к этим значениям. |
| **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const | Всегда возвращает false. |
| std::enable_if<\![IsNullable](../isnullable/)\<T1\>::value, **bool**\>::type [operator>=](./operator_greater_equal/)(const T1\&) const | Определяет, больше ли или равно значение, представленное текущим объектом, значение, представленное указанным объектом, применяя [operator>=()](./operator_greater_equal/) к этим значениям. |
| **bool** [operator>=](./operator_greater_equal/)(const [Nullable](./)\<T1\>\&) const | Определяет, больше ли или равно значение, представленное текущим объектом, значение, представленное указанным объектом [Nullable](./), применяя [operator>=()](./operator_greater_equal/) к этим значениям. |
| std::enable_if\<std::is_same\<T1, **bool**\>::value, [Nullable](./)\<T\>\>::type [operator|=](./operator_or_equal/)(**bool**) | Применяет [operator|=()](./operator_or_equal/) к значению, представленному текущим объектом, используя указанное значение в качестве аргумента справа. |
| void [reset](./reset/)() | Устанавливает текущее представленное значение в null. |
| void [set_Value](./set_value/)(const T\&) | Устанавливает новое значение nullable-объекта. |
| [String](../string/) [ToString](./tostring/)() const | Преобразует значение, представленное текущим объектом, в строку. |

## Типы

| Тип | Описание |
| --- | --- |
| [ValueType](./valuetype/) | Псевдоним типа значения, представленного этим классом. |

## Замечания

Представляет значение указанного типа, которому может быть присвоено null. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

## См. также

* Пространство имен [System](../)
* Библиотека [Aspose.Slides](../../)