---
title: DateTime
second_title: "Aspose.Slides для C++ справочник API"
description: "Представляет конкретное значение даты и времени во временной шкале. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс System::SmartPtr для управления объектами этого типа."
type: docs
weight: 222
url: /ru/system/datetime/
---
## Класс DateTime

Представляет конкретное значение даты и времени на временной шкале. Этот тип следует размещать в стеке и передавать в функции по значению или по ссылке. Никогда не используйте класс [System::SmartPtr](../smartptr/) для управления объектами этого типа.

```cpp
class DateTime
```

## Методы

| Метод | Описание |
| --- | --- |
| [DateTime](./) [Add](./add/)([TimeSpan](../timespan/)) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате добавления указанного временного промежутка к значению даты и времени, представленному текущим объектом. |
| [DateTime](./) [AddDays](./adddays/)(**double**) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного количества дней. |
| [DateTime](./) [AddHours](./addhours/)(**double**) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного количества часов. |
| [DateTime](./) [AddMilliseconds](./addmilliseconds/)(**double**) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного количества миллисекунд. |
| [DateTime](./) [AddMinutes](./addminutes/)(**double**) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного количества минут. |
| [DateTime](./) [AddMonths](./addmonths/)(int) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного количества месяцев. |
| [DateTime](./) [AddSeconds](./addseconds/)(**double**) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного количества секунд. |
| [DateTime](./) [AddTicks](./addticks/)(**int64_t**) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного количества интервалов по 100 наносекунд. |
| [DateTime](./) [AddYears](./addyears/)(int) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, равное текущему объекту, но с увеличенным на указанное число компонентом года. |
| static constexpr int [Compare](./compare/)([DateTime](./), [DateTime](./)) | Сравнивает два значения, представленных указанными экземплярами класса [DateTime](./), и возвращает значение, указывающее относительное положение этих значений во временной шкале. |
| constexpr int [CompareTo](./compareto/)([DateTime](./)) const | Сравнивает два значения даты и времени, представленные текущим объектом и указанным экземпляром класса [DateTime](./), и возвращает значение, указывающее их относительное положение во временной шкале. |
| constexpr [DateTime](./datetime/)() | Создаёт экземпляр, представляющий наименьшее возможное значение даты и времени, равное MinValue. |
| [DateTime](./datetime/)(int, int, int) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем и днём. |
| [DateTime](./datetime/)(int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем и днём в указанном календаре. |
| [DateTime](./datetime/)(int, int, int, int, int, int) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой. |
| [DateTime](./datetime/)(int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой. |
| [DateTime](./datetime/)(int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой и секундой в указанном календаре. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, [DateTimeKind](../datetimekind/)) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой, секундой и миллисекундой. |
| [DateTime](./datetime/)(int, int, int, int, int, int, int, const [SharedPtr](../sharedptr/)\<[Globalization::Calendar](../../system.globalization/calendar/)\>\&, [DateTimeKind](../datetimekind/)) | Создаёт экземпляр, представляющий значение даты и времени, заданное конкретным годом, месяцем, днём, часом, минутой, секундой и миллисекундой в указанном календаре. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/)) | Создаёт экземпляр, представляющий значение даты и времени, заданное числом тиков. |
| [DateTime](./datetime/)(**int64_t**, [DateTimeKind](../datetimekind/), **bool**) | Создаёт экземпляр, представляющий значение даты и времени, заданное числом тиков. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| [DateTime](./datetime/)(const [DateTime](./)\&) | Создаёт копию экземпляра. |
| static int [DaysInMonth](./daysinmonth/)(int, int) | Возвращает количество дней в указанном месяце указанного года. |
| static constexpr **bool** [Equals](./equals/)([DateTime](./), [DateTime](./)) | Определяет, представляют ли указанные экземпляры класса [DateTime](./) одно и то же значение даты и времени. |
| constexpr **bool** [Equals](./equals/)([DateTime](./)) const | Определяет, представляет ли указанный экземпляр класса [DateTime](./) то же значение даты и времени, что и текущий объект. |
| static [DateTime](./) [FromBinary](./frombinary/)(**int64_t**) | Десериализует значение даты и времени из указанного беззнакового 64-битного целого и устанавливает новое значение экземпляра класса [DateTime](./). |
| static [DateTime](./) [FromFileTime](./fromfiletime/)(**int64_t**) | Преобразует указанное файловое время в экземпляр класса [DateTime](./), представляющий то же значение даты и времени в локальном времени. |
| static [DateTime](./) [FromFileTimeUtc](./fromfiletimeutc/)(**int64_t**) | Преобразует указанное файловое время в экземпляр класса [DateTime](./), представляющий то же значение даты и времени в UTC. |
| static [DateTime](./) [FromOADate](./fromoadate/)(**double**) | Возвращает экземпляр класса [DateTime](./), представляющий значение даты и времени, эквивалентное указанной дате OLE Automation. |
| static [DateTime](./) [FromUnixTime](./fromunixtime/)(time_t) | Преобразует указанное значение Unix-времени в экземпляр класса [DateTime](./). ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| constexpr [DateTime](./) [get_Date](./get_date/)() const | Возвращает новый экземпляр класса [DateTime](./), представляющий часть даты из даты и времени текущего объекта, при этом все компоненты части времени устанавливаются в 0. |
| int [get_Day](./get_day/)() const | Возвращает порядковый номер дня в месяце, представленный текущим объектом. |
| constexpr [DayOfWeek](../dayofweek/) [get_DayOfWeek](./get_dayofweek/)() const | Возвращает значение, представляющее день недели, представленный текущим объектом. |
| int [get_DayOfYear](./get_dayofyear/)() const | Возвращает порядковый номер дня в году, представленный текущим объектом. |
| constexpr int [get_Hour](./get_hour/)() const | Возвращает компонент часов значения даты и времени, представленного текущим объектом. |
| constexpr [DateTimeKind](../datetimekind/) [get_Kind](./get_kind/)() const | Возвращает значение, указывающее, является ли дата и время текущего объекта локальной, UTC или ни тем, ни другим. |
| constexpr int [get_Millisecond](./get_millisecond/)() const | Возвращает компонент миллисекунд значения даты и времени, представленного текущим объектом. |
| constexpr int [get_Minute](./get_minute/)() const | Возвращает компонент минут значения даты и времени, представленного текущим объектом. |
| int [get_Month](./get_month/)() const | Возвращает порядковый номер месяца в году, представленный текущим объектом. |
| static [DateTime](./) [get_Now](./get_now/)() | Возвращает экземпляр класса [DateTime](./), представляющий текущее время как локальное. |
| constexpr int [get_Second](./get_second/)() const | Возвращает компонент секунд значения даты и времени, представленного текущим объектом. |
| constexpr **int64_t** [get_Ticks](./get_ticks/)() const | Возвращает количество интервалов по 100 наносекунд, прошедших с 0:00:00 UTC, 1 января 0001 года по григорианскому календарю до даты и времени, представленных текущим объектом. |
| constexpr [TimeSpan](../timespan/) [get_TimeOfDay](./get_timeofday/)() const | Возвращает значение, представляющее интервал времени от начала дня, представленного текущим объектом, до даты и времени, представленных текущим объектом. |
| static [DateTime](./) [get_Today](./get_today/)() | Возвращает экземпляр класса [DateTime](./), представляющий текущую дату, при этом все компоненты временной части значения, представленного объектом, установлены в 0. |
| static [DateTime](./) [get_UtcNow](./get_utcnow/)() | Возвращает экземпляр класса [DateTime](./), представляющий текущее время в формате UTC. |
| int [get_Year](./get_year/)() const | Возвращает год, представленный текущим объектом. |
| void [GetDateComponents](./getdatecomponents/)(int\&, int\&, int\&) const | Получает части даты. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)() const | Возвращает массив строк, где каждый элемент представляет текущий объект в виде строки, отформатированной согласно одному из стандартных спецификаторов формата даты и времени. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t) const | Возвращает массив строк, где каждый элемент представляет текущий объект в виде строки, отформатированной согласно указанному стандартному спецификатору формата даты и времени. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Возвращает массив строк, где каждый элемент представляет текущий объект в виде строки, отформатированной согласно одному из стандартных спецификаторов формата даты и времени и указанному поставщику формата. |
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetDateTimeFormats](./getdatetimeformats/)(char_t, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Возвращает массив строк, где каждый элемент представляет текущий объект в виде строки, отформатированной согласно указанному стандартному спецификатору формата даты и времени и поставщику формата. |
| int [GetHashCode](./gethashcode/)() const | Возвращает хеш-код текущего объекта. |
| **bool** [IsDaylightSavingTime](./isdaylightsavingtime/)() const | Определяет, находится ли значение даты и времени, представленное текущим объектом, в диапазоне летнего времени для текущего часового пояса. |
| static **bool** [IsLeapYear](./isleapyear/)(int) | Определяет, является ли указанный год високосным. |
| constexpr **bool** [IsNull](./isnull/)() const |  |
| constexpr **bool** [operator!=](./operator_not_equal/)([DateTime](./)) const | Определяет, представляют ли текущий объект и указанный объект [DateTime](./) разные значения даты и времени. |
| constexpr **bool** [operator!=](./operator_not_equal/)(std::nullptr_t) const |  |
| [DateTime](./) [operator+](./operator_plus/)([TimeSpan](../timespan/)) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного временного промежутка. |
| [DateTime](./)\& [operator+=](./operator_plus_equal/)([TimeSpan](../timespan/)) | Устанавливает текущий объект в значение даты и времени, полученное в результате сложения значения, представленного текущим объектом, и указанного временного промежутка. |
| [DateTime](./) [operator-](./operator_minus/)([TimeSpan](../timespan/)) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате вычитания указанного временного промежутка из значения, представленного текущим объектом. |
| constexpr [TimeSpan](../timespan/) [operator-](./operator_minus/)([DateTime](./)) const | Возвращает экземпляр класса [TimeSpan](../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами. |
| [DateTime](./)\& [operator-=](./operator_minus_equal/)([TimeSpan](../timespan/)) | Устанавливает текущий объект в значение даты и времени, полученное в результате вычитания указанного временного промежутка из значения даты и времени, представленного текущим объектом. |
| constexpr **bool** [operator<](./operator_less/)([DateTime](./)) const | Определяет, представляет ли текущий объект значение даты и времени, предшествующее значению, представленному указанным объектом [DateTime](./). |
| constexpr **bool** [operator<](./operator_less/)(std::nullptr_t) const |  |
| constexpr **bool** [operator<=](./operator_less_equal/)([DateTime](./)) const | Определяет, представляет ли текущий объект значение даты и времени, предшествующее или равное значению, представленному указанным объектом [DateTime](./). |
| constexpr **bool** [operator<=](./operator_less_equal/)(std::nullptr_t) const |  |
| [DateTime](./)\& [operator=](./operator_equal/)(const [DateTime](./)\&) | Присваивает значение, представленное указанным экземпляром [DateTime](./), текущему объекту. |
| constexpr **bool** [operator==](./operator_equal_equal/)([DateTime](./)) const | Определяет, представляют ли текущий объект и указанный объект [DateTime](./) одинаковое значение даты и времени. |
| constexpr **bool** [operator==](./operator_equal_equal/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>](./operator_greater/)([DateTime](./)) const | Определяет, представляет ли текущий объект значение даты и времени, более позднее, чем значение, представленное указанным объектом [DateTime](./). |
| constexpr **bool** [operator>](./operator_greater/)(std::nullptr_t) const |  |
| constexpr **bool** [operator>=](./operator_greater_equal/)([DateTime](./)) const | Определяет, представляет ли текущий объект значение даты и времени, более позднее или равное значению, представленному указанным объектом [DateTime](./). |
| constexpr **bool** [operator>=](./operator_greater_equal/)(std::nullptr_t) const |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./). |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя сведения о формате, зависящие от культуры. |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя указанный формат и сведения о формате, зависящие от культуры. Формат строкового представления должен точно соответствовать указанному формату. Выбрасывает исключение при неудачном преобразовании. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) | Преобразует указанное строковое представление значения даты и времени в эквивалентный объект [DateTime](./), используя указанные форматы, сведения о формате, зависящие от культуры, и стиль. Формат строкового представления должен точно соответствовать одному или нескольким из указанных форматов. Выбрасывает исключение, если преобразование не удалось. |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [ParseExact](./parseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/)) |  |
| static [DateTime](./) [SpecifyKind](./specifykind/)([DateTime](./), [DateTimeKind](../datetimekind/)) | Создаёт новый объект [DateTime](./), представляющий то же количество тиков, что и указанный объект [DateTime](./), и представляющий локальное время, UTC или ни то, ни другое, как указано аргументом **kind**. |
| [DateTime](./) [Subtract](./subtract/)([TimeSpan](../timespan/)) const | Возвращает новый экземпляр класса [DateTime](./), представляющий значение даты и времени, полученное в результате вычитания указанного временного промежутка из значения, представленного текущим объектом. |
| constexpr [TimeSpan](../timespan/) [Subtract](./subtract/)([DateTime](./)) const | Возвращает экземпляр класса [TimeSpan](../timespan/), представляющий интервал времени между значениями даты и времени, представленными текущим и указанным объектами. |
| **int64_t** [ToBinary](./tobinary/)() const | Сериализует текущий объект. |
| **int64_t** [ToFileTime](./tofiletime/)() const | Возвращает значение, представляющее дату и время текущего объекта в виде файлового времени. |
| **int64_t** [ToFileTimeUtc](./tofiletimeutc/)() const | Преобразует значение даты и времени, представленного текущим объектом, в файловое время UTC. |
| [DateTime](./) [ToLocalTime](./tolocaltime/)() const | Возвращает новый экземпляр класса [DateTime](./), представляющий дату и время текущего объекта в виде локального времени. |
| [String](../string/) [ToLongDateString](./tolongdatestring/)() const | Возвращает строку, содержащую полное датовое представление текущего объекта. |
| [String](../string/) [ToLongTimeString](./tolongtimestring/)() const | Возвращает строку, содержащую полное временное представление текущего объекта. |
| **double** [ToOADate](./tooadate/)() const | Возвращает значение даты и времени, представленного текущим объектом, в виде даты OLE Automation. |
| [String](../string/) [ToShortDateString](./toshortdatestring/)() const | Возвращает строку, содержащую короткое датовое представление текущего объекта. |
| [String](../string/) [ToShortTimeString](./toshorttimestring/)() const | Возвращает строку, содержащую короткое временное представление текущего объекта. |
| [String](../string/) [ToString](./tostring/)() const | Возвращает строковое представление даты и времени текущего объекта, используя правила форматирования, определённые текущей культурой. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&) const | Возвращает строковое представление даты и времени текущего объекта, используя указанный формат и правила форматирования, определённые текущей культурой. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Возвращает строковое представление даты и времени текущего объекта, используя указанные сведения о формате. |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(std::nullptr_t) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) const | Возвращает строковое представление даты и времени текущего объекта, используя указанные сведения о формате. |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&) const |  |
| [String](../string/) [ToString](./tostring/)(const [String](../string/)\&, std::nullptr_t) const |  |
| [DateTime](./) [ToUniversalTime](./touniversaltime/)() const | Возвращает новый экземпляр класса [DateTime](./), представляющий дату и время текущего объекта в виде UTC. |
| time_t [ToUnixTime](./tounixtime/)() const | Возвращает значение, представляющее дату и время текущего объекта в виде Unix-времени. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [DateTime](./)\&) | Преобразует указанное строковое представление даты и времени в эквивалентный объект [DateTime](./). |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Преобразует указанное строковое представление даты и времени в эквивалентный объект [DateTime](./), используя указанные сведения о формате, зависящие от культуры, и стиль. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Преобразует указанное строковое представление даты и времени в эквивалентный объект [DateTime](./), используя указанный формат, сведения о формате, зависящие от культуры, и стиль. Формат строкового представления должен точно соответствовать указанному формату. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [String](../string/)\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) | Преобразует указанное строковое представление даты и времени в эквивалентный объект [DateTime](./), используя указанные форматы, сведения о формате, зависящие от культуры, и стиль. Формат строкового представления должен точно соответствовать одному или нескольким из указанных форматов. |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, const [SharedPtr](../sharedptr/)\<[Globalization::DateTimeFormatInfo](../../system.globalization/datetimeformatinfo/)\>\&, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static **bool** [TryParseExact](./tryparseexact/)(const [String](../string/)\&, const [ArrayPtr](../arrayptr/)\<[String](../string/)\>\&, std::nullptr_t, [Globalization::DateTimeStyles](../../system.globalization/datetimestyles/), [DateTime](./)\&) |  |
| static const [TypeInfo](../typeinfo/)\& [Type](./type/)() | Возвращает объект [TypeInfo](../typeinfo/), содержащий информацию об этом классе. |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [MaxTicks](./maxticks/) | Количество интервалов по 100 наносекунд во временном интервале между минимальным возможным и максимальным возможным значением [DateTime](./). |
| static [MaxValue](./maxvalue/) | Экземпляр класса [DateTime](./), представляющий максимальное возможное значение даты и времени. |
| static constexpr [MinTicks](./minticks/) | Минимальное количество тиков, которое может представлять экземпляр класса [DateTime](./). |
| static [MinValue](./minvalue/) | Экземпляр класса [DateTime](./), представляющий минимальное возможное значение даты и времени. |
| static constexpr [TicksPerDay](./ticksperday/) | Количество тиков в дне. |
| static constexpr [TicksPerHour](./ticksperhour/) | Количество тиков в часе. |
| static constexpr [TicksPerMicrosecond](./tickspermicrosecond/) | Количество тиков в микросекунде. |
| static constexpr [TicksPerMillisecond](./tickspermillisecond/) | Количество тиков в миллисекунде. |
| static constexpr [TicksPerMinute](./ticksperminute/) | Количество тиков в минуте. |
| static constexpr [TicksPerSecond](./tickspersecond/) | Количество тиков в секунде. |
| static [UnixEpoch](./unixepoch/) | Экземпляр класса [DateTime](./), представляющий начало эпохи Unix (1970-01-01 00:00:00). |

## Примечания

```cpp
#include "system/console.h"
#include "system/date_time.h"

int main()
{
  using namespace System;

  // Создайте экземпляр класса 'DateTime'.
  DateTime dateTime{1990, 10, 30};

  // Выведите экземпляр в нескольких форматах.
  Console::WriteLine(dateTime.ToShortDateString());
  Console::WriteLine(dateTime.ToShortTimeString());
  Console::WriteLine(dateTime.ToString());

  return 0;
}
/*
Этот пример кода выводит следующий результат:
30.10.1990
0:00
30.10.1990 0:00:00
*/
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)