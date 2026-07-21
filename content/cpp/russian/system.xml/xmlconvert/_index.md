---
title: XmlConvert
second_title: Справочник API Aspose.Slides для C++
description: Кодирует и декодирует имена XML, а также предоставляет методы для преобразования между типами времени выполнения и типами языка определения XML-схем (XSD). При преобразовании типов возвращаемые значения не зависят от локали.
type: docs
weight: 157
url: /ru/system.xml/xmlconvert/
---
## XmlConvert класс

Кодирует и декодирует имена XML, а также предоставляет методы для преобразования между типами во времени выполнения и типами языка определения XML [Schema](../../system.xml.schema/) (XSD). При преобразовании типов возвращаемые значения не зависят от локали.

```cpp
class XmlConvert : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| static [String](../../system/string/) [DecodeName](./decodename/)(const [String](../../system/string/)\&) | Декодирует имя. Этот метод является обратным к методам XmlConvert::EncodeName(String) и XmlConvert::EncodeLocalName(String). |
| static [String](../../system/string/) [EncodeLocalName](./encodelocalname/)(const [String](../../system/string/)\&) | Преобразует имя в корректное локальное имя XML. |
| static [String](../../system/string/) [EncodeName](./encodename/)(const [String](../../system/string/)\&) | Преобразует имя в корректное имя XML. |
| static [String](../../system/string/) [EncodeNmToken](./encodenmtoken/)(const [String](../../system/string/)\&) | Проверяет, что имя соответствует спецификации XML. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типa значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| static **bool** [IsNCNameChar](./isncnamechar/)(char16_t) | Проверяет, является ли переданный символ допустимым символом без двоеточия. |
| static **bool** [IsPublicIdChar](./ispublicidchar/)(char16_t) | Возвращает переданный символ, если он является допустимым символом публичного идентификатора; иначе **nullptr**. |
| static **bool** [IsStartNCNameChar](./isstartncnamechar/)(char16_t) | Проверяет, является ли переданный символ допустимым начальным символом имени. |
| static **bool** [IsWhitespaceChar](./iswhitespacechar/)(char16_t) | Проверяет, является ли переданный символ допустимым пробельным символом XML. |
| static **bool** [IsXmlChar](./isxmlchar/)(char16_t) | Проверяет, является ли переданный символ допустимым символом XML. |
| static **bool** [IsXmlSurrogatePair](./isxmlsurrogatepair/)(char16_t, char16_t) | Проверяет, является ли переданная пара суррогатных символов допустимым символом XML. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а лишь инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со ссылкой nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как weak-указатель (а не shared). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| static **bool** [ToBoolean](./toboolean/)([String](../../system/string/)) | Преобразует [String](../../system/string/) в эквивалент [Boolean](../../system/boolean/). |
| static **uint8_t** [ToByte](./tobyte/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [Byte](../../system/byte/). |
| static char16_t [ToChar](./tochar/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [Char](../../system/char/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Преобразует [String](../../system/string/) в эквивалент [DateTime](../../system/datetime/). |
| static [DateTime](../../system/datetime/) [ToDateTime](./todatetime/)(const [String](../../system/string/)\&, [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Преобразует [String](../../system/string/) в [DateTime](../../system/datetime/) с использованием указанного XmlDateTimeSerializationMode. |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&) | Преобразует предоставленный [String](../../system/string/) в эквивалент [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [String](../../system/string/)\&) | Преобразует предоставленный [String](../../system/string/) в эквивалент [DateTimeOffset](../../system/datetimeoffset/). |
| static [DateTimeOffset](../../system/datetimeoffset/) [ToDateTimeOffset](./todatetimeoffset/)(const [String](../../system/string/)\&, const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\&) | Преобразует предоставленный [String](../../system/string/) в эквивалент [DateTimeOffset](../../system/datetimeoffset/). |
| static [Decimal](../../system/decimal/) [ToDecimal](./todecimal/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [Decimal](../../system/decimal/). |
| static **double** [ToDouble](./todouble/)([String](../../system/string/)) | Преобразует [String](../../system/string/) в эквивалент [Double](../../system/double/). |
| static [Guid](../../system/guid/) [ToGuid](./toguid/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [Guid](../../system/guid/). |
| static **int16_t** [ToInt16](./toint16/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [Int16](../../system/int16/). |
| static **int32_t** [ToInt32](./toint32/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [Int32](../../system/int32/). |
| static **int64_t** [ToInt64](./toint64/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [Int64](../../system/int64/). |
| static **int8_t** [ToSByte](./tosbyte/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [SByte](../../system/sbyte/). |
| static **float** [ToSingle](./tosingle/)([String](../../system/string/)) | Преобразует [String](../../system/string/) в эквивалент [Single](../../system/single/). |
| static [String](../../system/string/) [ToString](./tostring/)(**bool**) | Преобразует [Boolean](../../system/boolean/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(char16_t) | Преобразует [Char](../../system/char/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([Decimal](../../system/decimal/)) | Преобразует [Decimal](../../system/decimal/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int8_t**) | Преобразует [SByte](../../system/sbyte/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int16_t**) | Преобразует [Int16](../../system/int16/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int32_t**) | Преобразует [Int32](../../system/int32/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**int64_t**) | Преобразует [Int64](../../system/int64/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint8_t**) | Преобразует [Byte](../../system/byte/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint16_t**) | Преобразует [UInt16](../../system/uint16/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint32_t**) | Преобразует [UInt32](../../system/uint32/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**uint64_t**) | Преобразует [UInt64](../../system/uint64/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**float**) | Преобразует [Single](../../system/single/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)(**double**) | Преобразует [Double](../../system/double/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([TimeSpan](../../system/timespan/)) | Преобразует [TimeSpan](../../system/timespan/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/)) | Преобразует [DateTime](../../system/datetime/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), const [String](../../system/string/)\&) | Преобразует [DateTime](../../system/datetime/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTime](../../system/datetime/), [XmlDateTimeSerializationMode](../xmldatetimeserializationmode/)) | Преобразует [DateTime](../../system/datetime/) в [String](../../system/string/) с использованием указанного XmlDateTimeSerializationMode. |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/)) | Преобразует предоставленный [DateTimeOffset](../../system/datetimeoffset/) в [String](../../system/string/). |
| static [String](../../system/string/) [ToString](./tostring/)([DateTimeOffset](../../system/datetimeoffset/), const [String](../../system/string/)\&) | Преобразует предоставленный [DateTimeOffset](../../system/datetimeoffset/) в [String](../../system/string/) в указанном формате. |
| static [String](../../system/string/) [ToString](./tostring/)([Guid](../../system/guid/)) | Преобразует [Guid](../../system/guid/) в [String](../../system/string/). |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static [TimeSpan](../../system/timespan/) [ToTimeSpan](./totimespan/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [TimeSpan](../../system/timespan/). |
| static **uint16_t** [ToUInt16](./touint16/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [UInt16](../../system/uint16/). |
| static **uint32_t** [ToUInt32](./touint32/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [UInt32](../../system/uint32/). |
| static **uint64_t** [ToUInt64](./touint64/)(const [String](../../system/string/)\&) | Преобразует [String](../../system/string/) в эквивалент [UInt64](../../system/uint64/). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует снятие блокировки оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| static [String](../../system/string/) [VerifyName](./verifyname/)(const [String](../../system/string/)\&) | Проверяет, является ли имя корректным согласно рекомендации W3C Extended Markup Language. |
| static [String](../../system/string/) [VerifyNCName](./verifyncname/)(const [String](../../system/string/)\&) | Проверяет, является ли имя корректным **NCName** согласно рекомендации W3C Extended Markup Language. **NCName** — это имя, которое не может содержать двоеточие. |
| static [String](../../system/string/) [VerifyNMTOKEN](./verifynmtoken/)(const [String](../../system/string/)\&) | Проверяет, является ли строка корректным NMTOKEN согласно рекомендациям W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyPublicId](./verifypublicid/)(const [String](../../system/string/)\&) | Возвращает переданную строку, если все символы аргумента являются допустимыми символами публичного идентификатора. |
| static [String](../../system/string/) [VerifyTOKEN](./verifytoken/)(const [String](../../system/string/)\&) | Проверяет, является ли строка корректным токеном согласно рекомендациям W3C XML [Schema](../../system.xml.schema/) Part2: Datatypes. |
| static [String](../../system/string/) [VerifyWhitespace](./verifywhitespace/)(const [String](../../system/string/)\&) | Возвращает переданную строку, если все символы аргумента являются допустимыми пробельными символами. |
| static [String](../../system/string/) [VerifyXmlChars](./verifyxmlchars/)(const [String](../../system/string/)\&) | Возвращает переданную строку, если все символы и суррогатные пары в аргументе являются допустимыми символами XML; в противном случае выбрасывается XmlException с информацией о первом недопустимом символе. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Typedefs

| Typedef | Описание |
| --- | --- |
| [Ptr](./ptr/) | Псевдоним для shared pointer к экземпляру этого класса. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Xml](../)
* Библиотека [Aspose.Slides](../../)