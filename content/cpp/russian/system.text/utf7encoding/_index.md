---
title: UTF7Encoding
second_title: API-справочник Aspose.Slides для C++
description: "Кодировка UTF-7. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа на стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи в функции в качестве аргумента."
type: docs
weight: 365
url: /ru/system.text/utf7encoding/
---
## Класс UTF7Encoding

UTF-7 encoding. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class UTF7Encoding : public System::Text::Encoding
```

## Методы

| Method | Описание |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Клонирует объект кодировки. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Преобразует байты между двумя кодировками. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Преобразует байты между двумя кодировками. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Сравнивает с объектом. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, при котором два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Получает кодировку ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Получает стандартный объект кодировки Unicode с порядком байтов big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Получает стандартный объект кодировки UTF-32 с порядком байтов big-endian. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Получает имя кодировки, совместимое с телом почтового агента. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Получает [Windows](../../system.windows/) идентификатор кодовой страницы. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Получает резервный декодер. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Получает кодировку по умолчанию. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Получает резервный кодировщик. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Получает человекочитаемое имя кодировки. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Получает имя кодировки, совместимое с заголовком почтового агента. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Проверяет, может ли кодировка использоваться в браузере для отображения содержимого. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Проверяет, может ли кодировка использоваться в браузере для сохранения содержимого. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Проверяет, может ли кодировка использоваться в почтовом клиенте для отображения содержимого. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Проверяет, может ли кодировка использоваться в почтовом клиенте для сохранения содержимого. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Проверяет, является ли кодировка только для чтения. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Проверяет, является ли кодировка однобайтовой. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Получает кодировку Latin1. ДЛЯ ВНУТРЕННЕГО ИСПОЛЬЗОВАНИЯ. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Получает стандартный объект кодировки Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Получает стандартный объект кодировки UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Получает стандартный объект кодировки UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Только для внутреннего использования библиотеками классов: без маркировки и без проверки ввода. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Получает имя кодировки, совместимое с IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Получает [Windows](../../system.windows/) идентификатор кодовой страницы. |
| int [GetByteCount](./getbytecount/)(const char_t *, int) override | Получает количество символов, необходимых для кодирования буфера символов. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Получает количество символов, необходимых для кодирования буфера символов. |
| virtual int [GetByteCount](./getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | Получает количество символов, необходимых для кодирования буфера символов. |
| int [GetByteCount](./getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Получает количество символов, необходимых для кодирования буфера символов. |
| virtual int [GetByteCount](./getbytecount/)(const [String](../../system/string/)\&) | Получает количество символов, необходимых для кодирования строки. |
| virtual int [GetByteCount](./getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Получает количество символов, необходимых для кодирования буфера символов. |
| virtual int [GetByteCount](./getbytecount/)(const char_t *, int) | Получает количество символов, необходимых для кодирования буфера символов. |
| int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Получает байты, полученные при кодировании буфера символов. |
| int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) override | Получает байты, полученные при кодировании буфера символов. |
| int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) override | Получает байты, полученные при кодировании буфера символов. |
| virtual int [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Получает байты, полученные при кодировании буфера символов. |
| virtual int [GetBytes](./getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Получает байты, полученные при кодировании буфера символов. |
| int [GetBytes](./getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Получает байты, полученные при кодировании буфера символов. |
| virtual int [GetBytes](./getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Получает байты, полученные при кодировании буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const [String](../../system/string/)\&) | Получает байты, полученные при кодировании буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Получает байты, полученные при кодировании буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Получает байты, полученные при кодировании буфера символов. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Получает байты, полученные при кодировании буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](./getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Получает байты, полученные при кодировании буфера символов. |
| virtual int [GetBytes](./getbytes/)(const char_t *, int, **uint8_t** *, int) | Получает байты, полученные при кодировании буфера символов. |
| int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Получает количество символов, необходимых для декодирования буфера байтов. |
| int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) override | Получает количество символов, необходимых для декодирования буфера байтов. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Получает количество символов, необходимых для декодирования буфера байтов. |
| virtual int [GetCharCount](./getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Получает количество символов, необходимых для декодирования буфера байтов. |
| virtual int [GetCharCount](./getcharcount/)(const **uint8_t** *, int) | Получает количество символов, необходимых для декодирования буфера байтов. |
| int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) override | Получает символы, полученные при декодировании буфера байтов. |
| int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) override | Получает символы, полученные при декодировании буфера байтов. |
| virtual int [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Получает символы, полученные при декодировании буфера байтов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Получает символы, полученные при декодировании буфера байтов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](./getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Получает символы, полученные при декодировании буфера байтов. |
| virtual int [GetChars](./getchars/)(const **uint8_t** *, int, char_t *, int) | Получает символы, полученные при декодировании буфера байтов. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](./getdecoder/)() override | Получает декодер, который перенаправляет запросы к этому объекту. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](./getencoder/)() override | Получает кодировщик, который перенаправляет запросы к этому объекту. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Получает кодировку по имени. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Получает кодировку по кодовой странице. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Получает кодировку по кодовой странице. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Получает кодировку по имени. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Получает список известных кодировок. |
| int [GetHashCode](./gethashcode/)() const override | Получает хеш-код кодировки. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Получает максимальное количество байтов, необходимых для кодирования заданного количества символов. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Получает максимальное количество символов, необходимых для декодирования заданного количества байтов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](../encoding/getpreamble/)() | Возвращает последовательность байтов, обозначающих кодировку (например, BOM). |
| [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) override | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](./getstring/)(**uint8_t** *, int) | Декодирует буфер байтов в строку. |
| [String](../../system/string/) [GetString](./getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Декодирует буфер байтов в строку. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](./getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](./getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Декодирует буфер байтов в строку. |
| [String](../../system/string/) [GetString](./getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Декодирует буфер байтов в строку. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте сторожевой объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| **bool** [operator==](./operator_equal_equal/)(const [UTF7Encoding](./)\&) const | Сравнивает параметры кодировок. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Устанавливает резервный декодер. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Устанавливает резервный кодировщик. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает значение счётчика общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте сторожевой объект [LockContext](../../system/lockcontext/). |
|  [UTF7Encoding](./utf7encoding/)() | Конструктор. |
|  [UTF7Encoding](./utf7encoding/)(**bool**) | Конструктор. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Значение кодовой страницы по умолчанию. |
| static constexpr [UTF7_CODE_PAGE](./utf7_code_page/) | Магическое число, используемое [Windows](../../system.windows/) для идентификатора кодовой страницы UTF-7. |

## См. также

* Класс [Encoding](../encoding/)
* Пространство имён [System::Text](../)
* Библиотека [Aspose.Slides](../../)