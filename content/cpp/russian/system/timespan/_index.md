---
title: TimeSpan
second_title: Справочник API Aspose.Slides для C++
description: "Представляет интервал времени. Этот тип следует выделять в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 1288
url: /ru/system/timespan/
---
## Класс TimeSpan

Представляет интервал времени. Этот тип должен выделяться в стеке и передаваться в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class TimeSpan
```

## Методы

| Метод | Описание |
| --- | --- |
| [TimeSpan](./) [Add](./add/)([TimeSpan](./)) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, который является суммой интервалов времени, представленных текущим и указанными объектами. |
| static constexpr int [Compare](./compare/)([TimeSpan](./), [TimeSpan](./)) | Сравнивает два объекта [TimeSpan](./). |
| constexpr int [CompareTo](./compareto/)([TimeSpan](./)) const | Сравнивает текущий объект и указанный объект. |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Сравнивает текущий объект и указанный объект. |
| [TimeSpan](./) [Duration](./duration/)() const | Возвращает новый объект [TimeSpan](./), значение которого является абсолютным значением текущего объекта. |
| constexpr **bool** [Equals](./equals/)([TimeSpan](./)) const | Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| static constexpr **bool** [Equals](./equals/)([TimeSpan](./), [TimeSpan](./)) | Возвращает true, если указанные объекты представляют один и тот же интервал времени, иначе — false. |
| static [TimeSpan](./) [FromDays](./fromdays/)(**double**) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [TimeSpan](./) [FromHours](./fromhours/)(**double**) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [TimeSpan](./) [FromMilliseconds](./frommilliseconds/)(**double**) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [TimeSpan](./) [FromMinutes](./fromminutes/)(**double**) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static [TimeSpan](./) [FromSeconds](./fromseconds/)(**double**) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| static constexpr [TimeSpan](./) [FromTicks](./fromticks/)(**int64_t**) | Возвращает новый объект [TimeSpan](./), представляющий указанный интервал. |
| constexpr int [get_Days](./get_days/)() const | Возвращает компонент дней интервала времени, представленного текущим объектом [TimeSpan](./). |
| constexpr int [get_Hours](./get_hours/)() const | Возвращает компонент часов интервала времени, представленного текущим объектом [TimeSpan](./). |
| constexpr int [get_Milliseconds](./get_milliseconds/)() const | Возвращает компонент миллисекунд интервала времени, представленного текущим объектом [TimeSpan](./). |
| constexpr int [get_Minutes](./get_minutes/)() const | Возвращает компонент минут интервала времени, представленного текущим объектом [TimeSpan](./). |
| constexpr int [get_Seconds](./get_seconds/)() const | Возвращает компонент секунд интервала времени, представленного текущим объектом [TimeSpan](./). |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Возвращает количество интервалов по 100 наносекунд, составляющих интервал времени, представленный текущим объектом [TimeSpan](./). |
| constexpr **double** [get_TotalDays](./get_totaldays/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных днях. |
| constexpr **double** [get_TotalHours](./get_totalhours/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных часах. |
| **double** [get_TotalMilliseconds](./get_totalmilliseconds/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных миллисекундах. |
| constexpr **double** [get_TotalMinutes](./get_totalminutes/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных минутах. |
| constexpr **double** [get_TotalSeconds](./get_totalseconds/)() const | Возвращает значение текущего объекта [TimeSpan](./), выраженное в полных и дробных секундах. |
| int [GetHashCode](./gethashcode/)() const | Возвращает хэш-код текущего объекта. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| [TimeSpan](./) [Negate](./negate/)() const | Возвращает новый объект [TimeSpan](./), представляющий отрицательное значение текущего объекта [TimeSpan](./). |
| constexpr **bool** [operator!=](./operator_not_equal/)([TimeSpan](./)) const | Определяет, не равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [TimeSpan](./) [operator+](./operator_plus/)([TimeSpan](./)) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, который является суммой интервалов, представленных текущим и указанными объектами. |
| [TimeSpan](./) [operator+](./operator_plus/)() const | Возвращает себя. |
| [TimeSpan](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](./)) | Присваивает текущему объекту интервал времени, являющийся суммой интервала, представленного текущим объектом, и указанного объекта. |
| [TimeSpan](./) [operator-](./operator_minus/)([TimeSpan](./)) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, полученный вычитанием интервала, представленного указанным объектом, из интервала, представленного текущим объектом. |
| [TimeSpan](./) [operator-](./operator_minus/)() const | Возвращает новый объект [TimeSpan](./), представляющий отрицательное значение текущего объекта [TimeSpan](./). |
| [TimeSpan](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](./)) | Присваивает текущему объекту интервал времени, полученный вычитанием интервала, представленного указанным объектом, из интервала, представленного текущим объектом. |
| [TimeSpan](./) [operator/](./operator_div/)(**double**) const |  |
| constexpr **double** [operator/](./operator_div/)([TimeSpan](./)) const |  |
| [TimeSpan](./)\& [operator/=](./operator_div_equal/)(**double**) |  |
| constexpr **bool** [operator<](./operator_less/)([TimeSpan](./)) const | Определяет, короче ли интервал времени, представленный текущим объектом, чем интервал времени, представленный указанным объектом. |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([TimeSpan](./)) const | Определяет, короче ли или равен интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| constexpr [TimeSpan](./)\& [operator=](./operator_equal/)(const [TimeSpan](./)\&) | Устанавливает интервал времени, представленный указанным объектом [TimeSpan](./), в текущий объект [TimeSpan](./). |
| constexpr **bool** [operator==](./operator_equal_equal/)([TimeSpan](./)) const | Определяет, равен ли интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([TimeSpan](./)) const | Определяет, длиннее ли интервал времени, представленный текущим объектом, интервал времени, представленный указанным объектом. |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([TimeSpan](./)) const | Определяет, длиннее ли или равен интервал времени, представленный текущим объектом, интервалу времени, представленного указанным объектом. |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&) | Преобразует строку в эквивалентный объект [TimeSpan](./). |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанного поставщика формата. |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) |  |
| static [TimeSpan](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанных форматов, поставщика формата и стилей. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанного формата, поставщика формата и стилей. |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| static [TimeSpan](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/)) |  |
| [TimeSpan](./) [Subtract](./subtract/)([TimeSpan](./)) const | Возвращает новый экземпляр класса [TimeSpan](./), представляющий интервал времени, полученный вычитанием интервала, представленного указанным объектом, из интервала, представленного текущим объектом. |
| constexpr [TimeSpan](./timespan/)() | Создаёт объект [TimeSpan](./), представляющий нулевой интервал времени. |
| explicit constexpr [TimeSpan](./timespan/)(**int64_t**) | Создаёт экземпляр класса [TimeSpan](./), представляющий указанный интервал времени. |
| [TimeSpan](./timespan/)(int, int, int) | Создаёт экземпляр класса [TimeSpan](./), представляющий интервал времени, равный сумме указанного количества часов, минут и секунд. |
| [TimeSpan](./timespan/)(int, int, int, int, int) | Создаёт экземпляр класса [TimeSpan](./), представляющий интервал времени, равный сумме указанного количества часов, минут, секунд и миллисекунд. |
| constexpr [TimeSpan](./timespan/)(const [TimeSpan](./)\&) | Создаёт объект [TimeSpan](./), представляющий интервал времени, равный интервалу, представленного указанным объектом [TimeSpan](./). |
| [String](../string/) [ToString](./tostring/)() const | Возвращает строковое представление интервала времени, представленного текущим объектом. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Преобразует значение текущего объекта в эквивалентное строковое представление, используя указанный формат. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Преобразует значение текущего объекта в эквивалентное строковое представление, используя указанный формат и поставщик формата. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [TimeSpan](./)\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) и возвращает результат преобразования. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанного поставщика формата и возвращает результат преобразования. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанных форматов и поставщика формата, и возвращает результат преобразования. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанного формата, поставщика формата и стилей, и возвращает результат преобразования. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанных форматов, поставщика формата и стилей, и возвращает результат преобразования. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::TimeSpanStyles](../../system.globalization/timespanstyles/), [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [TimeSpan](./)\&) | Преобразует строку в эквивалентный объект [TimeSpan](./) с использованием указанного формата и поставщика формата, и возвращает результат преобразования. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [TimeSpan](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [TimeSpan](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Возвращает объект [TypeInfo](../typeinfo/), представляющий структуру [TimeSpan](./). |

## Поля

| Поле | Описание |
| --- | --- |
| static [MaxValue](./maxvalue/) | Объект [TimeSpan](./), представляющий самый длинный возможный интервал. |
| static [MinValue](./minvalue/) | /// Объект [TimeSpan](./), представляющий самый короткий возможный интервал. |
| static constexpr [TicksPerDay](./ticksperday/) | Количество интервалов по 100 наносекунд в дне (24-часовом интервале). |
| static constexpr [TicksPerHour](./ticksperhour/) | Количество интервалов по 100 наносекунд в часе. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Количество интервалов по 100 наносекунд в миллисекунде. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Количество интервалов по 100 наносекунд в минуте. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Количество интервалов по 100 наносекунд в секунде. |
| static [Zero](./zero/) | Объект [TimeSpan](./), представляющий нулевой интервал. |

## Замечания



```cpp
#include "system/datetime.h"
#include "system/timespan.h"
#include <iostream>

