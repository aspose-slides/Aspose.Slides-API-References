---
title: JapaneseCalendar
second_title: Aspose.Slides для справки API C++
description: "Японский календарь. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 183
url: /ru/system.globalization/japanesecalendar/
---
## JapaneseCalendar класс

Japanese calendar. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class JapaneseCalendar : public System::Globalization::Calendar
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual [DateTime](../../system/datetime/) [AddDays](../calendar/adddays/)([DateTime](../../system/datetime/), int) const | Добавляет дни к моменту времени. |
| virtual [DateTime](../../system/datetime/) [AddHours](../calendar/addhours/)([DateTime](../../system/datetime/), int) const | Добавляет часы к моменту времени. |
| virtual [DateTime](../../system/datetime/) [AddMilliseconds](../calendar/addmilliseconds/)([DateTime](../../system/datetime/), **double**) const | Добавляет миллисекунды к моменту времени. |
| virtual [DateTime](../../system/datetime/) [AddMinutes](../calendar/addminutes/)([DateTime](../../system/datetime/), int) const | Добавляет минуты к моменту времени. |
| virtual [DateTime](../../system/datetime/) [AddMonths](../calendar/addmonths/)([DateTime](../../system/datetime/), int) const | Добавляет месяцы к моменту времени. |
| virtual [DateTime](../../system/datetime/) [AddSeconds](../calendar/addseconds/)([DateTime](../../system/datetime/), int) const | Добавляет секунды к моменту времени. |
| virtual [DateTime](../../system/datetime/) [AddWeeks](../calendar/addweeks/)([DateTime](../../system/datetime/), int) const | Добавляет недели к моменту времени. |
| virtual [DateTime](../../system/datetime/) [AddYears](../calendar/addyears/)([DateTime](../../system/datetime/), int) const | Добавляет годы к моменту времени. |
|  [Calendar](../calendar/calendar/)(const [Calendar](../calendar/)\&) | Информация RTTI. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Создает копию текущего объекта и возвращает shared pointer на неё. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Получает тип алгоритма. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Получает индекс текущей эры. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Получает значение текущей эры. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Получает список эр, существующих в календаре. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Проверяет, является ли календарь только для чтения. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Максимальный момент времени, поддерживаемый календарём. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Минимальный момент времени, поддерживаемый календарём. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Получает последний год, который может быть представлен двузначным. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| int [GetDayOfMonth](./getdayofmonth/)([DateTime](../../system/datetime/)) const override | Получает день месяца для указанного момента времени. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Получает день недели для указанного момента времени. |
| int [GetDayOfYear](./getdayofyear/)([DateTime](../../system/datetime/)) const override | Получает день года для указанного момента времени. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Получает количество дней в указанном месяце. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Получает количество дней в указанном месяце. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Получает количество дней в указанном месяце. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Получает количество дней в указанном году. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Получает количество дней в указанном году. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Получает количество дней в указанном году. |
| int [GetEra](./getera/)([DateTime](../../system/datetime/)) const override | Получает эру для указанного момента времени. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Получает часы для указанного момента времени. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Получает високосный месяц для указанного года. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Получает високосный месяц для указанного года. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Получает високосный месяц для указанного года. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Получает миллисекунды для указанного момента времени. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Получает минуты для указанного момента времени. |
| int [GetMonth](./getmonth/)([DateTime](../../system/datetime/)) const override | Получает месяц для указанного момента времени. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Получает количество месяцев в указанном году. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Информация RTTI. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Информация RTTI. |
| virtual int [GetSecond](../calendar/getsecond/)([DateTime](../../system/datetime/)) const | Получает секунды для указанного момента времени. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual int [GetWeekOfYear](../calendar/getweekofyear/)([DateTime](../../system/datetime/), [CalendarWeekRule](../calendarweekrule/), [DayOfWeek](../../system/dayofweek/)) const | Получает номер недели года для указанного момента времени. |
| virtual int [GetYear](../calendar/getyear/)([DateTime](../../system/datetime/)) const | Получает год для указанного момента времени. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const override | Проверяет, является ли день високосным. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int) const | Проверяет, является ли день високосным. |
| virtual **bool** [IsLeapDay](./isleapday/)(int, int, int, int) const | Проверяет, является ли день високосным. |
| **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const override | Проверяет, является ли месяц високосным. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int) const | Проверяет, является ли месяц високосным. |
| virtual **bool** [IsLeapMonth](./isleapmonth/)(int, int, int) const | Проверяет, является ли месяц високосным. |
| **bool** [IsLeapYear](./isleapyear/)(int, int) const override | Проверяет, является ли год високосным. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int) const | Проверяет, является ли год високосным. |
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Проверяет, является ли год высоким. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Проверяет значения года, месяца, дня и эры. |
|  [JapaneseCalendar](./japanesecalendar/)() | Конструктор. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Получает только-читабельную версию календаря. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик shared-reference на указанное значение. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Устанавливает последний год, который может быть представлен двузначным. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как weak-pointer (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика shared-reference. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик shared-reference. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик shared-reference. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const override | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(int, int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Преобразует год в четырёхзначный, используя свойство TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик weak-reference. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик weak-reference. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [Calendar](../calendar/)
* Пространство имён [System::Globalization](../)
* Библиотека [Aspose.Slides](../../)