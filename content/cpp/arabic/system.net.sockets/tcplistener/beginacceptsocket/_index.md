---
title: BeginAcceptSocket()
second_title: مرجع API Aspose.Slides للـ C++
description: يباشر عملية قبول غير متزامنة.
type: docs
weight: 144
url: /ar/system.net.sockets/tcplistener/beginacceptsocket/
---
## TcpListener::BeginAcceptSocket(AsyncCallback, System::SharedPtr\<Object\>) method


يباشر عملية قبول غير متزامنة.

```cpp
System::SharedPtr<IAsyncResult> System::Net::Sockets::TcpListener::BeginAcceptSocket(AsyncCallback callback, System::SharedPtr<Object> state)
```


### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| callback | [AsyncCallback](../../../system/asynccallback/) | دالة رد نداء ستُستدعى عند اكتمال العملية. |
| state | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | بيانات مقدمة من المستخدم تُستخدم لتحديد كل عملية اتصال غير متزامنة بشكل فريد. |

### قيمة الإرجاع

كائن [IAsyncResult](../../../system/iasyncresult/) يمثل عملية القبول غير المتزامنة التي تم بدءها.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [AsyncCallback](../../../system/asynccallback/)
* الفئة [IAsyncResult](../../../system/iasyncresult/)
* الفئة [Object](../../../system/object/)
* الفئة [TcpListener](../)
* النطاق [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)