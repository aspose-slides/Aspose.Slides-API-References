---
title: Details_SoapException
second_title: Справочник API Aspose.Slides для C++
description: "Представляет исключение, выбрасываемое, когда метод вызывается через SOAP и происходит ошибка. Никогда не создавайте экземпляры этого класса вручную. Вместо этого используйте класс SoapException. Никогда не оборачивайте экземпляры класса SoapException в System::SmartPtr."
type: docs
weight: 1
url: /ru/system.web.services.protocols/details_soapexception/
---
## Details_SoapException класс


Представляет исключение, выбрасываемое, когда метод вызывается через SOAP и происходит ошибка. Никогда не создавайте экземпляры этого класса вручную. Вместо этого используйте класс SoapException. Никогда не оборачивайте экземпляры класса SoapException в [System::SmartPtr](../../system/smartptr/).

```cpp
class Details_SoapException : public System::Details_SystemException
```

## Методы

| Метод | Описание |
| --- | --- |
|  [Details_SoapException](./details_soapexception/)() | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [Exception](../../system/exception/)) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/)) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [Exception](../../system/exception/)) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [Exception](../../system/exception/)) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Создаёт новый экземпляр. |
|  [Details_SoapException](./details_soapexception/)([String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>, [String](../../system/string/), [String](../../system/string/), [String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\>, [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\>, [Exception](../../system/exception/)) | Создаёт новый экземпляр. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типового значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, несмотря на то, что согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [String](../../system/string/) [get_Actor](./get_actor/)() | Возвращает часть кода, где выбрасывается исключение при использовании версии SOAP 1.1. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\> [get_Code](./get_code/)() | Возвращает локальное имя, квалифицированное пространством имён в формате 'namespace:localname', которое указывает код ошибки SOAP. |
| virtual [SharedPtr](../../system/sharedptr/)\<[Collections::Generic::IDictionary](../../system.collections.generic/idictionary/)\<[SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>, [SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>\>\> [get_Data](../../system/details_exception/get_data/)() | Возвращает словарь с пользовательскими данными исключения. |
| [System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlNode](../../system.xml/xmlnode/)\> [get_Detail](./get_detail/)() | Возвращает детали о выброшенном исключении. |
| **int32_t** [get_HResult](../../system/details_exception/get_hresult/)() const | Возвращает 32-битное целочисленное значение, представляющее код HRESULT, связанный с исключением, представленным текущим объектом. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [get_InnerException](../../system/details_exception/get_innerexception/)() const | Возвращает ссылку на объект, представляющий внутреннее исключение. |
| [String](../../system/string/) [get_Lang](./get_lang/)() | Возвращает язык, используемый для локализации свойств исключения. |
| virtual [String](../../system/string/) [get_Message](../../system/details_exception/get_message/)() const | Возвращает строку, содержащую описание ошибки. |
| [String](../../system/string/) [get_Node](./get_node/)() | Возвращает часть кода, где выбрасывается исключение при использовании версии SOAP 2.0. |
| [String](../../system/string/) [get_Role](./get_role/)() | Возвращает роль XML-веб-службы, которая выбрасывает исключение. |
| virtual [String](../../system/string/) [get_StackTrace](../../system/details_exception/get_stacktrace/)() const | Возвращает строку, содержащую трассировку стека. |
| [System::SharedPtr](../../system/sharedptr/)\<SoapFaultSubCode\> [get_SubCode](./get_subcode/)() | Возвращает необязательную информацию из XML-элемента 'subcode'. |
| virtual [ExceptionWrapper](../../system/exceptionwrapper/)\<[Details_Exception](../../system/details_exception/)\> [GetBaseException](../../system/details_exception/getbaseexception/)() const | Возвращает копию объекта Exception, представляющего самое внутреннее исключение. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет вычислять хеш пользовательских объектов. |
| const [System::TypeInfo](../../system/typeinfo/)\& [GetType](../../system/details_systemexception/gettype/)() const override | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| **bool** [Is](../../system/details_systemexception/is/)(const [System::TypeInfo](../../system/typeinfo/)\&) const override |  |
| static **bool** [IsClientFaultCode](./isclientfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Проверяет, равен ли заданный код коду ошибки SOAP 'Client'. |
| static **bool** [IsMustUnderstandFaultCode](./ismustunderstandfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Проверяет, равен ли заданный код коду ошибки SOAP 'MustUnderstand'. |
| static **bool** [IsServerFaultCode](./isserverfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Проверяет, равен ли заданный код коду ошибки SOAP 'Server'. |
| static **bool** [IsVersionMismatchFaultCode](./isversionmismatchfaultcode/)([System::SharedPtr](../../system/sharedptr/)\<[Xml::XmlQualifiedName](../../system.xml/xmlqualifiedname/)\>) | Проверяет, равен ли заданный код коду ошибки SOAP 'VersionMismatch'. |
| void [Lock](../../system/object/lock/)() | Осуществляет блокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типового значения с nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик совместно используемых ссылок на указанное значение. |
| void [set_HResult](../../system/details_exception/set_hresult/)(**int32_t**) | Устанавливает HRESULT — кодовое числовое значение, назначаемое конкретному исключению. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-ый шаблонный аргумент как слабую ссылку (а не общую). Позволяет переключать указатели в контейнерах в режим weak. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение совместно используемого счётчика ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает совместно используемый счётчик ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает совместно используемый счётчик ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| [String](../../system/string/) [ToString](../../system/details_exception/tostring/)() const override | Возвращает строковое представление текущего объекта. |
| static const [System::TypeInfo](../../system/typeinfo/)\& [Type](../../system/details_systemexception/type/)() |  |
| void [Unlock](../../system/object/unlock/)() | Осуществляет разблокировку, аналогичную оператору C# lock(). Вызывайте напрямую или используйте объект-сторож [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; используйте умные указатели или ThisProtector. |
| virtual const char * [what](../../system/details_exception/what/)() const | Реализует метод [what()](../../system/details_exception/what/), вызываемый классом [ExceptionWrapper](../../system/exceptionwrapper/). Несмотря на то, что этот класс не наследуется от std::exception, производные классы могут использовать защищённые/приватные члены для реализации своей логики. Перемещение реализации этого метода в [ExceptionWrapper](../../system/exceptionwrapper/) может нарушить эту логику. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Поля

| Поле | Описание |
| --- | --- |
| static [ClientFaultCode](./clientfaultcode/) | Код ошибки SOAP, представляющий вызов клиента, оформленный некорректно или не содержащий необходимую информацию. |
| static [DetailElementName](./detailelementname/) | Локальное имя, квалифицированное пространством имён в формате 'namespace:localname'. |
| static [MustUnderstandFaultCode](./mustunderstandfaultcode/) | Код ошибки SOAP, указывающий, что элемент SOAP, отмеченный атрибутом 'MustUnderstand', не был обработан. |
| static [ServerFaultCode](./serverfaultcode/) | Код ошибки SOAP, представляющий ошибку, произошедшую на сервере. |
| static [VersionMismatchFaultCode](./versionmismatchfaultcode/) | Код ошибки SOAP, представляющий недопустимое пространство имён. |

## См. также

* Класс [Details_SystemException](../../system/details_systemexception/)
* Пространство имён [System::Web::Services::Protocols](../)
* Библиотека [Aspose.Slides](../../)