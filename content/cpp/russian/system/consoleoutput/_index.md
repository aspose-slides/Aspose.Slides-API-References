---
title: ConsoleOutput
second_title: Справочник API Aspose.Slides для C++
description: "Представляет стандартный поток вывода. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 209
url: /ru/system/consoleoutput/
---
## ConsoleOutput класс

Представляет стандартный поток вывода. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ConsoleOutput : public System::IO::TextWriter
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [Close](../../system.io/textwriter/close/)() | Закрывает поток и освобождает полученные ресурсы. |
| void [Dispose](../../system.io/textwriter/dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает базовый поток. |
| virtual **bool** [Equals](../object/equals/)([ptr](../object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../object/equals/). |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T1\>::value\&&[IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual void [Flush](../../system.io/textwriter/flush/)() | Сбрасывает содержимое буфера в базовый поток. |
| [SharedPtr](../sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() override | Всегда возвращает кодировку ASCII. |
| virtual [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\> [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() const | Возвращает текущий используемый объект [IFormatProvider](../iformatprovider/). |
| [IFormatProviderPtr](../iformatproviderptr/) [get_FormatProvider](../../system.io/textwriter/get_formatprovider/)() | Возвращает текущий используемый объект [IFormatProvider](../iformatprovider/). |
| virtual [System::String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() const | Возвращает строку, которая является разделителем строк. |
| [String](../string/) [get_NewLine](../../system.io/textwriter/get_newline/)() | Возвращает строку, которая является разделителем строк. |
| Detail::SmartPtrCounter * [GetCounter](../object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../object/gethashcode/). Позволяет вычислять хэш для пользовательских объектов. |
| virtual const [TypeInfo](../typeinfo/)\& [GetType](../object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../object/gettype/). |
| virtual **bool** [Is](../object/is/)(const [TypeInfo](../typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
| virtual [ptr](../object/ptr/) [MemberwiseClone](../object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../object/object/)([Object](../object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../object/)\& [operator=](../object/operator_equal/)([Object](../object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../object/referenceequals/)([ptr](../object/ptr/) const\&, [ptr](../object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект значимого типа с nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../object/referenceequals/)([String](../string/) const\&, [String](../string/) const\&) | Специализация [Object::ReferenceEquals](../object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| virtual void [set_NewLine](../../system.io/textwriter/set_newline/)(const [System::String](../string/)\&) | Устанавливает строку-разделитель строк. |
| virtual void [SetTemplateWeakPtr](../object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../object/sharedcount/)() const | Возвращает текущее значение счётчика общих ссылок. |
| [Object](../object/) * [SharedRefAdded](../object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../string/) [ToString](../object/tostring/)() const | Аналог метода C# [Object.ToString()](../object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../typeinfo/)\& [Type](../object/type/)() | Реализует конструкцию C# typeof([System.Object](../object/)). |
| void [Unlock](../object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [Write](./write/)(**bool**) override | Выводит строковое представление указанного булевого значения в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Выводит строковое представление указанного объекта в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(char_t) override | Выводит указанный символ в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)([Decimal](../decimal/)) override | Выводит строковое представление значения [Decimal](../decimal/) в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(**double**) override | Выводит строковое представление double-значения в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(**int32_t**) override | Выводит строковое представление 32-битного целого значения в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(**int64_t**) override | Выводит строковое представление 64-битного целого значения в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(**float**) override | Выводит строковое представление float-значения в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(const [String](../string/)\&) override | Выводит указанный объект строки в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(**uint32_t**) override | Выводит строковое представление беззнакового 32-битного целого значения в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(**uint64_t**) override | Выводит строковое представление беззнакового 64-битного целого значения в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Выводит строковое представление указанного массива символов в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Выводит строковое представление диапазона значений указанного массива символов в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(const char_t *) override | Выводит указанный C-строку в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(const [TypeInfo](../typeinfo/)\&) override | Выводит строковое представление указанного объекта [TypeInfo](../typeinfo/) в поток вывода, представляемый текущим объектом. |
| void [Write](./write/)(const char *) |  |
| virtual void [Write](../../system.io/textwriter/write/)(int) | Записывает строковое представление указанного 32-битного целого значения в поток. |
| void [Write](../../system.io/textwriter/write/)(const [String](../string/)\&, const TArgs\&...) | Записывает указанные значения, отформатированные согласно заданному формату, в поток. |
| void [WriteLine](./writeline/)() override | Выводит текущий разделитель строк в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) override | Выводит строковое представление указанного объекта, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(**bool**) override | Выводит строковое представление указанного булевого значения, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(char_t) override | Выводит указанный символ, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)([Decimal](../decimal/)) override | Выводит строковое представление значения [Decimal](../decimal/), за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(**double**) override | Выводит строковое представление double-значения, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(int) override | Выводит строковое представление 32-битного целого, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(**int64_t**) override | Выводит строковое представление 64-битного целого, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(**float**) override | Выводит строковое представление float-значения, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(const [String](../string/)\&) override | Выводит указанный объект строки, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(**uint32_t**) override | Выводит строковое представление беззнакового 32-битного целого, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(**uint64_t**) override | Выводит строковое представление беззнакового 64-битного целого, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&) override | Выводит строковое представление указанного массива символов, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Выводит строковое представление диапазона значений указанного массива символов, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(const char_t *) override | Выводит указанный C-строку, за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(const [TypeInfo](../typeinfo/)\&) override | Выводит строковое представление указанного объекта [TypeInfo](../typeinfo/), за которым следует текущий разделитель строк, в поток вывода, представляемый текущим объектом. |
| void [WriteLine](./writeline/)(const char *) |  |
| void [WriteLine](../../system.io/textwriter/writeline/)(const [String](../string/)\&, const TArgs\&...) | Записывает указанные значения, отформатированные согласно заданному формату, с последующими символами завершения строки, в поток. |
| virtual  [~Object](../object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
| virtual  [~TextWriter](../../system.io/textwriter/~textwriter/)() | Деструктор. |

## См. также

* Класс [TextWriter](../../system.io/textwriter/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)