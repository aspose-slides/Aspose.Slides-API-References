---
title: TextWriter
second_title: Aspose.Slides для C++ справка по API
description: "Базовый класс для классов, представляющих писатели, которые записывают последовательности символов в различные места назначения. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 443
url: /ru/system.io/textwriter/
---
## TextWriter класс

Базовый класс для классов, представляющих записи, которые записывают последовательности символов в различные назначения. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TextWriter : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual void [Close](./close/)() | Закрывает поток и освобождает приобретённые ресурсы. |
| void [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает базовый поток. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типовых значений в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| virtual void [Flush](./flush/)() | Сбрасывает содержимое буфера в базовый поток. |
| virtual [SharedPtr](../../system/sharedptr/)\<[System::Text::Encoding](../../system.text/encoding/)\> [get_Encoding](./get_encoding/)() | Возвращает текущую используемую кодировку. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](./get_formatprovider/)() const | Возвращает текущий используемый объект [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](./get_formatprovider/)() | Возвращает текущий используемый объект [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](./get_newline/)() const | Возвращает строку-разделитель. |
| [String](../../system/string/) [get_NewLine](./get_newline/)() | Возвращает строку-разделитель. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать при построении подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [set_NewLine](./set_newline/)(const [System::String](../../system/string/)\&) | Устанавливает строку-разделитель. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Записывает строковое представление указанного объекта в поток. |
| virtual void [Write](./write/)(**bool**) | Записывает строковое представление указанного булевого значения в поток. |
| virtual void [Write](./write/)(char_t) | Записывает указанный символ в поток. |
| virtual void [Write](./write/)([Decimal](../../system/decimal/)) | Записывает строковое представление указанного объекта [Decimal](../../system/decimal/) в поток. |
| virtual void [Write](./write/)(**double**) | Записывает строковое представление указанного double-значения в поток. |
| virtual void [Write](./write/)(int) | Записывает строковое представление указанного 32-битного целого значения в поток. |
| virtual void [Write](./write/)(**int64_t**) | Записывает строковое представление указанного 64-битного целого значения в поток. |
| virtual void [Write](./write/)(**float**) | Записывает строковое представление указанного float-значения в поток. |
| virtual void [Write](./write/)(const [String](../../system/string/)\&) | Записывает указанную строку в поток. |
| virtual void [Write](./write/)(**uint32_t**) | Записывает строковое представление указанного беззнакового 32-битного целого значения в поток. |
| virtual void [Write](./write/)(**uint64_t**) | Записывает строковое представление указанного беззнакового 64-битного целого значения в поток. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Записывает все символы из указанного массива в поток. |
| virtual void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Записывает указанный поддиапазон символов UTF-16 из указанного массива символов в поток. |
| virtual void [Write](./write/)(const char_t *) | Записывает указанную C-строку в поток. |
| virtual void [Write](./write/)(const [TypeInfo](../../system/typeinfo/)\&) | Записывает строковое представление указанного объекта [TypeInfo](../../system/typeinfo/) в поток. |
| void [Write](./write/)(const [String](../../system/string/)\&, const TArgs\&...) | Записывает указанные значения, форматированные согласно заданному формату, в поток. |
| virtual void [WriteLine](./writeline/)() | Записывает символы-разделители строк в поток. |
| virtual void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Записывает строковое представление указанного объекта, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](./writeline/)(**bool**) | Записывает строковое представление указанного булевого значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](./writeline/)(char_t) | Записывает указанный символ, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](./writeline/)([Decimal](../../system/decimal/)) | Записывает строковое представление указанного объекта [Decimal](../../system/decimal/) с последующим символом-разделителем строки в поток. |
| virtual void [WriteLine](./writeline/)(**double**) | Записывает строковое представление указанного double-значения с последующим символом-разделителем строки в поток. |
| virtual void [WriteLine](./writeline/)(int) | Записывает строковое представление указанного 32-битного целого значения с последующим символом-разделителем строки в поток. |
| virtual void [WriteLine](./writeline/)(**int64_t**) | Записывает строковое представление указанного 64-битного целого значения с последующим символом-разделителем строки в поток. |
| virtual void [WriteLine](./writeline/)(**float**) | Записывает строковое представление указанного float-значения с последующим символом-разделителем строки в поток. |
| virtual void [WriteLine](./writeline/)(const [String](../../system/string/)\&) | Записывает указанную строку, за которой следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](./writeline/)(**uint32_t**) | Записывает строковое представление указанного беззнакового 32-битного целого значения с последующим символом-разделителем строки в поток. |
| virtual void [WriteLine](./writeline/)(**uint64_t**) | Записывает строковое представление указанного беззнакового 64-битного целого значения с последующим символом-разделителем строки в поток. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) | Записывает все символы из указанного массива, за которыми следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) | Записывает указанный поддиапазон символов UTF-16 из указанного массива символов, за которыми следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](./writeline/)(const char_t *) | Записывает указанную C-строку, за которой следуют символы-разделители строк, в поток. |
| virtual void [WriteLine](./writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Записывает строковое представление указанного объекта [TypeInfo](../../system/typeinfo/) с последующим символом-разделителем строки в поток. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Записывает указанные значения, форматированные согласно заданному формату, с последующим символом-разделителем строки в поток. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
| virtual  [~TextWriter](./~textwriter/)() | Деструктор. |

## Типedefs

| Типedef | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к этому классу. |

## См. также

* Класс [IDisposable](../../system/idisposable/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)