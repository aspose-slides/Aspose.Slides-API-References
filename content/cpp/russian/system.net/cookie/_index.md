---
title: Cookie
second_title: Справочник API Aspose.Slides для C++
description: "Представляет HTTP-cookie. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам времени выполнения и/или к сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 1
url: /ru/system.net/cookie/
---
## Класс Cookie

Represents an HTTP cookie. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class Cookie : public System::Object
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[Cookie](./)\> [Clone](./clone/)() | Создает копию текущего экземпляра. |
|  [Cookie](./cookie/)() | Создает новый экземпляр. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/)) | Создает новый экземпляр. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Создает новый экземпляр. |
|  [Cookie](./cookie/)([String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [String](../../system/string/)) | Создает новый экземпляр. |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) override | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, при котором два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутреннего использования. |
| [String](../../system/string/) [get_Comment](./get_comment/)() const | Возвращает значение атрибута 'Comment'. |
| [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\> [get_CommentUri](./get_commenturi/)() const | Возвращает значение атрибута 'CommentURL'. |
| **bool** [get_Discard](./get_discard/)() const | Возвращает значение атрибута 'Discard'. |
| [String](../../system/string/) [get_Domain](./get_domain/)() const | Возвращает значение атрибута 'Domain'. |
| **bool** [get_DomainImplicit](./get_domainimplicit/)() | Возвращает значение, указывающее, является ли домен неявным. |
| [String](../../system/string/) [get_DomainKey](./get_domainkey/)() const | Возвращает ключ домена. |
| **bool** [get_Expired](./get_expired/)() | Возвращает значение, указывающее, истек ли срок действия cookie. |
| [DateTime](../../system/datetime/) [get_Expires](./get_expires/)() | Возвращает значение атрибута 'Expires'. |
| **bool** [get_HttpOnly](./get_httponly/)() const | Возвращает значение атрибута 'HttpOnly'. |
| [String](../../system/string/) [get_Name](./get_name/)() const | Возвращает имя cookie. |
| [String](../../system/string/) [get_Path](./get_path/)() const | Возвращает значение атрибута 'Path'. |
| **bool** [get_Plain](./get_plain/)() const | Возвращает значение, указывающее, является ли спецификация cookie 'Plain'. |
| [String](../../system/string/) [get_Port](./get_port/)() const | Возвращает значение атрибута 'Port'. |
| [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\> [get_PortList](./get_portlist/)() const | Возвращает коллекцию значений атрибута 'Port'. |
| **bool** [get_Secure](./get_secure/)() const | Возвращает значение атрибута 'Secure'. |
| [DateTime](../../system/datetime/) [get_TimeStamp](./get_timestamp/)() const | Возвращает время создания cookie. |
| [String](../../system/string/) [get_Value](./get_value/)() const | Возвращает значение cookie. |
| [CookieVariant](../cookievariant/) [get_Variant](./get_variant/)() const | Возвращает спецификацию cookie. |
| **int32_t** [get_Version](./get_version/)() const | Возвращает значение атрибута '[Version](../../system/version/)'. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Возвращает структуру счетчика ссылок, связанную с объектом. |
| **int32_t** [GetHashCode](./gethashcode/)() const override | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хэшировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Возвращает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [InternalSetName](./internalsetname/)([String](../../system/string/)) | Этот метод вызывается другими методами для установки имени метода. |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создает объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, а просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счетчик совместных ссылок на указанное значение. |
| void [set_Comment](./set_comment/)([String](../../system/string/)) | Устанавливает значение атрибута 'Comment'. |
| void [set_CommentUri](./set_commenturi/)([System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>) | Устанавливает значение атрибута 'CommentURL'. |
| void [set_Discard](./set_discard/)(**bool**) | Устанавливает значение атрибута 'Discard'. |
| void [set_Domain](./set_domain/)([String](../../system/string/)) | Устанавливает значение атрибута 'Domain'. |
| void [set_DomainImplicit](./set_domainimplicit/)(**bool**) | Устанавливает значение, указывающее, является ли домен неявным. |
| void [set_Expired](./set_expired/)(**bool**) | Устанавливает значение, указывающее, истек ли срок действия cookie. |
| void [set_Expires](./set_expires/)([DateTime](../../system/datetime/)) | Устанавливает значение атрибута 'Expires'. |
| void [set_HttpOnly](./set_httponly/)(**bool**) | Устанавливает значение атрибута 'HttpOnly'. |
| void [set_Name](./set_name/)([String](../../system/string/)) | Устанавливает имя cookie. |
| void [set_Path](./set_path/)([String](../../system/string/)) | Устанавливает значение атрибута 'Path'. |
| void [set_Port](./set_port/)([String](../../system/string/)) | Устанавливает значение атрибута 'Port'. |
| void [set_Secure](./set_secure/)(**bool**) | Устанавливает значение атрибута 'Secure'. |
| void [set_Value](./set_value/)([String](../../system/string/)) | Устанавливает значение cookie. |
| void [set_Variant](./set_variant/)([CookieVariant](../cookievariant/)) | Устанавливает спецификацию cookie. |
| void [set_Version](./set_version/)(**int32_t**) | Устанавливает значение атрибута '[Version](../../system/version/)'. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й шаблонный аргумент как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Возвращает текущий значение совместного счетчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Инкрементирует совместный счетчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Декрементирует и возвращает совместный счетчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToServerString](./toserverstring/)() | Сериализует текущий экземпляр в строковое представление. |
| [String](../../system/string/) [ToString](./tostring/)() const override | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| **bool** [VerifySetDefaults](./verifysetdefaults/)([CookieVariant](../cookievariant/), [System::SharedPtr](../../system/sharedptr/)\<[Uri](../../system/uri/)\>, **bool**, [String](../../system/string/), **bool**, **bool**) | Проверяет и устанавливает значения атрибутов по умолчанию. |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Инкрементирует слабый счетчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Декрементирует слабый счетчик ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static [CommentAttributeName](./commentattributename/) | Имя атрибута 'Comment'. |
| static [CommentUrlAttributeName](./commenturlattributename/) | Имя атрибута 'CommentURL'. |
| static [DiscardAttributeName](./discardattributename/) | Имя атрибута 'Discard'. |
| static [DomainAttributeName](./domainattributename/) | Имя атрибута 'Domain'. |
| static [EqualsLiteral](./equalsliteral/) | Разделитель, используемый для разделения имени и значения атрибута. |
| static [ExpiresAttributeName](./expiresattributename/) | Имя атрибута 'Expires'. |
| static [HttpOnlyAttributeName](./httponlyattributename/) | Имя атрибута 'HttpOnly'. |
| static [MaxAgeAttributeName](./maxageattributename/) | Имя атрибута 'Max-Age'. |
| static [MaxSupportedVersion](./maxsupportedversion/) | Максимальная поддерживаемая версия. |
| static [MaxSupportedVersionString](./maxsupportedversionstring/) | Строковое представление максимальной поддерживаемой версии. |
| static [PathAttributeName](./pathattributename/) | Имя атрибута 'Path'. |
| static [PortAttributeName](./portattributename/) | Имя атрибута 'Port'. |
| static [PortSplitDelimiters](./portsplitdelimiters/) | Массив, содержащий разделители для значений атрибута 'Port'. |
| static [QuotesLiteral](./quotesliteral/) | Символ, использующийся для обрамления частей атрибута. |
| static [ReservedToName](./reservedtoname/) | Значение, зарезервированное для имени cookie. |
| static [ReservedToValue](./reservedtovalue/) | Значение, зарезервированное для значения cookie. |
| static [SecureAttributeName](./secureattributename/) | Имя атрибута 'Secure'. |
| static [SeparatorLiteral](./separatorliteral/) | Разделитель атрибутов. |
| static [SpecialAttributeLiteral](./specialattributeliteral/) | Префикс имен специальных атрибутов. |
| static [VersionAttributeName](./versionattributename/) | Имя атрибута '[Version](../../system/version/)'. |

## Смотрите также

* Класс [Object](../../system/object/)
* Пространство имен [System::Net](../)
* Библиотека [Aspose.Slides](../../)