---
title: SoapDocumentMethodAttribute
second_title: Aspose.Slides для C++ — справочник API
description: "Указывает, что все сообщения SOAP, передаваемые или возвращаемые методом, используют форматирование Document. Объекты этого класса должны выделяться только с помощью функции System::MakeObject(). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте этот указатель для передачи его в функции в качестве аргумента."
type: docs
weight: 53
url: /ru/system.web.services.protocols/soapdocumentmethodattribute/
---
## SoapDocumentMethodAttribute класс


Указывает, что все сообщения SOAP, передаваемые или возвращаемые методом, используют форматирование Document. Объекты этого класса должны выделяться только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или нарушениям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class SoapDocumentMethodAttribute : public System::Attribute
```

## Методы

| Метод | Описание |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты типа значения в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей запятой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен никакому значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| [String](../../system/string/) [get_Action](./get_action/)() | Получает значение атрибута 'SOAPAction'. |
| [String](../../system/string/) [get_Binding](./get_binding/)() | Получает привязку, для которой метод веб-службы XML реализует операцию. |
| **bool** [get_OneWay](./get_oneway/)() | Получает значение, указывающее, что клиент не ждёт завершения обработки метода сервером. |
| [SoapParameterStyle](../soapparameterstyle/) [get_ParameterStyle](./get_parameterstyle/)() | Получает значение, указывающее, инкапсулированы ли параметры в единственном XML-элементе под элементом 'Body'. |
| [String](../../system/string/) [get_RequestElementName](./get_requestelementname/)() | Получает имя XML-элемента, связанного с запросом SOAP, определённого в описании сервиса как операция. |
| [String](../../system/string/) [get_RequestNamespace](./get_requestnamespace/)() | Получает пространство имён, связанное с запросом SOAP. |
| [String](../../system/string/) [get_ResponseElementName](./get_responseelementname/)() | Получает имя XML-элемента, связанного с ответом SOAP. |
| [String](../../system/string/) [get_ResponseNamespace](./get_responsenamespace/)() | Получает пространство имён, связанное с ответом SOAP. |
| [Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/) [get_Use](./get_use/)() | Получает значение, определяющее метод кодирования сообщения. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| static [Object::ptr](../../system/object/ptr/) [GetCustomAttribute](../../system/attribute/getcustomattribute/)(const [TypeInfo](../../system/typeinfo/)\&, const [TypeInfo](../../system/typeinfo/)\&) | Возвращает пользовательский атрибут указанного типа, применённый к указанному типу. |
| static [ArrayPtr](../../system/arrayptr/)\<[Object::ptr](../../system/object/ptr/)\> [GetCustomAttributes](../../system/attribute/getcustomattributes/)(const [TypeInfo](../../system/typeinfo/)\&) | Возвращает все пользовательские атрибуты, применённые к указанному типу. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект типa значения со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Action](./set_action/)([String](../../system/string/)) | Устанавливает значение атрибута 'SOAPAction'. |
| void [set_Binding](./set_binding/)([String](../../system/string/)) | Устанавливает привязку, для которой метод веб-службы XML реализует операцию. |
| void [set_OneWay](./set_oneway/)(**bool**) | Устанавливает значение, указывающее, что клиент не ждёт завершения обработки метода сервером. |
| void [set_ParameterStyle](./set_parameterstyle/)([SoapParameterStyle](../soapparameterstyle/)) | Устанавливает значение, указывающее, инкапсулированы ли параметры в единственном XML-элементе под элементом 'Body'. |
| void [set_RequestElementName](./set_requestelementname/)([String](../../system/string/)) | Устанавливает имя XML-элемента, связанного с запросом SOAP, определённого в описании сервиса как операция. |
| void [set_RequestNamespace](./set_requestnamespace/)([String](../../system/string/)) | Устанавливает пространство имён, связанное с запросом SOAP. |
| void [set_ResponseElementName](./set_responseelementname/)([String](../../system/string/)) | Устанавливает имя XML-элемента, связанного с ответом SOAP. |
| void [set_ResponseNamespace](./set_responsenamespace/)([String](../../system/string/)) | Устанавливает пространство имён, связанное с ответом SOAP. |
| void [set_Use](./set_use/)([Description::SoapBindingUse](../../system.web.services.description/soapbindinguse/)) | Устанавливает значение, определяющее метод кодирования сообщения. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не общий). Позволяет переключать указатели в контейнерах в слабый режим. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)() | Создаёт новый экземпляр. |
|  [SoapDocumentMethodAttribute](./soapdocumentmethodattribute/)([String](../../system/string/)) | Создаёт новый экземпляр. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |

## Смотрите также

* Класс [Attribute](../../system/attribute/)
* Пространство имён [System::Web::Services::Protocols](../)
* Библиотека [Aspose.Slides](../../)