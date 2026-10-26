---
title: NumberFormatInfo
second_title: Справочник API Aspose.Slides для C++
description: "Содержит информацию о том, как форматировать числа. Операции установки доступны только для объектов, не только для чтения. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() . Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 248
url: /ru/system.globalization/numberformatinfo/
---
## NumberFormatInfo класс

Содержит информацию о том, как форматировать числа. Операции установки доступны только для объектов, не являющихся только для чтения. Экземпляры этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям проверки утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class NumberFormatInfo : public virtual System::Object,
                         public System::IFormatProvider,
                         public System::ICloneable
```

## Методы

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Клонирует информацию о формате. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| int [get_CurrencyDecimalDigits](./get_currencydecimaldigits/)() const | Возвращает количество десятичных знаков валюты. |
| [String](../../system/string/) [get_CurrencyDecimalSeparator](./get_currencydecimalseparator/)() const | Возвращает десятичный разделитель валюты. |
| [String](../../system/string/) [get_CurrencyGroupSeparator](./get_currencygroupseparator/)() const | Возвращает разделитель разрядов валюты. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_CurrencyGroupSizes](./get_currencygroupsizes/)() const | Возвращает количество десятичных знаков валюты в группе. |
| int [get_CurrencyNegativePattern](./get_currencynegativepattern/)() const | Возвращает шаблон отрицательной валюты. |
| int [get_CurrencyPositivePattern](./get_currencypositivepattern/)() const | Возвращает шаблон положительной валюты. |
| [String](../../system/string/) [get_CurrencySymbol](./get_currencysymbol/)() const | Возвращает символ валюты. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [get_CurrentInfo](./get_currentinfo/)() | Возвращает информацию о формате чисел, определённую текущей культурой потока. |
| [DigitShapes](../digitshapes/) [get_DigitSubstitution](./get_digitsubstitution/)() const | Возвращает значение, определяющее отображение формы цифры. |
| static const [NumberFormatInfoPtr](../numberformatinfoptr/)\& [get_InvariantInfo](./get_invariantinfo/)() | Возвращает информацию о формате чисел, определённую инвариантной культурой. |
| **bool** [get_IsReadOnly](./get_isreadonly/)() const | Проверяет, является ли формат только для чтения. |
| [String](../../system/string/) [get_NaNSymbol](./get_nansymbol/)() const | Возвращает символ Not-a-Number. |
| [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_NativeDigits](./get_nativedigits/)() const | Возвращает символы цифр (от 0 до 9). |
| [String](../../system/string/) [get_NegativeInfinitySymbol](./get_negativeinfinitysymbol/)() const | Возвращает символ отрицательной бесконечности. |
| [String](../../system/string/) [get_NegativeSign](./get_negativesign/)() const | Возвращает знак минуса. |
| int [get_NumberDecimalDigits](./get_numberdecimaldigits/)() const | Возвращает количество десятичных знаков. |
| [String](../../system/string/) [get_NumberDecimalSeparator](./get_numberdecimalseparator/)() const | Возвращает десятичный разделитель. |
| [String](../../system/string/) [get_NumberGroupSeparator](./get_numbergroupseparator/)() const | Возвращает разделитель разрядов числа. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_NumberGroupSizes](./get_numbergroupsizes/)() const | Возвращает количество цифр в группе. |
| int [get_NumberNegativePattern](./get_numbernegativepattern/)() const | Возвращает шаблон отрицательного числа. |
| int [get_PercentDecimalDigits](./get_percentdecimaldigits/)() const | Возвращает количество десятичных знаков в процентных значениях. |
| [String](../../system/string/) [get_PercentDecimalSeparator](./get_percentdecimalseparator/)() const | Возвращает десятичный разделитель в процентных значениях. |
| [String](../../system/string/) [get_PercentGroupSeparator](./get_percentgroupseparator/)() const | Возвращает разделитель групп в процентных значениях. |
| [ArrayPtr](../../system/arrayptr/)\<int\> [get_PercentGroupSizes](./get_percentgroupsizes/)() const | Возвращает количество цифр в группе процентных значений. |
| int [get_PercentNegativePattern](./get_percentnegativepattern/)() const | Возвращает шаблон отрицательного процента. |
| int [get_PercentPositivePattern](./get_percentpositivepattern/)() const | Возвращает шаблон положительного процента. |
| [String](../../system/string/) [get_PercentSymbol](./get_percentsymbol/)() const | Возвращает символ процента. |
| [String](../../system/string/) [get_PerMilleSymbol](./get_permillesymbol/)() const | Возвращает символ промилле. |
| [String](../../system/string/) [get_PositiveInfinitySymbol](./get_positiveinfinitysymbol/)() const | Возвращает символ положительной бесконечности. |
| [String](../../system/string/) [get_PositiveSign](./get_positivesign/)() const | Возвращает знак плюс. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру данных счётчика ссылок, связанную с объектом. |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [GetFormat](./getformat/)(const [TypeInfo](../../system/typeinfo/)\&) override | Возвращает форматтер определённого типа. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [GetInstance](./getinstance/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Возвращает форматтер, связанный с поставщиком формата. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [NumberFormatInfo](./numberformatinfo/)() | Конструктор по умолчанию (инвариантный [NumberFormatInfo](./)). |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать построение подклассов. |
| [NumberFormatInfo](./)\& [operator=](./operator_equal/)(const [NumberFormatInfo](./)\&) |  |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать построение подклассов. |
| static [NumberFormatInfoPtr](../numberformatinfoptr/) [ReadOnly](./readonly/)([NumberFormatInfoPtr](../numberformatinfoptr/)) | Возвращает неизменяемую версию форматтера. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_CurrencyDecimalDigits](./set_currencydecimaldigits/)(int) | Устанавливает количество десятичных знаков валюты. |
| void [set_CurrencyDecimalSeparator](./set_currencydecimalseparator/)(const [String](../../system/string/)\&) | Устанавливает десятичный разделитель валюты. |
| void [set_CurrencyGroupSeparator](./set_currencygroupseparator/)(const [String](../../system/string/)\&) | Устанавливает разделитель разрядов валюты. |
| void [set_CurrencyGroupSizes](./set_currencygroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Устанавливает количество десятичных знаков валюты в группе. |
| void [set_CurrencyNegativePattern](./set_currencynegativepattern/)(int) | Устанавливает шаблон отрицательной валюты. |
| void [set_CurrencyPositivePattern](./set_currencypositivepattern/)(int) | Устанавливает шаблон положительной валюты. |
| void [set_CurrencySymbol](./set_currencysymbol/)(const [String](../../system/string/)\&) | Устанавливает символ валюты. |
| void [set_DigitSubstitution](./set_digitsubstitution/)([DigitShapes](../digitshapes/)) | Устанавливает значение, определяющее отображение формы цифры. |
| void [set_NaNSymbol](./set_nansymbol/)(const [String](../../system/string/)\&) | Устанавливает символ Not-a-Number. |
| void [set_NativeDigits](./set_nativedigits/)(const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Устанавливает символы цифр (от 0 до 9). |
| void [set_NegativeInfinitySymbol](./set_negativeinfinitysymbol/)(const [String](../../system/string/)\&) | Устанавливает символ отрицательной бесконечности. |
| void [set_NegativeSign](./set_negativesign/)(const [String](../../system/string/)\&) | Устанавливает знак минуса. |
| void [set_NumberDecimalDigits](./set_numberdecimaldigits/)(int) | Устанавливает количество десятичных знаков. |
| void [set_NumberDecimalSeparator](./set_numberdecimalseparator/)(const [String](../../system/string/)\&) | Устанавливает десятичный разделитель. |
| void [set_NumberGroupSeparator](./set_numbergroupseparator/)(const [String](../../system/string/)\&) | Устанавливает разделитель разрядов числа. |
| void [set_NumberGroupSizes](./set_numbergroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Устанавливает количество цифр в группе. |
| void [set_NumberNegativePattern](./set_numbernegativepattern/)(int) | Устанавливает шаблон отрицательного числа. |
| void [set_PercentDecimalDigits](./set_percentdecimaldigits/)(int) | Устанавливает количество десятичных знаков в процентных значениях. |
| void [set_PercentDecimalSeparator](./set_percentdecimalseparator/)(const [String](../../system/string/)\&) | Устанавливает десятичный разделитель в процентных значениях. |
| void [set_PercentGroupSeparator](./set_percentgroupseparator/)(const [String](../../system/string/)\&) | Устанавливает разделитель групп в процентных значениях. |
| void [set_PercentGroupSizes](./set_percentgroupsizes/)(const [ArrayPtr](../../system/arrayptr/)\<int\>\&) | Устанавливает количество цифр в группе процентных значений. |
| void [set_PercentNegativePattern](./set_percentnegativepattern/)(int) | Устанавливает шаблон отрицательного процента. |
| void [set_PercentPositivePattern](./set_percentpositivepattern/)(int) | Устанавливает шаблон положительного процента. |
| void [set_PercentSymbol](./set_percentsymbol/)(const [String](../../system/string/)\&) | Устанавливает символ процента. |
| void [set_PerMilleSymbol](./set_permillesymbol/)(const [String](../../system/string/)\&) | Устанавливает символ промилле. |
| void [set_PositiveInfinitySymbol](./set_positiveinfinitysymbol/)(const [String](../../system/string/)\&) | Устанавливает символ положительной бесконечности. |
| void [set_PositiveSign](./set_positivesign/)(const [String](../../system/string/)\&) | Устанавливает знак плюс. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-охранитель [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Очищает все внутренние структуры данных. |

## Смотрите также

* Класс [Object](../../system/object/)
* Класс [IFormatProvider](../../system/iformatprovider/)
* Класс [ICloneable](../../system/icloneable/)
* Пространство имён [System::Globalization](../)
* Библиотека [Aspose.Slides](../../)