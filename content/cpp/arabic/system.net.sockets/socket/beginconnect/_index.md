---
title: BeginConnect()
second_title: مرجع API Aspose.Slides للـ C++
description: يباشر عملية اتصال غير متزامنة.
type: docs
weight: 573
url: /ar/system.net.sockets/socket/beginconnect/
---
## Socket::BeginConnect(System::SharedPtr\<EndPoint\>, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يباشر عملية اتصال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<EndPoint> remoteEP, AsyncCallback callback, System::SharedPtr<Object> state)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | نقطة النهاية البعيدة. |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء سيتم استدعاؤها عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاتصال غير المتزامنة التي تم بدءها.

## Socket::BeginConnect(String, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يباشر عملية اتصال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(String host, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| host | [String](../../../system/string/) | اسم المضيف البعيد. |
| port | **int32_t** | رقم المنفذ للمضيف البعيد. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء سيتم استدعاؤها عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاتصال غير المتزامنة التي تم بدءها.

## Socket::BeginConnect(System::SharedPtr\<IPAddress\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يباشر عملية اتصال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::SharedPtr<IPAddress> address, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| address | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | عنوان الـ IP للمضيف البعيد. |
| port | **int32_t** | رقم المنفذ للمضيف البعيد. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء سيتم استدعاؤها عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاتصال غير المتزامنة التي تم بدءها.

## Socket::BeginConnect(System::ArrayPtr\<System::SharedPtr\<IPAddress\>\>, int32_t, AsyncCallback, System::SharedPtr\<Object\>) طريقة

يباشر عملية اتصال غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::Socket::BeginConnect(System::ArrayPtr<System::SharedPtr<IPAddress>> addresses, int32_t port, AsyncCallback requestCallback, System::SharedPtr<Object> state)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| addresses | [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\>\> | عناوين الـ IP للمضيف البعيد. |
| port | **int32_t** | رقم المنفذ للمضيف البعيد. |
| requestCallback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء سيتم استدعاؤها عند إكمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات يقدمها المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية الاتصال غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* الفئة [IAsyncResult](../../../system/iasyncresult/)
* الفئة [EndPoint](../../../system.net/endpoint/)
* الفئة [Object](../../../system/object/)
* الفئة [Socket](../)
* الفئة [String](../../../system/string/)
* الفئة [IPAddress](../../../system.net/ipaddress/)
* النطاق [System::Net::Sockets](../../)
* المكتبة [Aspose.Slides](../../../)