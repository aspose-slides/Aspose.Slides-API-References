---
title: DateTimeOffset
second_title: Справочник API Aspose.Slides для C++
description: "Содержит дату и время суток относительно Всемирного координированного времени. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 235
url: /ru/system/datetimeoffset/
---
## DateTimeOffset класс

Содержит дату и время суток относительно Всемирного координированного времени. Объекты этого класса следует создавать только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью operator new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class DateTimeOffset
```

## Методы

| Метод | Описание |
| --- | --- |
| [DateTimeOffset](./) [Add](./add/)([TimeSpan](../timespan/)) const | Добавляет указанный интервал времени к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddDays](./adddays/)(**double**) const | Добавляет указанное количество дней к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddHours](./addhours/)(**double**) const | Добавляет указанное количество часов к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Добавляет указанное количество миллисекунд к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMinutes](./addminutes/)(**double**) const | Добавляет указанное количество минут к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddMonths](./addmonths/)(int) const | Добавляет указанное количество месяцев к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddSeconds](./addseconds/)(**double**) const | Добавляет указанное количество секунд к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddTicks](./addticks/)(**int64_t**) const | Добавляет указанное количество тактов к объекту [DateTimeOffset](./). |
| [DateTimeOffset](./) [AddYears](./addyears/)(int) const | Добавляет указанное количество лет к объекту [DateTimeOffset](./). |
| static int [Compare](./compare/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Сравнивает два объекта [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [DateTimeOffset](./)\&) const | Сравнивает два объекта [DateTimeOffset](./). |
| int [CompareTo](./compareto/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Сравнивает два объекта [DateTimeOffset](./). |
| constexpr [DateTimeOffset](./datetimeoffset/)() | Конструктор по умолчанию. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/)) | Конструктор. |
|  [DateTimeOffset](./datetimeoffset/)(**int64_t**, [TimeSpan](../timespan/)) | Конструктор. |
|  [DateTimeOffset](./datetimeoffset/)([DateTime](../datetime/), [TimeSpan](../timespan/)) | Конструктор. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, [TimeSpan](../timespan/)) | Конструктор. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, [TimeSpan](../timespan/)) | Конструктор. |
|  [DateTimeOffset](./datetimeoffset/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [TimeSpan](../timespan/)) | Конструктор. |
| static **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&, const [DateTimeOffset](./)\&) | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени. |
| **bool** [Equals](./equals/)(const [DateTimeOffset](./)\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени. |
| **bool** [Equals](./equals/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени. |
| **bool** [EqualsExact](./equalsexact/)(const [DateTimeOffset](./)\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени и имеют одинаковое смещение. |
| **bool** [EqualsExact](./equalsexact/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) const | Проверяет, представляют ли два объекта [DateTimeOffset](./) одну и ту же точку времени и имеют одинаковое смещение. |
| static [DateTimeOffset](./) [FromFileTime](./fromfiletime/)(**int64_t**) | [Convert](../convert/)[Windows](../../system.windows/) время файла в дату и время с локальным смещением. |
| static [DateTimeOffset](./) [FromUnixTimeMilliseconds](./fromunixtimemilliseconds/)(**int64_t**) | [Convert](../convert/) Unix-время в объект [DateTimeOffset](./). |
| static [DateTimeOffset](./) [FromUnixTimeSeconds](./fromunixtimeseconds/)(**int64_t**) | [Convert](../convert/) Unix-время в объект [DateTimeOffset](./). |
| [DateTime](../datetime/) [get_Date](./get_date/)() const | Получает компонент даты текущего объекта. |
| [DateTime](../datetime/) [get_DateTime](./get_datetime/)() const | Получает значение [DateTime](../datetime/). |
| int [get_Day](./get_day/)() const | Получает день месяца текущего объекта. |
| [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Получает день недели текущего объекта. |
| int [get_DayOfYear](./get_dayofyear/)() const | Получает день года текущего объекта. |
| int [get_Hour](./get_hour/)() const | Получает часовой компонент текущего объекта. |
| [DateTime](../datetime/) [get_LocalDateTime](./get_localdatetime/)() const | Получает значение [DateTime](../datetime/), представляющее локальную дату и время. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Получает миллисекундный компонент текущего объекта. |
| int [get_Minute](./get_minute/)() const | Получает минутный компонент текущего объекта. |
| int [get_Month](./get_month/)() const | Получает компонент месяца текущего объекта. |
| static [DateTimeOffset](./) [get_Now](./get_now/)() | Получает [DateTimeOffset](./), у которого дата и время установлены в текущее локальное время, а смещение установлено в смещение локального времени. |
| constexpr [TimeSpan](../timespan/) [get_Offset](./get_offset/)() const | Получает смещение от UTC. |
| constexpr int [get_Second](./get_second/)() const | Получает секундный компонент текущего объекта. |
| **int64_t** [get_Ticks](./get_ticks/)() const | Получает количество тактов текущего объекта. |
| [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Получает время суток текущего объекта. |
| [DateTime](../datetime/) [get_UtcDateTime](./get_utcdatetime/)() const | Получает значение [DateTime](../datetime/), представляющее дату и время UTC. |
| static [DateTimeOffset](./) [get_UtcNow](./get_utcnow/)() | Получает [DateTimeOffset](./), у которого дата и время установлены в текущее UTC-время, а смещение равно [TimeSpan::Zero](../timespan/zero/). |
| **int64_t** [get_UtcTicks](./get_utcticks/)() const | Получает количество тактов текущего объекта во времени UTC. |
| int [get_Year](./get_year/)() const | Получает компонент года текущего объекта. |
| int [GetHashCode](./gethashcode/)() const | Получает хеш-код текущего объекта [DateTimeOffset](./). |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| **bool** [operator!=](./operator_not_equal/)(const [DateTimeOffset](./)\&) const | Определяет, представляют ли текущий объект и указанный объект [DateTimeOffset](./) разные значения даты и времени. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTimeOffset](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Возвращает новый экземпляр класса [DateTimeOffset](./), представляющий значение даты и времени, которое является суммой значения, представленного текущим объектом, и указанного интервала времени. |
| [DateTimeOffset](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Возвращает новый экземпляр класса [DateTimeOffset](./), представляющий значение даты и времени, полученное вычитанием указанного интервала времени из значения, представленного текущим объектом. |
| [TimeSpan](../timespan/) [operator-](./operator_minus/)(const [DateTimeOffset](./)\&) const | Возвращает экземпляр класса [TimeSpan](../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами. |
| **bool** [operator<](./operator_less/)(const [DateTimeOffset](./)\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое предшествует значению, представленному указанным объектом [DateTimeOffset](./). |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| **bool** [operator<=](./operator_less_equal/)(const [DateTimeOffset](./)\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое предшествует или равно значению, представленному указанным объектом [DateTimeOffset](./). |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| **bool** [operator==](./operator_equal_equal/)(const [DateTimeOffset](./)\&) const | Определяет, представляют ли текущий объект и указанный объект [DateTimeOffset](./) одинаковое значение даты и времени. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| **bool** [operator>](./operator_greater/)(const [DateTimeOffset](./)\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое позже значения, представленного указанным объектом [DateTimeOffset](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| **bool** [operator>=](./operator_greater_equal/)(const [DateTimeOffset](./)\&) const | Определяет, представляет ли текущий объект значение даты и времени, которое позже или равно значению, представленному указанным объектом [DateTimeOffset](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанную строку в эквивалент [DateTimeOffset](./). |
| static [DateTimeOffset](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Преобразует указанную строку в объект [DateTimeOffset](./) с использованием указанного поставщика формата и стиля форматирования. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Преобразует указанную строку в объект [DateTimeOffset](./) с использованием указанного формата, поставщика формата и стиля форматирования. |
| static [DateTimeOffset](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Преобразует указанную строку в объект [DateTimeOffset](./) с использованием указанных форматов, поставщика формата и стиля форматирования. |
| [DateTimeOffset](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Вычитает указанный интервал времени из текущего объекта. |
| [TimeSpan](../timespan/) [Subtract](./subtract/)(const [DateTimeOffset](./)\&) const | Вычитает указанное значение [DateTimeOffset](./) из текущего объекта. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Преобразует текущий объект во время файла [Windows](../../system.windows/). |
| [DateTimeOffset](./) [ToLocalTime](./tolocaltime/)() const | Преобразует текущий объект в объект, представляющий локальное время. |
| [DateTimeOffset](./) [ToOffset](./tooffset/)([TimeSpan](../timespan/)) const | Заменяет смещение текущего объекта указанным смещением. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Преобразует текущий объект в строку с использованием указанного формата и поставщика формата. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Преобразует текущий объект в строку с использованием указанного поставщика формата. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Преобразует текущий объект в строку с использованием указанного формата. |
| [String](../string/) [ToString](./tostring/)() const | Преобразует текущий объект в строку. |
| [DateTimeOffset](./) [ToUniversalTime](./touniversaltime/)() const | Преобразует текущий объект в объект, представляющий время UTC. |
| **int64_t** [ToUnixTimeMilliseconds](./tounixtimemilliseconds/)() const | Получает миллисекунды, прошедшие с начала эпохи Unix. |
| **int64_t** [ToUnixTimeSeconds](./tounixtimeseconds/)() const | Получает секунды, прошедшие с начала эпохи Unix. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTimeOffset](./)\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./) с использованием указанного поставщика формата и стиля форматирования. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./) с использованием указанных форматов, поставщика формата и стиля форматирования. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTimeOffset](./)\&) | Пытается преобразовать указанную строку в объект [DateTimeOffset](./) с использованием указанного формата, поставщика формата и стиля форматирования. |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Возвращает объект [TypeInfo](../typeinfo/), представляющий структуру [TimeSpan](../timespan/). |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxOffset](./maxoffset/) | Получает максимальное смещение в тактах. |
| static [MaxValue](./maxvalue/) | Получает наибольшее значение [DateTimeOffset](./). |
| static constexpr [MinOffset](./minoffset/) | Получает минимальное смещение в тактах. |
| static [MinValue](./minvalue/) | Получает самое раннее значение [DateTimeOffset](./). |
| static [UnixEpoch](./unixepoch/) | Получает начало эпохи Unix. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)