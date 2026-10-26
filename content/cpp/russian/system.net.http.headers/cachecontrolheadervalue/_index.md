---
title: CacheControlHeaderValue
second_title: Справочник API Aspose.Slides для C++
description: "Представляет значение заголовка 'Cache-Control'. Объекты этого класса должны создаваться только с помощью функции System::MakeObject(). Нельзя создавать экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 14
url: /ru/system.net.http.headers/cachecontrolheadervalue/
---
## CacheControlHeaderValue класс

Представляет значение заголовка 'Cache-Control'. Объекты этого класса должны создаваться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class CacheControlHeaderValue : public System::ICloneable
```

## Методы

| Метод | Описание |
| --- | --- |
|  [CacheControlHeaderValue](./cachecontrolheadervalue/)() | Создаёт новый экземпляр. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равно ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[System::SharedPtr](../../system/sharedptr/)\<[NameValueHeaderValue](../namevalueheadervalue/)\>\>\> [get_Extensions](./get_extensions/)() | Возвращает коллекцию токенов расширения кеша. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxAge](./get_maxage/)() | Получает значение максимального возраста в секундах, определяющее период, в течение которого клиент будет принимать ответ. |
| **bool** [get_MaxStale](./get_maxstale/)() | Получает значение, определяющее, будет ли клиент принимать просроченные ответы. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MaxStaleLimit](./get_maxstalelimit/)() | Получает значение в секундах, определяющее период, в течение которого клиент будет принимать просроченные ответы. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_MinFresh](./get_minfresh/)() | Получает значение, определяющее срок актуальности. |
| **bool** [get_MustRevalidate](./get_mustrevalidate/)() | Получает значение, определяющее, требует ли сервер переоценки записи кеша, когда она становится устаревшей. |
| **bool** [get_NoCache](./get_nocache/)() | Получает значение, определяющее, будет ли клиент принимать кэшированный ответ. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_NoCacheHeaders](./get_nocacheheaders/)() | Получает коллекцию имён полей в директиве 'no-cache' заголовка 'Cache-Control'. |
| **bool** [get_NoStore](./get_nostore/)() | Получает значение, определяющее, что кеш не должен хранить любую часть HTTP-запроса или ответа. |
| **bool** [get_NoTransform](./get_notransform/)() | Получает значение, определяющее, что кеш или прокси не должны изменять любую часть тела сущности. |
| **bool** [get_OnlyIfCached](./get_onlyifcached/)() | Получает значение, определяющее, что клиент должен использовать только кэшированные записи. |
| **bool** [get_Private](./get_private/)() | Получает значение, определяющее, что сообщение HTTP-ответа или его часть предназначены для одного пользователя и не должны кэшироваться совместным кешем. |
| [System::SharedPtr](../../system/sharedptr/)\<[Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<[String](../../system/string/)\>\> [get_PrivateHeaders](./get_privateheaders/)() | Получает коллекцию имён полей в директиве 'private' заголовка 'Cache-Control'. |
| **bool** [get_ProxyRevalidate](./get_proxyrevalidate/)() | Получает значение, определяющее, требует ли сервер переоценки записи кеша, когда она становится устаревшей для совместных кешей пользовательских агентов. |
| **bool** [get_Public](./get_public/)() | Получает значение, определяющее, может ли HTTP-ответ кэшироваться любым кешем. |
| [Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\> [get_SharedMaxAge](./get_sharedmaxage/)() | Получает общее значение максимального возраста в секундах, которое переопределяет директиву 'max-age' в заголовке 'Cache-Control' или заголовок 'Expires' для совместного кеша. |
| static **int32_t** [GetCacheControlLength](./getcachecontrollength/)([String](../../system/string/), **int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>, [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Преобразует переданную строку, начиная с указанного индекса, в экземпляр класса [CacheControlHeaderValue](./). |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\> [Parse](./parse/)([String](../../system/string/)) | Преобразует переданную строку в экземпляр класса [CacheControlHeaderValue](./). |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со ссылкой на nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместных ссылок на указанное значение. |
| void [set_MaxAge](./set_maxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Устанавливает значение максимального возраста в секундах, определяющее период, в течение которого клиент будет принимать ответ. |
| void [set_MaxStale](./set_maxstale/)(**bool**) | Устанавливает значение, определяющее, будет ли клиент принимать просроченные ответы. |
| void [set_MaxStaleLimit](./set_maxstalelimit/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Устанавливает значение в секундах, определяющее период, в течение которого клиент будет принимать просроченные ответы. |
| void [set_MinFresh](./set_minfresh/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Устанавливает значение, определяющее срок актуальности. |
| void [set_MustRevalidate](./set_mustrevalidate/)(**bool**) | Устанавливает значение, определяющее, требуется ли серверу переоценка записи кеша, когда она становится устаревшей. |
| void [set_NoCache](./set_nocache/)(**bool**) | Устанавливает значение, определяющее, будет ли клиент принимать кэшированный ответ. |
| void [set_NoStore](./set_nostore/)(**bool**) | Устанавливает значение, определяющее, что кеш не должен хранить любую часть HTTP-запроса или ответа. |
| void [set_NoTransform](./set_notransform/)(**bool**) | Устанавливает значение, определяющее, что кеш или прокси не должны изменять любую часть тела сущности. |
| void [set_OnlyIfCached](./set_onlyifcached/)(**bool**) | Устанавливает значение, определяющее, что клиент должен использовать только кэшированные записи. |
| void [set_Private](./set_private/)(**bool**) | Устанавливает значение, определяющее, что сообщение HTTP-ответа или его часть предназначены для одного пользователя и не должны кэшироваться совместным кешем. |
| void [set_ProxyRevalidate](./set_proxyrevalidate/)(**bool**) | Устанавливает значение, определяющее, требует ли сервер переоценки записи кеша, когда она становится устаревшей для совместных кешей пользовательских агентов. |
| void [set_Public](./set_public/)(**bool**) | Устанавливает значение, определяющее, может ли HTTP-ответ кэшироваться любым кешем. |
| void [set_SharedMaxAge](./set_sharedmaxage/)([Nullable](../../system/nullable/)\<[TimeSpan](../../system/timespan/)\>) | Устанавливает общее значение максимального возраста в секундах, которое переопределяет директиву 'max-age' в заголовке 'Cache-Control' или заголовок 'Expires' для совместного кеша. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых ссылок. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика совместных ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик совместных ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static **bool** [TryParse](./tryparse/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[CacheControlHeaderValue](./)\>\&) | Пытается преобразовать переданную строку в экземпляр класса [CacheControlHeaderValue](./). |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## См. также

* Класс [ICloneable](../../system/icloneable/)
* Пространство имён [System::Net::Http::Headers](../)
* Библиотека [Aspose.Slides](../../)