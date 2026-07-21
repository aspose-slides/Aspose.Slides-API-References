---
title: UnicodeEncoding
second_title: Aspose.Slides для C++ — справка API
description: "Кодировка Unicode. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте его для передачи в функции в качестве аргумента."
type: docs
weight: 339
url: /ru/system.text/unicodeencoding/
---
## UnicodeEncoding класс

Кодировка Unicode. Экземпляры этого класса следует выделять только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляры этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class UnicodeEncoding : public System::Text::ICUEncoding
```

## Методы

| Method | Description |
| --- | --- |
| [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\> [Clone](./clone/)() override | Клонирует объект кодировки. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&) | Преобразует байты между двумя кодировками. |
| static [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [Convert](../encoding/convert/)(const [EncodingPtr](../../system/encodingptr/)\&, const [EncodingPtr](../../system/encodingptr/)\&, const [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>\&, int, int) | Преобразует байты между двумя кодировками. |
| **bool** [Equals](./equals/)([SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Сравнивает кодировки. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| static [EncodingPtr](../../system/encodingptr/) [get_ASCII](../encoding/get_ascii/)() | Получает кодировку ASCII. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUnicode](../encoding/get_bigendianunicode/)() | Получает объект стандартной кодировки Unicode с порядком байтов big-endian. |
| static [EncodingPtr](../../system/encodingptr/) [get_BigEndianUTF32](../encoding/get_bigendianutf32/)() | Получает объект стандартной кодировки UTF-32 с порядком байтов big-endian. |
| virtual [String](../../system/string/) [get_BodyName](../encoding/get_bodyname/)() | Получает имя кодировки, совместимое с телом почтового агента. |
| virtual int [get_CodePage](../encoding/get_codepage/)() | Получает [Windows](../../system.windows/) идентификатор кодовой страницы. |
| [DecoderFallbackPtr](../../system/decoderfallbackptr/) [get_DecoderFallback](../encoding/get_decoderfallback/)() const | Получает запасной декодер. |
| static [EncodingPtr](../../system/encodingptr/) [get_Default](../encoding/get_default/)() | Получает кодировку по умолчанию. |
| const [EncoderFallbackPtr](../../system/encoderfallbackptr/) [get_EncoderFallback](../encoding/get_encoderfallback/)() const | Получает запасной кодировщик. |
| virtual [String](../../system/string/) [get_EncodingName](../encoding/get_encodingname/)() | Получает человекочитаемое имя кодировки. |
| virtual [String](../../system/string/) [get_HeaderName](../encoding/get_headername/)() | Получает имя кодировки, совместимое с заголовком почтового агента. |
| virtual **bool** [get_IsBrowserDisplay](../encoding/get_isbrowserdisplay/)() | Проверяет, может ли кодировка быть использована в браузере для отображения содержимого. |
| virtual **bool** [get_IsBrowserSave](../encoding/get_isbrowsersave/)() | Проверяет, может ли кодировка быть использована в браузере для сохранения содержимого. |
| virtual **bool** [get_IsMailNewsDisplay](../encoding/get_ismailnewsdisplay/)() | Проверяет, может ли кодировка быть использована в почтовом клиенте для отображения содержимого. |
| virtual **bool** [get_IsMailNewsSave](../encoding/get_ismailnewssave/)() | Проверяет, может ли кодировка быть использована в почтовом клиенте для сохранения содержимого. |
| **bool** [get_IsReadOnly](../encoding/get_isreadonly/)() | Проверяет, является ли кодировка только для чтения. |
| virtual **bool** [get_IsSingleByte](../encoding/get_issinglebyte/)() | Проверяет, является ли кодировка однобайтовой. |
| static [EncodingPtr](../../system/encodingptr/) [get_Latin1](../encoding/get_latin1/)() | Получает кодировку Latin1. FOR INTERNAL USE. |
| static [EncodingPtr](../../system/encodingptr/) [get_Unicode](../encoding/get_unicode/)() | Получает объект стандартной кодировки Unicode. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF32](../encoding/get_utf32/)() |  |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF7](../encoding/get_utf7/)() | Получает объект стандартной кодировки UTF-7. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8](../encoding/get_utf8/)() | Получает объект стандартной кодировки UTF-8. |
| static [EncodingPtr](../../system/encodingptr/) [get_UTF8Unmarked](../encoding/get_utf8unmarked/)() | Только для внутреннего использования, предназначено библиотекам классов: без маркировки и без проверки ввода. |
| virtual [String](../../system/string/) [get_WebName](../encoding/get_webname/)() | Получает имя кодировки, совместимое с IANA. |
| virtual int [get_WindowsCodePage](../encoding/get_windowscodepage/)() | Получает [Windows](../../system.windows/) идентификатор кодовой страницы. |
| int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) override | Получает количество символов, необходимых для кодирования буфера символов. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(System::Details::ArrayView\<char_t\>, int, int) | RTTI. |
| int [GetByteCount](../icuencoding/getbytecount/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const [String](../../system/string/)\&) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | RTTI. |
| virtual int [GetByteCount](../icuencoding/getbytecount/)(const char_t *, int) | RTTI. |
| int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) override | Получает байты, полученные в результате кодирования буфера символов. |
| virtual int [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Получает байты, полученные в результате кодирования буфера символов. |
| virtual int [GetBytes](../icuencoding/getbytes/)(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<**uint8_t**\>, int) | Получает байты, полученные в результате кодирования буфера символов. |
| int [GetBytes](../icuencoding/getbytes/)(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<**uint8_t**, SB\>\&, int) | Получает байты, полученные в результате кодирования буфера символов. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&, int, int, [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int) | Получает байты, полученные в результате кодирования буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const [String](../../system/string/)\&) | Получает байты, полученные в результате кодирования буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>, int, int) | Получает байты, полученные в результате кодирования буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::ArrayView\<char_t\>\&, int, int) | Получает байты, полученные в результате кодирования буфера символов. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)(const System::Details::StackArray\<char_t, N\>\&, int, int) | Получает байты, полученные в результате кодирования буфера символов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetBytes](../icuencoding/getbytes/)([ArrayPtr](../../system/arrayptr/)\<char_t\>) | Получает байты, полученные в результате кодирования буфера символов. |
| virtual int [GetBytes](../icuencoding/getbytes/)(const char_t *, int, **uint8_t** *, int) | Получает байты, полученные в результате кодирования буфера символов. |
| int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) override | Получает количество символов, необходимых для декодирования буфера байтов. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Получает количество символов, необходимых для декодирования буфера байтов. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Получает количество символов, необходимых для декодирования буфера байтов. |
| virtual int [GetCharCount](../icuencoding/getcharcount/)(const **uint8_t** *, int) | Получает количество символов, необходимых для декодирования буфера байтов. |
| int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) override | Получает символы, полученные в результате декодирования буфера байтов. |
| virtual int [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int, [ArrayPtr](../../system/arrayptr/)\<char_t\>, int) | Получает символы, полученные в результате декодирования буфера байтов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Получает символы, полученные в результате декодирования буфера байтов. |
| virtual [ArrayPtr](../../system/arrayptr/)\<char_t\> [GetChars](../icuencoding/getchars/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Получает символы, полученные в результате декодирования буфера байтов. |
| virtual int [GetChars](../icuencoding/getchars/)(const **uint8_t** *, int, char_t *, int) | Получает символы, полученные в результате декодирования буфера байтов. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| [DecoderPtr](../../system/decoderptr/) [GetDecoder](../icuencoding/getdecoder/)() override | Получает декодер, который перенаправляет запросы к этому объекту. |
| [EncoderPtr](../../system/encoderptr/) [GetEncoder](../icuencoding/getencoder/)() override | Получает кодировщик, который перенаправляет запросы к этому объекту. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&) | Получает кодировку по имени. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int) | Получает кодировку по кодовой странице. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(int, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Получает кодировку по кодовой странице. |
| static [EncodingPtr](../../system/encodingptr/) [GetEncoding](../encoding/getencoding/)(const [String](../../system/string/)\&, const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&, const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Получает кодировку по имени. |
| static [ArrayPtr](../../system/arrayptr/)\<[EncodingInfoPtr](../../system/encodinginfoptr/)\> [GetEncodings](../encoding/getencodings/)() | Получает список известных кодировок. |
| int [GetHashCode](./gethashcode/)() const override | Хеширует кодировку. |
| int [GetMaxByteCount](./getmaxbytecount/)(int) override | Получает максимальное количество байтов, необходимых для кодирования указанного количества символов. |
| int [GetMaxCharCount](./getmaxcharcount/)(int) override | Получает максимальное количество символов, необходимых для декодирования указанного количества байтов. |
| [ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [GetPreamble](./getpreamble/)() override | Возвращает последовательность байтов, обозначающую кодировку (например BOM). |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(**uint8_t** *, int) | Декодирует буфер байтов в строку. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(const [ReadOnlySpan](../../system/readonlyspan/)\<**uint8_t**\>\&) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&) | Декодирует буфер байтов в строку. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>\&) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)([ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>, int, int) | Декодирует буфер байтов в строку. |
| virtual [String](../../system/string/) [GetString](../encoding/getstring/)(const System::Details::ArrayView\<**uint8_t**\>\&, int, int) | Декодирует буфер байтов в строку. |
| [String](../../system/string/) [GetString](../encoding/getstring/)(System::Details::StackArray\<**uint8_t**, N\>, int, int) | Декодирует буфер байтов в строку. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
|  [ICUEncoding](../icuencoding/icuencoding/)(const Details::EncodingInfoInternal *) | Конструктор. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| **bool** [operator==](./operator_equal_equal/)(const [UnicodeEncoding](./)\&) const | Сравнивает кодировки по кодовым страницам и флагам. |
| **bool** [operator==](../icuencoding/operator_equal_equal/)(const [ICUEncoding](../icuencoding/)\&) const | Сравнивает кодировки, используя кодовые страницы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик разделяемых ссылок на указанное значение. |
| void [set_DecoderFallback](../encoding/set_decoderfallback/)(const [DecoderFallbackPtr](../../system/decoderfallbackptr/)\&) | Устанавливает запасной декодер. |
| void [set_EncoderFallback](../encoding/set_encoderfallback/)(const [EncoderFallbackPtr](../../system/encoderfallbackptr/)\&) | Устанавливает запасной кодировщик. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо разделяемого). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика разделяемых ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик разделяемых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
|  [UnicodeEncoding](./unicodeencoding/)() | Конструктор. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**) | Конструктор. |
|  [UnicodeEncoding](./unicodeencoding/)(**bool**, **bool**, **bool**) | Конструктор. |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывается напрямую или с использованием охранного объекта [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Field | Description |
| --- | --- |
| static constexpr [BIG_UNICODE_CODE_PAGE](./big_unicode_code_page/) | Номер кодовой страницы в порядке big-endian. |
| static constexpr [DEFAULT_CODE_PAGE](../encoding/default_code_page/) | Значение кодовой страницы по умолчанию. |
| static constexpr [UNICODE_CODE_PAGE](./unicode_code_page/) | Номер кодовой страницы в порядке little-endian. |

## См. также

* Класс [ICUEncoding](../icuencoding/)
* Пространство имён [System::Text](../)
* Библиотека [Aspose.Slides](../../)