---
title: Decimal
second_title: Справочник API Aspose.Slides для C++
description: "Представляет десятичное число. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 261
url: /ru/system/decimal/
---
## Decimal класс

Представляет десятичное число. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class Decimal
```

## Методы

| Method | Описание |
| --- | --- |
| static [Decimal](./) [Add](./add/)(const [Decimal](./)\&, const [Decimal](./)\&) | Добавляет два указанных значения [Decimal](./). |
| static [Decimal](./) [Ceiling](./ceiling/)(const [Decimal](./)\&) | Возвращает наименьшее целое значение, которое больше либо равно указанному значению. |
| static int [Compare](./compare/)(const [Decimal](./)\&, const [Decimal](./)\&) | Определяет, меньше ли значение, представляемое первым объектом [Decimal](./), равно ли оно или больше значения, представляемого вторым объектом [Decimal](./). |
| int [CompareTo](./compareto/)(const [Decimal](./)\&) const | Определяет, меньше ли значение, представляемое текущим объектом, равно ли оно или больше значения, представленного указанным объектом. |
| [Decimal](./decimal/)() | Создаёт экземпляр, представляющий 0. |
| [Decimal](./decimal/)(std::int8_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::int16_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::int32_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::int64_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint8_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint16_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint32_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(std::uint64_t) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(**float**) | Создаёт экземпляр, представляющий указанное значение. |
| [Decimal](./decimal/)(**double**) | Создаёт экземпляр, представляющий указанное значение. |
| explicit [Decimal](./decimal/)(const std::string\&) | Создаёт экземпляр, представляющий значение, строковое представление которого указано как объект класса std::string. |
| [Decimal](./decimal/)(**int32_t**, **int32_t**, **int32_t**, **bool**, **uint8_t**) | Создаёт объект [Decimal](./) из указанных компонентов. |
| [Decimal](./decimal/)(const [Decimal](./)\&) | Создаёт экземпляр класса [Decimal](./), представляющий то же число, что и указанный объект [Decimal](./). |
| [Decimal](./decimal/)(const [ArrayPtr](../arrayptr/)\<**int32_t**\>\&) | Создаёт экземпляр класса [Decimal](./) из массива целых чисел, содержащего двоичное представление. |
| [Decimal](./decimal/)(std::nullptr_t) | Всегда генерирует ArgumentNullException. |
| [Decimal](./decimal/)(const [number_type](./number_type/)\&) | Создаёт экземпляр класса [Decimal](./), представляющий указанное значение. |
| static [Decimal](./) [Divide](./divide/)(const [Decimal](./)\&, const [Decimal](./)\&) | Делит два указанных значения [Decimal](./). |
| **bool** [Equals](./equals/)(const [Decimal](./)\&) const | Определяет, равны ли значения, представленные текущим объектом и указанным объектом. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Определяет, равны ли значения, представленные текущим объектом и указанным объектом. |
| static **bool** [Equals](./equals/)(const [Decimal](./)\&, const [Decimal](./)\&) | Определяет, равны ли значения, представленные указанными объектами. |
| static [Decimal](./) [Floor](./floor/)(const [Decimal](./)\&) | Возвращает наибольшее целое значение, которое меньше или равно указанному значению. |
| static [Decimal](./) [FromOACurrency](./fromoacurrency/)(**int64_t**) | [Convert](../convert/) указанное значение валюты OLE в эквивалентное значение [Decimal](./). НЕ РЕАЛИЗОВАНО. |
| static [System::ArrayPtr](../arrayptr/)\<int\> [GetBits](./getbits/)(const [Decimal](./)\&) | Преобразует указанный объект [Decimal](./) в двоичное представление его значения. |
| static void [GetBytes](./getbytes/)(const [Decimal](./)\&, const [System::ArrayPtr](../arrayptr/)\<**uint8_t**\>\&) | [Convert](../convert/) указанное значение [Decimal](./) в массив байтов. |
| int [GetHashCode](./gethashcode/)() const | Возвращает хеш-код текущего объекта. |
| [TypeCode](../typecode/) [GetTypeCode](./gettypecode/)() const | Получает код типа объекта. |
| static [Decimal](./) [Multiply](./multiply/)(const [Decimal](./)\&, const [Decimal](./)\&) | Умножает два указанных значения [Decimal](./). |
| static [Decimal](./) [Negate](./negate/)(const [Decimal](./)\&) | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате отрицания значения, представленного указанным объектом. |
| explicit [operator bool](./operator_bool/)() const | Преобразует значение, представляемое текущим объектом, в логическое значение. |
| explicit [operator double](./operator_double/)() const | Преобразует значение, представляемое текущим объектом, в число двойной точности с плавающей точкой. |
| explicit [operator float](./operator_float/)() const | Преобразует значение, представляемое текущим объектом, в число одинарной точности с плавающей точкой. |
| **bool** [operator!=](./operator_not_equal/)(const [Decimal](./)\&) const | Определяет, не равны ли значения, представленные текущим объектом и указанным объектом. |
| **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const | Определяет, отличается ли значение, представляемое текущим объектом, от 0. |
| [Decimal](./) [operator%](./operator%/)(const [Decimal](./)\&) const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате операции взятия остатка от деления значений, представленных текущим и указанным объектами. |
| [Decimal](./)\& [operator%=](./operator%_equal/)(const [Decimal](./)\&) | Присваивает текущему объекту новое значение, полученное в результате операции взятия остатка от деления значений, представленных текущим и указанным объектами. |
| [Decimal](./) [operator*](./operator_star/)(const [Decimal](./)\&) const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате умножения значений, представленных текущим и указанным объектами. |
| [Decimal](./)\& [operator*=](./operator_star_equal/)(const [Decimal](./)\&) | Присваивает текущему объекту новое значение, полученное в результате умножения значений, представленных текущим и указанным объектами. |
| [Decimal](./) [operator+](./operator_plus/)(const [Decimal](./)\&) const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате сложения значений, представленных текущим и указанным объектами. |
| [Decimal](./)\& [operator++](./operator_plus_plus/)() | Увеличивает значение, представляемое текущим объектом. |
| [Decimal](./)\& [operator+=](./operator_plus_equal/)(const [Decimal](./)\&) | Присваивает текущему объекту новое значение, полученное в результате сложения значений, представленных текущим и указанным объектами. |
| [Decimal](./) [operator-](./operator_minus/)(const [Decimal](./)\&) const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате вычитания значения, представленного указанным объектом, из значения, представленного текущим объектом. |
| [Decimal](./) [operator-](./operator_minus/)() const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате отрицания значения, представленного текущим объектом. |
| [Decimal](./)\& [operator--](./operator_minus_minus/)() | Уменьшает значение, представляемое текущим объектом. |
| [Decimal](./)\& [operator-=](./operator_minus_equal/)(const [Decimal](./)\&) | Присваивает текущему объекту новое значение, полученное в результате вычитания значения, представленное указанным объектом, из значения, представленного текущим объектом. |
| [Decimal](./) [operator/](./operator_div/)(const [Decimal](./)\&) const | Возвращает новый экземпляр класса [Decimal](./), представляющий значение, полученное в результате деления значения, представленного текущим объектом, на значение, представляемое указанным объектом. |
| [Decimal](./)\& [operator/=](./operator_div_equal/)(const [Decimal](./)\&) | Присваивает текущему объекту новое значение, полученное в результате деления значения, представленного текущим объектом, на значение, представляемое указанным объектом. |
| **bool** [operator<](./operator_less/)(const [Decimal](./)\&) const | Определяет, меньше ли значение, представляемое текущим объектом, чем значение, представляемое указанным объектом. |
| **bool** [operator<=](./operator_less_equal/)(const [Decimal](./)\&) const | Определяет, меньше ли или равно значение, представляемое текущим объектом, значению, представляемому указанным объектом. |
| [Decimal](./)\& [operator=](./operator_equal/)(const [Decimal](./)\&) | Присваивает значение, представленное указанным объектом, текущему объекту. |
| **bool** [operator==](./operator_equal_equal/)(const [Decimal](./)\&) const | Определяет, равны ли значения, представленные текущим объектом и указанным объектом. |
| **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const | Определяет, равно ли значение, представляемое текущим объектом, 0. |
| **bool** [operator>](./operator_greater/)(const [Decimal](./)\&) const | Определяет, больше ли значение, представляемое текущим объектом, чем значение, представляемое указанным объектом. |
| **bool** [operator>=](./operator_greater_equal/)(const [Decimal](./)\&) const | Определяет, больше ли или равно значение, представляемое текущим объектом, значению, представляемому указанным объектом. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./). |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/)) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./) с использованием указанного стиля. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./) с использованием указанного поставщика формата. |
| static [Decimal](./) [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует строковое представление десятичного числа в эквивалентный экземпляр класса [Decimal](./) с использованием указанного стиля и поставщика формата. |
| static [Decimal](./) [Remainder](./remainder/)(const [Decimal](./)\&, const [Decimal](./)\&) | Вычисляет остаток от деления двух значений [Decimal](./). |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, [MidpointRounding](../midpointrounding/)) | Округляет указанное значение до ближайшего целого числа. Параметр определяет поведение функции, если указанное значение одинаково близко к двум ближайшим целым. |
| static [Decimal](./) [Round](./round/)(const [Decimal](./)\&, int, [MidpointRounding](../midpointrounding/)) | Округляет указанное значение до ближайшего значения с заданным числом десятичных знаков. Параметр определяет поведение функции, если указанное значение одинаково близко к двум ближайшим числам. |
| static [Decimal](./) [Subtract](./subtract/)(const [Decimal](./)\&, const [Decimal](./)\&) | Вычитает одно указанное значение [Decimal](./) из другого. |
| static **uint8_t** [ToByte](./tobyte/)([Decimal](./)) | Преобразует значение [Decimal](./) в беззнаковое 8-битное целое. |
| static **double** [ToDouble](./todouble/)([Decimal](./)) | Преобразует значение [Decimal](./) в число двойной точности. |
| static **int16_t** [ToInt16](./toint16/)([Decimal](./)) | Преобразует значение [Decimal](./) в знаковое 16-битное целое. |
| static **int32_t** [ToInt32](./toint32/)([Decimal](./)) | Преобразует значение [Decimal](./) в знаковое 32-битное целое. |
| static **int64_t** [ToInt64](./toint64/)([Decimal](./)) | Преобразует значение [Decimal](./) в знаковое 64-битное целое. |
| static **int64_t** [ToOACurrency](./tooacurrency/)(const [Decimal](./)\&) | [Convert](../convert/) указанное значение [Decimal](./) в эквивалентное значение валюты OLE. НЕ РЕАЛИЗОВАНО. |
| static **int8_t** [ToSByte](./tosbyte/)([Decimal](./)) | Преобразует значение [Decimal](./) в знаковое 8-битное целое. |
| static **float** [ToSingle](./tosingle/)([Decimal](./)) | Преобразует значение [Decimal](./) в число одинарной точности. |
| std::string [ToStdString](./tostdstring/)() const | Возвращает экземпляр std::string, содержащий строковое представление значения, представленного объектом. |
| [String](../string/) [ToString](./tostring/)() const | Возвращает строковое представление значения, представленного объектом. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Преобразует текущий объект в строку, используя сведения о формате, специфичные для культуры. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [Decimal](./)\&, std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Преобразует текущий объект в его строковое представление, используя указанный строковый формат и сведения о формате, специфичные для культуры, предоставленные указанным объектом [IFormatProvider](../iformatprovider/). |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [String](../string/) [ToStringInternal](./tostringinternal/)() const | Возвращает строковое представление значения, представленного объектом. Для внутреннего использования. |
| static **uint16_t** [ToUInt16](./touint16/)([Decimal](./)) | Преобразует значение [Decimal](./) в беззнаковое 16-битное целое. |
| static **uint32_t** [ToUInt32](./touint32/)([Decimal](./)) | Преобразует значение [Decimal](./) в беззнаковое 32-битное целое. |
| static **uint64_t** [ToUInt64](./touint64/)([Decimal](./)) | Преобразует значение [Decimal](./) в беззнаковое 64-битное целое. |
| static [Decimal](./) [Truncate](./truncate/)(const [Decimal](./)\&) | Возвращает объект [Decimal](./), представляющий значение, у которого целая часть равна целой части значения, представленного указанным объектом [Decimal](./), при этом отбрасываются все дробные цифры. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Decimal](./)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Decimal](./)\&) | Преобразует указанную строку, содержащую строковое представление числа, в эквивалентное значение [Decimal](./) с использованием предоставленной информации о формате и стиля числа. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Возвращает ссылку на объект [TypeInfo](../typeinfo/), представляющий информацию о типе класса [Decimal](./). |
| [~Decimal](./~decimal/)() | Деструктор. |

## Поля

| Поле | Описание |
| --- | --- |
| static [MaxValue](./maxvalue/) | Представляет наибольшее число, которое может быть представлено классом [Decimal](./). |
| static [MinusOne](./minusone/) | Представляет число -1. |
| static [MinValue](./minvalue/) | Представляет наименьшее число, которое может быть представлено классом [Decimal](./). |
| static [One](./one/) | Представляет число 1. |
| static [Zero](./zero/) | Представляет число 0. |

## Псевдоним

| Псевдоним | Описание |
| --- | --- |
| [number_type](./number_type/) | Псевдоним для Detail::decimal_number_type. |

## Замечания



```cpp
#include "system/console.h"
#include "system/decimal.h"

int main()
{
  using namespace System;

  Console::WriteLine(Decimal::MinValue);
  Console::WriteLine(Decimal::MaxValue);

  auto dividend = Decimal::One;
  auto divisor = 6;
  Console::WriteLine(dividend/divisor);

  return 0;
}
/*
Этот пример кода выводит следующий результат:
- 79228162514264337593543950335
79228162514264337593543950335
0,1666666666666666666666666667
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)