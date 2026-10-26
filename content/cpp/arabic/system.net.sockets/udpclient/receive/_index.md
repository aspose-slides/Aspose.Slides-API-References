---
title: Receive()
second_title: مرجع API ل Aspose.Slides للـ C++
description: يعيد حزمة بيانات أرسلتها الخادم.
type: docs
weight: 92
url: /ar/system.net.sockets/udpclient/receive/
---
## UdpClient::Receive(System::SharedPtr\<IPEndPoint\>\&) طريقة

يعيد حزمة بيانات أرسلتها الخادم.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::UdpClient::Receive(System::SharedPtr<IPEndPoint> &remoteEP)
```

### المعاملات

| المعلمة | النوع | الوصف |
| --- | --- | --- |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\>\& | [IPEndPoint](../../../system.net/ipendpoint/) يمثل المضيف البعيد الذي أُرسِلَتْ منه البيانات. |

### قيمة الإرجاع

مصفوفة بايت سيتم تعيين البيانات المستلمة فيها.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* الفئة [IPEndPoint](../../../system.net/ipendpoint/)
* الفئة [UdpClient](../)
* النطاق [System::Net::Sockets](../../)
* المكتبة [Aspose.Slides](../../../)