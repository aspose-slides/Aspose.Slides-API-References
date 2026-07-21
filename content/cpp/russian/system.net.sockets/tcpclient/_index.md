---
title: TcpClient
second_title: Aspose.Slides для C++ API Reference
description: "Представляет клиента для TCP сетевых сервисов. Объекты этого класса должны выделяться только с помощью функции System::MakeObject() function. Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель System::SmartPtr и используйте его для передачи в функции в качестве аргумента."
type: docs
weight: 66
url: /ru/system.net.sockets/tcpclient/
---
## TcpClient класс

Представляет клиента для TCP сетевых сервисов. Объекты этого класса должны быть выделены только с помощью функции [System::MakeObject()](../../system/makeobject/). Никогда не создавайте экземпляр этого типа в стеке или с помощью оператора new, так как это приведёт к ошибкам выполнения и/или сбоям утверждений. Всегда оборачивайте этот класс в указатель [System::SmartPtr](../../system/smartptr/) и используйте этот указатель для передачи его в функции в качестве аргумента.

```cpp
class TcpClient : public System::IDisposable
```

## Методы

| Метод | Описание |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([String](../../system/string/), **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Инициирует асинхронную операцию подключения. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Инициирует асинхронную операцию подключения. |
| [System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\> [BeginConnect](./beginconnect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**, [AsyncCallback](../../system/asynccallback/), [System::SharedPtr](../../system/sharedptr/)\<[Object](../../system/object/)\>) | Инициирует асинхронную операцию подключения. |
| void [Close](./close/)() | Закрывает соединение и освобождает текущий экземпляр. |
| void [Connect](./connect/)([String](../../system/string/), **int32_t**) | Устанавливает соединение с указанным удалённым узлом. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>, **int32_t**) | Устанавливает соединение с указанным удалённым узлом. |
| void [Connect](./connect/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Устанавливает соединение с указанным удалённым узлом. |
| void [Connect](./connect/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IPAddress](../../system.net/ipaddress/)\>\>, **int32_t**) | Устанавливает соединение с указанным удалённым узлом. |
| virtual void [Dispose](../../system/idisposable/dispose/)() | Не делает ничего. |
| void [EndConnect](./endconnect/)([System::SharedPtr](../../system/sharedptr/)\<[IAsyncResult](../../system/iasyncresult/)\>) | Ожидает завершения указанной асинхронной операции подключения. |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | Сравнивает объекты, используя семантику C# [Object.Equals](../../system/object/equals/). |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты ссылочного типа в стиле C#. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | Сравнивает объекты значимого типа в стиле C#. |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | Эмулирует сравнение чисел с плавающей точкой в стиле C#, где два NaN считаются равными, хотя согласно IEC 60559:1989 NaN не равен ни одному значению, включая NaN. |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | Только для внутренних целей. |
| **int32_t** [get_Available](./get_available/)() | Возвращает количество байтов, полученных и готовых к чтению. |
| [System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\> [get_Client](./get_client/)() | Получает сокет. |
| **bool** [get_Connected](./get_connected/)() | Возвращает значение, указывающее, подключён ли сокет к удалённому узлу. |
| **bool** [get_ExclusiveAddressUse](./get_exclusiveaddressuse/)() | Получает значение, указывающее, позволяет ли текущий экземпляр только одному клиенту использовать порт. |
| [System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\> [get_LingerState](./get_lingerstate/)() | Получает значение, указывающее, будет ли сокет задерживать закрытие в попытке отправить все ожидающие данные. |
| **bool** [get_NoDelay](./get_nodelay/)() | Получает значение, указывающее, использует ли текущий экземпляр алгоритм Найгла. |
| **int32_t** [get_ReceiveBufferSize](./get_receivebuffersize/)() | Получает размер буфера, используемого для получения данных. |
| **int32_t** [get_ReceiveTimeout](./get_receivetimeout/)() | Получает значение, указывающее количество времени, после которого приём данных будет прерван по таймауту. |
| **int32_t** [get_SendBufferSize](./get_sendbuffersize/)() | Получает размер буфера, используемого для отправки данных. |
| **int32_t** [get_SendTimeout](./get_sendtimeout/)() | Получает значение, указывающее количество времени, после которого отправка данных будет прерван по таймауту. |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | Получает структуру данных счётчика ссылок, связанную с объектом. |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | Аналог метода C# [Object.GetHashCode()](../../system/object/gethashcode/). Позволяет хешировать пользовательские объекты. |
| [System::SharedPtr](../../system/sharedptr/)\<[NetworkStream](../networkstream/)\> [GetStream](./getstream/)() | Возвращает поток, используемый для отправки и получения данных. |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | Получает фактический тип объекта. Аналог вызова C# [System.Object.GetType()](../../system/object/gettype/). |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | Проверяет, представляет ли объект экземпляр типа, описанного targetType. Аналог оператора C# 'is'. |
| void [Lock](../../system/object/lock/)() | Реализует блокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | Аналог метода C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/). Позволяет клонировать пользовательские типы. |
|  [Object](../../system/object/object/)() | Создаёт объект. Инициализирует все внутренние структуры данных. |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | Конструктор копирования. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | Оператор присваивания. На самом деле ничего не копирует, просто инициализирует новый объект и позволяет копировать конструировать подклассы. |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | Сравнивает объекты по ссылке. |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | Сравнивает объект значимого типа со значением nullptr по ссылке. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строки и nullptr. |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | Специализация [Object::ReferenceEquals](../../system/object/referenceequals/) для случая строк. |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | Уменьшает счётчик общих ссылок на указанное значение. |
| void [set_Client](./set_client/)([System::SharedPtr](../../system/sharedptr/)\<[Socket](../socket/)\>) | Устанавливает сокет. |
| void [set_ExclusiveAddressUse](./set_exclusiveaddressuse/)(**bool**) | Устанавливает значение, указывающее, позволяет ли текущий экземпляр только одному клиенту использовать порт. |
| void [set_LingerState](./set_lingerstate/)([System::SharedPtr](../../system/sharedptr/)\<[LingerOption](../lingeroption/)\>) | Устанавливает значение, указывающее, будет ли сокет задерживать закрытие в попытке отправить все ожидающие данные. |
| void [set_NoDelay](./set_nodelay/)(**bool**) | Устанавливает значение, указывающее, использует ли текущий экземпляр алгоритм Найгла. |
| void [set_ReceiveBufferSize](./set_receivebuffersize/)(**int32_t**) | Устанавливает размер буфера, используемого для получения данных. |
| void [set_ReceiveTimeout](./set_receivetimeout/)(**int32_t**) | Устанавливает значение, указывающее количество времени, после которого приём данных будет прерван по таймауту. |
| void [set_SendBufferSize](./set_sendbuffersize/)(**int32_t**) | Устанавливает размер буфера, используемого для отправки данных. |
| void [set_SendTimeout](./set_sendtimeout/)(**int32_t**) | Устанавливает значение, указывающее количество времени, после которого отправка данных будет прерван по таймауту. |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | Устанавливает n-й аргумент шаблона как слабый указатель (а не shared). Позволяет переключать указатели в контейнерах в режим слабых. |
| int [SharedCount](../../system/object/sharedcount/)() const | Получает текущее значение счётчика общих ссылок. |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | Увеличивает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | Уменьшает и возвращает счётчик общих ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
|  [TcpClient](./tcpclient/)([System::SharedPtr](../../system/sharedptr/)\<[IPEndPoint](../../system.net/ipendpoint/)\>) | Создаёт новый экземпляр. |
|  [TcpClient](./tcpclient/)() | Создаёт новый экземпляр. |
|  [TcpClient](./tcpclient/)([AddressFamily](../addressfamily/)) | Создаёт новый экземпляр. |
|  [TcpClient](./tcpclient/)([String](../../system/string/), **int32_t**) | Создаёт новый экземпляр. |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | Аналог метода C# [Object.ToString()](../../system/object/tostring/). Позволяет преобразовывать пользовательские объекты в строку. |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | Реализует конструкцию C# typeof([System.Object](../../system/object/)). |
| void [Unlock](../../system/object/unlock/)() | Реализует разблокировку оператора C# lock(). Вызывайте напрямую или используйте объект-страж [LockContext](../../system/lockcontext/). |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | Увеличивает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | Уменьшает счётчик слабых ссылок. Не следует вызывать напрямую; вместо этого используйте умные указатели или ThisProtector. |
| virtual  [~Object](../../system/object/~object/)() | Уничтожает объект. Освобождает все внутренние структуры данных. |
| virtual  [~TcpClient](./~tcpclient/)() | Разрушает текущий экземпляр. |

## См. также

* Класс [IDisposable](../../system/idisposable/)
* Пространство имён [System::Net::Sockets](../)
* Библиотека [Aspose.Slides](../../)