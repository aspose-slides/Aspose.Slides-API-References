---
title: PersianCalendar
second_title: Aspose.Slides для C++ API Reference
description: "Персидский календарь. Объекты этого класса должны создаваться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 261
url: /ru/system.globalization/persiancalendar/
---
## PersianCalendar класс

Персидский календарь. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class PersianCalendar : public System::Globalization::Calendar
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
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Создаёт копию текущего объекта и возвращает shared pointer на него. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [CalendarAlgorithmType](../calendaralgorithmtype/) [get_AlgorithmType](./get_algorithmtype/)() const override | Получает тип алгоритма. |
| int [get_CurrentEra](../calendar/get_currentera/)() const | Получает индекс текущей эры. |
| int [get_CurrentEraValue](../calendar/get_currenteravalue/)() const | Получает значение текущей эры. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_Eras](./get_eras/)() const override | Получает список эр, существующих в календаре. |
| **bool** [get_IsReadOnly](../calendar/get_isreadonly/)() const | Проверяет, является ли календарь только для чтения. |
| [DateTime](../../system/datetime/) [get_MaxSupportedDateTime](./get_maxsupporteddatetime/)() const override | Максимальный момент времени, поддерживаемый календарём. |
| [DateTime](../../system/datetime/) [get_MinSupportedDateTime](./get_minsupporteddatetime/)() const override | Минимальный момент времени, поддерживаемый календарём. |
| virtual int [get_TwoDigitYearMax](../calendar/get_twodigityearmax/)() const | Получает последний год, который может быть представлен двумя цифрами. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual int [GetDayOfMonth](../calendar/getdayofmonth/)([DateTime](../../system/datetime/)) const | Получает день месяца для указанного момента времени. |
| [DayOfWeek](../../system/dayofweek/) [GetDayOfWeek](./getdayofweek/)([DateTime](../../system/datetime/)) const override | Получает день недели для указанного момента времени. |
| virtual int [GetDayOfYear](../calendar/getdayofyear/)([DateTime](../../system/datetime/)) const | Получает день года для указанного момента времени. |
| int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const override | Получает количество дней в указанном месяце. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int) const | Информация RTTI. |
| virtual int [GetDaysInMonth](./getdaysinmonth/)(int, int, int) const | Информация RTTI. |
| int [GetDaysInYear](./getdaysinyear/)(int, int) const override | Получает количество дней в указанном году. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int) const | Получает количество дней в указанном году. |
| virtual int [GetDaysInYear](./getdaysinyear/)(int, int) const | Получает количество дней в указанном году. |
| virtual int [GetEra](../calendar/getera/)([DateTime](../../system/datetime/)) const | Получает эру для указанного момента времени. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual int [GetHour](../calendar/gethour/)([DateTime](../../system/datetime/)) const | Получает часы для указанного момента времени. |
| int [GetLeapMonth](./getleapmonth/)(int, int) const override | Получает високосный месяц для указанного года. |
| virtual int [GetLeapMonth](./getleapmonth/)(int) const | Получает високосный месяц для указанного года. |
| virtual int [GetLeapMonth](./getleapmonth/)(int, int) const | Получает високосный месяц для указанного года. |
| virtual **double** [GetMilliseconds](../calendar/getmilliseconds/)([DateTime](../../system/datetime/)) const | Получает миллисекунды для указанного момента времени. |
| virtual int [GetMinute](../calendar/getminute/)([DateTime](../../system/datetime/)) const | Получает минуты для указанного момента времени. |
| virtual int [GetMonth](../calendar/getmonth/)([DateTime](../../system/datetime/)) const | Получает месяц для указанного момента времени. |
| int [GetMonthsInYear](./getmonthsinyear/)(int, int) const override | Получает количество месяцев в указанном году. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int) const | Получает количество месяцев в указанном году. |
| virtual int [GetMonthsInYear](./getmonthsinyear/)(int, int) const | Получает количество месяцев в указанном году. |
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
| virtual **bool** [IsLeapYear](./isleapyear/)(int, int) const | Проверяет, является ли год високосным. |
| **bool** [IsValidDay](../calendar/isvalidday/)(int, int, int, int) const | Проверяет значения года, месяца, дня и эры. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Calendar](../calendar/)\& [operator=](../calendar/operator_equal/)(const [Calendar](../calendar/)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) |  |
|  [PersianCalendar](./persiancalendar/)() | Конструктор. |
| static [CalendarPtr](../calendarptr/) [ReadOnly](../calendar/readonly/)(const [CalendarPtr](../calendarptr/)\&) | Получает только читаемую версию календаря. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на заданное значение. |
| virtual void [set_TwoDigitYearMax](../calendar/set_twodigityearmax/)(int) | Устанавливает последний год, который может быть представлен двумя цифрами. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n'th шаблонный аргумент как weak-pointer (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual [DateTime](../../system/datetime/) [ToDateTime](../calendar/todatetime/)(int, int, int, int, int, int, int, int) const | Создаёт объект [DateTime](../../system/datetime/) из компонентов. |
| virtual int [ToFourDigitYear](../calendar/tofourdigityear/)(int) const | Преобразует год в четырёхзначный год, используя свойство TwoDigitYearMax. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [PersianEra](./persianera/) | Текущая персидская эра. |

## См. также

* Класс [Calendar](../calendar/)
* Пространство имён [System::Globalization](../)
* Библиотека [Aspose.Slides](../../)