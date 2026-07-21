---
title: ContentDispositionHeaderValue
second_title: Aspose.Slides для C++ справочник API
description: "Представляет значение заголовка 'Content-Disposition'. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 27
url: /ru/system.net.http.headers/contentdispositionheadervalue/
---
## ContentDispositionHeaderValue класс


Представляет значение заголовка 'Content-Disposition'. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class ContentDispositionHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)() | Создаёт новый экземпляр. |
|  [ContentDispositionHeaderValue](./contentdispositionheadervalue/)([String](../../system/string/)) | Создаёт новый экземпляр. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_CreationDate](./get_creationdate/)() | Получает дату создания файла. |
| [String](../../system/string/) [get_DispositionType](./get_dispositiontype/)() | Получает тип диспозиции. |
| [String](../../system/string/) [get_FileName](./get_filename/)() | Получает значение, определяющее, как сформировать имя файла для хранения полезной нагрузки сообщения. Используется, когда сущность отсоединена и хранится в отдельном файле. |
| [String](../../system/string/) [get_FileNameStar](./get_filenamestar/)() | Получает значение, определяющее, как формировать имена файлов для хранения полезной нагрузки сообщения. Используется, когда сущности отсоединены и хранятся в отдельных файлах. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ModificationDate](./get_modificationdate/)() | Получает дату изменения файла. |
| [String](../../system/string/) [get_Name](./get_name/)() | Получает название части тела содержимого. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Parameters](./get_parameters/)() | Возвращает коллекцию параметров заголовка 'Content-Disposition'. |
| [Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\> [get_ReadDate](./get_readdate/)() | Получает дату последнего чтения файла. |
| [Nullable](../../system/nullable/)\<**int64_t**\> [get_Size](./get_size/)() | Получает примерный размер файла. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| static **int32_t** [GetDispositionTypeLength](./getdispositiontypelength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [ContentDispositionHeaderValue](./). |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Преобразует переданную строку в экземпляр класса [ContentDispositionHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_CreationDate](./set_creationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Устанавливает дату создания файла. |
| void [set_DispositionType](./set_dispositiontype/)([String](../../system/string/)) | Устанавливает тип диспозиции. |
| void [set_FileName](./set_filename/)([String](../../system/string/)) | Устанавливает значение, определяющее, как сформировать имя файла для хранения полезной нагрузки сообщения. Используется, когда сущность отсоединена и хранится в отдельном файле. |
| void [set_FileNameStar](./set_filenamestar/)([String](../../system/string/)) | Устанавливает значение, определяющее, как формировать имена файлов для хранения полезной нагрузки сообщения. Используется, когда сущности отсоединены и хранятся в отдельных файлах. |
| void [set_ModificationDate](./set_modificationdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Устанавливает дату изменения файла. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Устанавливает название части тела содержимого. |
| void [set_ReadDate](./set_readdate/)([Nullable](../../system/nullable/)\<[DateTimeOffset](../../system/datetimeoffset/)\>) | Устанавливает дату последнего чтения файла. |
| void [set_Size](./set_size/)([Nullable](../../system/nullable/)\<**int64_t**\>) | Устанавливает примерный размер файла. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый шаблонный аргумент как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает счётчик общих ссылок и возвращает его значение. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ContentDispositionHeaderValue](./)\>\&) | Пытается преобразовать переданную строку в экземпляр класса [ContentDispositionHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструктор C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ICloneable](../../system/icloneable/)
* Пространство имён [System::Net::Http::Headers](../)
* Библиотека [Aspose.Slides](../../)