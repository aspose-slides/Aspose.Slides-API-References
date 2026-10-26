---
title: StringWriter
second_title: "Aspose.Slides для справочника API C++"
description: "Реализует TextWriter, который записывает информацию в строку. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никак не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам во время выполнения и/или сбоям проверок. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 417
url: /ru/system.io/stringwriter/
---
## StringWriter класс

Implements a [TextWriter](../textwriter/) that writes information to a string. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class StringWriter : public System::IO::TextWriter
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [Close](../textwriter/close/)() | Закрывает поток и освобождает полученные ресурсы. |
| void [Dispose](../textwriter/dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает базовый поток. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| virtual void [Flush](../textwriter/flush/)() | Сбрасывает содержимое буфера в базовый поток. |
| [SharedPtr](../../system/sharedptr/)\<[Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Возвращает текущую используемую кодировку. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Возвращает текущий используемый объект [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Возвращает текущий используемый объект [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Возвращает строку-разделитель строк. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Возвращает строку-разделитель строк. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\> [GetStringBuilder](./getstringbuilder/)() | Возвращает текущий используемый StringBuilder. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Устанавливает строку-разделитель строк. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый аргумент шаблона как слабый указатель (вместо разделяемого). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&, const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Создаёт новый экземпляр [StringWriter](./) с использованием указанного StringBuilder и [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)(const [System::SharedPtr](../../system/sharedptr/)\<[Text::StringBuilder](../../system.text/stringbuilder/)\>\&) | Создаёт новый экземпляр [StringWriter](./) с использованием указанного StringBuilder и [IFormatProvider](../../system/iformatprovider/) из текущей культуры. |
|  [StringWriter](./stringwriter/)(const [IFormatProviderPtr](../../system/iformatproviderptr/)\&) | Создаёт новый экземпляр [StringWriter](./) с использованием указанного [IFormatProvider](../../system/iformatprovider/). |
|  [StringWriter](./stringwriter/)() | Создаёт новый экземпляр [StringWriter](./) с использованием [IFormatProvider](../../system/iformatprovider/) из текущей культуры. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Возвращает базовую строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Write](./write/)(char_t) override | Записывает указанный символ в поток. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Записывает указанный поддиапазон символов из указанного массива символов в поток. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Записывает указанную строку в поток. |
| virtual void [Write](../textwriter/write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Записывает строковое представление указанного объекта в поток. |
| virtual void [Write](../textwriter/write/)(**bool**) | Записывает строковое представление указанного логического значения в поток. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Записывает строковое представление указанного объекта [Decimal](../../system/decimal/) в поток. |
| virtual void [Write](../textwriter/write/)(**double**) | Записывает строковое представление указанного двойного точного числа с плавающей точкой в поток. |
| virtual void [Write](../textwriter/write/)(int) | Записывает строковое представление указанного 32-битного целого числа в поток. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Записывает строковое представление указанного 64-битного целого числа в поток. |
| virtual void [Write](../textwriter/write/)(**float**) | Записывает строковое представление указанного одинарного числа с плавающей точкой в поток. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Записывает строковое представление указанного беззнакового 32-битного целого числа в поток. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Записывает строковое представление указанного беззнакового 64-битного целого числа в поток. |
| virtual void [Write](../textwriter/write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Записывает все символы из указанного массива в поток. |
| virtual void [Write](../textwriter/write/)(const char_t *) | Записывает указанную C-строку в поток. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Записывает строковое представление указанного объекта [TypeInfo](../../system/typeinfo/) в поток. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Записывает указанные значения, отформатированные согласно заданному формату, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)() | Записывает символы-разделители строк в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Записывает строковое представление указанного объекта, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Записывает строковое представление указанного логического значения, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Записывает указанный символ, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Записывает строковое представление указанного объекта [Decimal](../../system/decimal/), за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Записывает строковое представление указанного двойного точного числа с плавающей точкой, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Записывает строковое представление указанного 32-битного целого числа, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Записывает строковое представление указанного 64-битного целого числа, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Записывает строковое представление указанного одинарного числа с плавающей точкой, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&) | Записывает указанную строку, за которой следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Записывает строковое представление указанного беззнакового 32-битного целого числа, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Записывает строковое представление указанного беззнакового 64-битного целого числа, за которым следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Записывает все символы из указанного массива, за которыми следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Записывает указанный поддиапазон UTF-16 символов из указанного массива символов, за которыми следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(const char_t *) | Записывает указанную C-строку, за которой следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Записывает строковое представление указанного объекта [TypeInfo](../../system/typeinfo/), за которым следуют символы-разделители строк, в поток. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Записывает указанные значения, отформатированные согласно заданному формату, за которыми следуют символы-разделители строк, в поток. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Деструктор. |

## Смотрите также

* Класс [TextWriter](../textwriter/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)