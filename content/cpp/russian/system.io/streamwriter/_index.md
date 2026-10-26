---
title: StreamWriter
second_title: Справочник API Aspose.Slides для C++
description: "Представляет writer, который записывает символы в поток байтов. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 391
url: /ru/system.io/streamwriter/
---
## StreamWriter класс

Представляет writer, который записывает символы в поток байтов. Объекты этого класса следует создавать только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class StreamWriter : public System::IO::TextWriter
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Close](./close/)() override | Закрывает поток и освобождает приобретённые ресурсы. |
| void [Dispose](./dispose/)() override | Освобождает все ресурсы, используемые текущим объектом, и закрывает базовый поток. |
| virtual void [Dispose](./dispose/)(**bool**) | Освобождает все ресурсы, используемые текущим объектом, и закрывает базовый поток. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| void [Flush](./flush/)() override | Сбрасывает содержимое буфера в базовый поток, а затем сбрасывает базовый поток. |
| **bool** [get_AutoFlush](./get_autoflush/)() const | Возвращает значение, указывающее, будет ли [StreamWriter](./) сбрасывать данные в базовый поток каждый раз при вызове метода [StreamWriter::Write](./write/). |
| [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\> [get_BaseStream](./get_basestream/)() const | Возвращает shared-pointer к объекту, представляющему базовый поток. |
| [EncodingPtr](../../system/encodingptr/) [get_Encoding](./get_encoding/)() override | Возвращает текущую используемую кодировку. |
| virtual [SharedPtr](../../system/sharedptr/)\<[IFormatProvider](../../system/iformatprovider/)\> [get_FormatProvider](../textwriter/get_formatprovider/)() const | Возвращает текущий используемый объект [IFormatProvider](../../system/iformatprovider/). |
| [IFormatProviderPtr](../../system/iformatproviderptr/) [get_FormatProvider](../textwriter/get_formatprovider/)() | Возвращает текущий используемый объект [IFormatProvider](../../system/iformatprovider/). |
| virtual [System::String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() const | Возвращает строку-разделитель строк. |
| [String](../../system/string/) [get_NewLine](../textwriter/get_newline/)() | Возвращает строку-разделитель строк. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хэшировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# `is`. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналогичную оператору C# `lock()`. Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместно используемых ссылок на указанное значение. |
| void [set_AutoFlush](./set_autoflush/)(**bool**) | Возвращает значение, указывающее, следует ли [StreamWriter](./) сбрасывать данные в базовый поток каждый раз при вызове метода [StreamWriter::Write](./write/). |
| virtual void [set_NewLine](../textwriter/set_newline/)(const [System::String](../../system/string/)\&) | Устанавливает строку-разделитель строк. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Делает n-й шаблонный аргумент слабым указателем (вместо shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместно используемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместно используемых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместно используемых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&) | Конструирует экземпляр объекта [StreamWriter](./), который записывает символы в указанный базовый поток, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&) | Конструирует экземпляр объекта [StreamWriter](./), который записывает символы в указанный базовый поток, используя заданную кодировку и буфер размером по умолчанию 1024 байта. |
|  [StreamWriter](./streamwriter/)(const [SharedPtr](../../system/sharedptr/)\<[Stream](../stream/)\>\&, const [EncodingPtr](../../system/encodingptr/)\&, int, **bool**) | Конструирует экземпляр объекта [StreamWriter](./), который записывает символы в указанный базовый поток, используя заданную кодировку и буфер указанного размера. Параметр определяет, следует ли закрывать базовый поток при освобождении объекта [StreamWriter](./). |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&) | Конструирует экземпляр объекта [StreamWriter](./), который записывает символы в указанный файл, используя кодировку UTF-8 и буфер размером по умолчанию 1024 байта. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&) | Конструирует экземпляр объекта [StreamWriter](./), который записывает символы в указанный файл, используя заданную кодировку и буфер размером по умолчанию 1024 байта. Параметр определяет, следует ли добавлять данные в файл или перезаписывать его. |
|  [StreamWriter](./streamwriter/)(const [String](../../system/string/)\&, **bool**, const [EncodingPtr](../../system/encodingptr/)\&, int) | Конструирует экземпляр объекта [StreamWriter](./), который записывает символы в указанный файл, используя заданную кодировку и размер буфера. Параметр определяет, следует ли добавлять данные в файл или перезаписывать его. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# `typeof([System.Object](../../system/object/))`. |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналогичную оператору C# `lock()`. Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [Write](./write/)(char_t) override | Записывает указанный символ в поток. |
| void [Write](./write/)(const [String](../../system/string/)\&) override | Записывает указанную строку в поток. |
| void [Write](./write/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Записывает строковое представление указанного объекта в поток. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Записывает все символы из указанного массива в поток. |
| void [Write](./write/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Записывает указанный поддиапазон UTF-16 символов из указанного массива символов в поток. |
| void [Write](./write/)(const char_t *) override | Записывает указанную C-строку в поток. |
| void [Write](./write/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Записывает строковое представление указанного объекта в поток. |
| virtual void [Write](../textwriter/write/)(**bool**) | Записывает строковое представление указанного булевого значения в поток. |
| virtual void [Write](../textwriter/write/)([Decimal](../../system/decimal/)) | Записывает строковое представление указанного объекта [Decimal](../../system/decimal/) в поток. |
| virtual void [Write](../textwriter/write/)(**double**) | Записывает строковое представление указанного двойного точного значения с плавающей запятой в поток. |
| virtual void [Write](../textwriter/write/)(int) | Записывает строковое представление указанного 32-битного целого значения в поток. |
| virtual void [Write](../textwriter/write/)(**int64_t**) | Записывает строковое представление указанного 64-битного целого значения в поток. |
| virtual void [Write](../textwriter/write/)(**float**) | Записывает строковое представление указанного одинарного точного значения с плавающей запятой в поток. |
| virtual void [Write](../textwriter/write/)(**uint32_t**) | Записывает строковое представление указанного беззнакового 32-битного целого значения в поток. |
| virtual void [Write](../textwriter/write/)(**uint64_t**) | Записывает строковое представление указанного беззнакового 64-битного целого значения в поток. |
| virtual void [Write](../textwriter/write/)(const [TypeInfo](../../system/typeinfo/)\&) | Записывает строковое представление указанного объекта [TypeInfo](../../system/typeinfo/) в поток. |
| void [Write](../textwriter/write/)(const [String](../../system/string/)\&, const TArgs\&...) | Записывает указанные значения, отформатированные согласно заданному формату, в поток. |
| void [WriteLine](./writeline/)() override | Записывает символы-разделители строк в поток. |
| void [WriteLine](./writeline/)(const [String](../../system/string/)\&) override | Записывает указанную строку, а затем символы-разделители строк, в поток. |
| void [WriteLine](./writeline/)(const [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) override | Записывает строковое представление указанного объекта, а затем символы-разделители строк, в поток. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&) override | Записывает все символы из указанного массива, а затем символы-разделители строк, в поток. |
| void [WriteLine](./writeline/)(const [ArrayPtr](../../system/arrayptr/)\<char_t\>\&, **int32_t**, **int32_t**) override | Записывает указанный поддиапазон UTF-16 символов из указанного массива, а затем символы-разделители строк, в поток. |
| void [WriteLine](./writeline/)(const char_t *) override | Записывает указанную C-строку, а затем символы-разделители строк, в поток. |
| void [WriteLine](./writeline/)(const [System::SharedPtr](../../system/sharedptr/)\<T\>\&) | Записывает строковое представление указанного объекта, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**bool**) | Записывает строковое представление указанного булевого значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(char_t) | Записывает указанный символ, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)([Decimal](../../system/decimal/)) | Записывает строковое представление указанного объекта [Decimal](../../system/decimal/), а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**double**) | Записывает строковое представление указанного двойного точного значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(int) | Записывает строковое представление указанного 32-битного целого значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**int64_t**) | Записывает строковое представление указанного 64-битного целого значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**float**) | Записывает строковое представление указанного одинарного точного значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint32_t**) | Записывает строковое представление указанного беззнакового 32-битного целого значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(**uint64_t**) | Записывает строковое представление указанного беззнакового 64-битного целого значения, а затем символы-разделители строк, в поток. |
| virtual void [WriteLine](../textwriter/writeline/)(const [TypeInfo](../../system/typeinfo/)\&) | Записывает строковое представление указанного объекта [TypeInfo](../../system/typeinfo/), а затем символы-разделители строк, в поток. |
| void [WriteLine](../textwriter/writeline/)(const [String](../../system/string/)\&, const TArgs\&...) | Записывает указанные значения, отформатированные согласно заданному формату, затем символы-разделители строк, в поток. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
|  [~StreamWriter](./~streamwriter/)() | Деструктор. |
| virtual  [~TextWriter](../textwriter/~textwriter/)() | Деструктор. |

## Смотрите также

* Класс [TextWriter](../textwriter/)
* Пространство имён [System::IO](../)
* Библиотека [Aspose.Slides](../../)