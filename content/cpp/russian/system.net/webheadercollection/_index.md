---
title: WebHeaderCollection
second_title: Справочник API Aspose.Slides для C++
description: "Представляет коллекцию заголовков протокола. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 482
url: /ru/system.net/webheadercollection/
---
## WebHeaderCollection класс

Представляет коллекцию заголовков протокола. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с использованием оператора new, так как это приведет к ошибкам времени выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class WebHeaderCollection : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Add](./add/)([String](../../system/string/), [String](../../system/string/)) | Добавляет указанную пару имени заголовка и значения заголовка в коллекцию. |
| void [Add](./add/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Добавляет указанную пару заголовка и значения заголовка в коллекцию. |
| void [Add](./add/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Добавляет указанную пару заголовка и значения заголовка в коллекцию. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [AllKeys](./allkeys/)() | Возвращает коллекцию имен заголовков, хранящихся в коллекции. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| **int32_t** [get_Count](./get_count/)() const | Возвращает количество элементов в коллекции. |
| [System::ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\> [get_Keys](./get_keys/)() | Возвращает коллекцию имен заголовков, хранящихся в коллекции. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счетчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [String](../../system/string/) [GetKey](./getkey/)(int) | Возвращает ключ по указанному индексу. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [GetValues](./getvalues/)([String](../../system/string/)) | Возвращает коллекцию значений заголовков. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpRequestHeader](../httprequestheader/)) | Получает значение заголовка, используя указанный заголовок запроса. |
| [String](../../system/string/) [idx_get](./idx_get/)([HttpResponseHeader](../httpresponseheader/)) | Получает значение заголовка, используя указанный заголовок ответа. |
| [String](../../system/string/) [idx_get](./idx_get/)([String](../../system/string/)) | Получает значение заголовка по указанному имени заголовка. |
| void [idx_set](./idx_set/)([HttpRequestHeader](../httprequestheader/), [String](../../system/string/)) | Устанавливает значение указанного заголовка. |
| void [idx_set](./idx_set/)([HttpResponseHeader](../httpresponseheader/), [String](../../system/string/)) | Устанавливает значение заголовка, используя указанный заголовок ответа. |
| void [idx_set](./idx_set/)([String](../../system/string/), [String](../../system/string/)) | Устанавливает значение заголовка, используя указанное имя заголовка. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог операторa C# 'is'. |
| static **bool** [IsRestricted](./isrestricted/)(const [String](../../system/string/)\&) | Проверяет, можно ли установить указанный HTTP-заголовок для запроса. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызовите напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструкторы подклассов. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает по ссылке объект типа значения с nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| void [Remove](./remove/)([String](../../system/string/)) | Удаляет заголовок по указанному имени заголовка. |
| void [Remove](./remove/)([HttpResponseHeader](../httpresponseheader/)) | Удаляет указанный заголовок ответа. |
| void [Remove](./remove/)([HttpRequestHeader](../httprequestheader/)) | Удаляет указанный заголовок запроса. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик общих ссылок на указанное значение. |
| void [Set](./set/)([String](../../system/string/), [String](../../system/string/)) | Устанавливает значение указанного заголовка. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счетчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счетчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызовите напрямую или используйте охранный объект [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счетчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [WebHeaderCollection](./webheadercollection/)() | Создает новый экземпляр. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имён [System::Net](../)
* Библиотека [Aspose.Slides](../../)