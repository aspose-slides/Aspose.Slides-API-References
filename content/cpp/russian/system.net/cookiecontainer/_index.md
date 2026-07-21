---
title: CookieContainer
second_title: Справочник API Aspose.Slides для C++
description: "Предоставляет контейнер для экземпляров класса CookieCollection. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 40
url: /ru/system.net/cookiecontainer/
---
## CookieContainer класс

Provides a container for the CookieCollection-class instances. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class CookieContainer : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | Добавляет cookie в коллекцию. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>, **bool**) | Добавляет cookie в коллекцию. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | Копирует cookie из указанной коллекции в текущую. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Cookie](../cookie/)\>) | Добавляет cookie для указанного URI. |
| void [Add](./add/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\>) | Копирует cookie из указанной коллекции для указанного URI в текущую коллекцию. |
|  [CookieContainer](./cookiecontainer/)() | Создаёт новый экземпляр. |
|  [CookieContainer](./cookiecontainer/)(**int32_t**) | Создаёт новый экземпляр. |
|  [CookieContainer](./cookiecontainer/)(**int32_t**, **int32_t**, **int32_t**) | Создаёт новый экземпляр. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [CookieCutter](./cookiecutter/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/), [String](../../system/string/), **bool**) | Копирует cookie из указанного HTTP-заголовка для указанного URI. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| **int32_t** [get_Capacity](./get_capacity/)() | Получает ёмкость коллекции. |
| **int32_t** [get_Count](./get_count/)() | Возвращает количество элементов коллекции. |
| **int32_t** [get_MaxCookieSize](./get_maxcookiesize/)() | Получает максимальный размер cookie. |
| **int32_t** [get_PerDomainCapacity](./get_perdomaincapacity/)() | Получает ёмкость коллекции на домен. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Возвращает HTTP-заголовок, содержащий cookie, связанные с указанным URI. |
| [String](../../system/string/) [GetCookieHeader](./getcookieheader/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)\&) | Возвращает HTTP-заголовок, содержащий cookie, связанные с указанным URI. |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [GetCookies](./getcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Возвращает коллекцию cookie, связанных с указанным URI. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает реальный тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| [System::SharedPtr](../../system/sharedptr/)\<[CookieCollection](../cookiecollection/)\> [InternalGetCookies](./internalgetcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Возвращает коллекцию cookie, связанных с указанным URI. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| **bool** [IsLocalDomain](./islocaldomain/)([String](../../system/string/)) | Проверяет, является ли указанный домен localhost. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типа значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Capacity](./set_capacity/)(**int32_t**) | Устанавливает ёмкость коллекции. |
| void [set_MaxCookieSize](./set_maxcookiesize/)(**int32_t**) | Устанавливает максимальный размер cookie. |
| void [set_PerDomainCapacity](./set_perdomaincapacity/)(**int32_t**) | Устанавливает ёмкость коллекции на домен. |
| void [SetCookies](./setcookies/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, [String](../../system/string/)) | Копирует cookie из указанного заголовка в коллекцию и связывает их с указанным URI. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (вместо shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущие значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static [DefaultCookieLengthLimit](./defaultcookielengthlimit/) | Максимальный размер cookie. |
| static [DefaultCookieLimit](./defaultcookielimit/) | Максимальное количество элементов коллекции. |
| static [DefaultPerDomainCookieLimit](./defaultperdomaincookielimit/) | Максимальное количество элементов коллекции на домен. |

## См. также

* Класс [Object](../../system/object/)
* Пространство имён [System::Net](../)
* Библиотека [Aspose.Slides](../../)