---
title: BeginConnect()
second_title: مرجع API Aspose.Slides للغة C++
description: يباشر عملية اتصال غير متزامنة.
type: docs
weight: 261
url: /ar/system.net.sockets/tcpclient/beginconnect/
---
## TcpClient::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية اتصال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| host | [String](../../../system/string/) | اسم مضيف بعيد. |
| port | **int32_t** | منفذ المضيف البعيد. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاتصال غير المتزامنة التي تم بدءها.

## TcpClient::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية اتصال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | عنوان IP لمضيف بعيد. |
| port | **int32_t** | منفذ المضيف البعيد. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاتصال غير المتزامنة التي تم بدءها.

## TcpClient::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يبدأ عملية اتصال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpClient::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### المعلمات

| معامل | نوع | وصف |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | عناوين IP لمضيف بعيد. |
| port | **int32_t** | منفذ المضيف البعيد. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء تُستدعى عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاتصال غير المتزامنة التي تم بدءها.

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* تعريف نوع [AsyncCallback](../../../system/asynccallback/)
* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IAsyncResult](../../../system/iasyncresult/)
* فئة [String](../../../system/string/)
* فئة [Object](../../../system/object/)
* فئة [TcpClient](../)
* فئة [IPAddress](../../../system.net/ipaddress/)
* نطاق [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)