int main()
{
  const auto date1 = System::DateTime(2021, 01, 01);
  const auto date2 = System::DateTime(2021, 10, 30);

  const auto interval = date2 - date1;

  std::cout << "Number of ticks: " << interval.get_Ticks() << std::endl;
  std::cout << "Number of milliseconds: " << interval.get_Milliseconds() << std::endl;
  std::cout << "Total number of milliseconds: " << interval.get_TotalMilliseconds() << std::endl;
  std::cout << "Number of minutes: " << interval.get_Minutes() << std::endl;
  std::cout << "Total number of minutes: " << interval.get_TotalMinutes() << std::endl;
  std::cout << "Number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Total number of hours: " << interval.get_Hours() << std::endl;
  std::cout << "Number of days: " << interval.get_Days() << std::endl;
  std::cout << "Total number of days: " << interval.get_TotalDays() << std::endl;

  return 0;
}
/*
Этот пример кода выводит следующее:
Количество тактов: 260928000000000
Количество миллисекунд: 0
Общее количество миллисекунд: 2.60928e+10
Количество минут: 0
Общее количество минут: 434880
Количество часов: 0
Общее количество часов: 0
Количество дней: 302
Общее количество дней: 302
*/
```

## См. также

* Namespace [System](../)
* Library [Aspose.Slides](../../)