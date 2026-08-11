---
title: Connect()
second_title: Aspose.Slides لـ C++ مرجع واجهة برمجة التطبيقات
description: يقوم بإنشاء اتصال إلى المنفذ المحدد على المضيف المحدد.
type: docs
weight: 66
url: /ar/system.net.sockets/udpclient/connect/
---
## UdpClient::Connect(String, int32_t) طريقة

يُنشئ اتصالًا إلى المنفذ المحدد على المضيف المحدد.

```cpp
void System::Net::Sockets::UdpClient::Connect(String hostname, int32_t port)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | اسم المضيف البعيد في DNS الذي تريد الاتصال به. |
| port | **int32_t** | رقم المنفذ المحلي الذي تريد التواصل من خلاله. |

## UdpClient::Connect(System::SharedPtr\<IPAddress\>, int32_t) طريقة

يُنشئ اتصالًا مع المضيف في العنوان المحدد على المنفذ المحدد.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPAddress> addr, int32_t port)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| addr | [System::SharedPtr](../../../system/sharedptr/)\<[IPAddress](../../../system.net/ipaddress/)\> | الـ[IPAddress](../../../system.net/ipaddress/) للمضيف البعيد الذي سترسل إليه البيانات. |
| port | **int32_t** | رقم المنفذ المحلي الذي تريد التواصل من خلاله. |

## UdpClient::Connect(System::SharedPtr\<IPEndPoint\>) طريقة

يُنشئ اتصالًا بنقطة انتهاء عن بُعد.

```cpp
void System::Net::Sockets::UdpClient::Connect(System::SharedPtr<IPEndPoint> endPoint)
```

### Arguments

| المعامل | النوع | الوصف |
| --- | --- | --- |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | نقطة النهاية التي تربط بها اتصال UDP. |

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [UdpClient](../)
* فئة [IPAddress](../../../system.net/ipaddress/)
* فئة [IPEndPoint](../../../system.net/ipendpoint/)
* نطاق [System::Net::Sockets](../../)
* مكتبة [Aspose.Slides](../../../)