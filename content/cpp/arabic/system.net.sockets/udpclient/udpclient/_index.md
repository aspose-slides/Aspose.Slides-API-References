---
title: UdpClient()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للغة C++
description: يقوم بإنشاء مثيل جديد من الفئة UdpClient.
type: docs
weight: 27
url: /ar/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() منشئ

يُنشئ مثيلاً جديداً من الفئة [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) منشئ

يُنشئ مثيلاً جديداً من الفئة [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | قيمة تحدد مخطط العنونة للمقابس. |

## UdpClient::UdpClient(int32_t) منشئ

يُنشئ مثيلاً جديداً من الفئة [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| port | **int32_t** | رقم المنفذ المحلي الذي تنوي التواصل من خلاله. |

## UdpClient::UdpClient(int32_t, AddressFamily) منشئ

يُنشئ مثيلاً جديداً من الفئة [UdpClient](../).

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| port | **int32_t** | رقم المنفذ المحلي الذي تنوي التواصل من خلاله. |
| family | [AddressFamily](../../addressfamily/) | قيمة تحدد مخطط العنونة للمقابس. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) منشئ

يُنشئ مثيلاً جديداً من الفئة [UdpClient](../). المعامل local EP هو نقطة النهاية المحلية التي تقوم بربط اتصال UDP بها.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) منشئ

ينشئ مثيلاً جديداً من الفئة [UdpClient](../) ويتصل بالمضيف البعيد المحدد على المنفذ المحدد.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | اسم المضيف البعيد في DNS الذي تنوي الاتصال به. |
| port | **int32_t** | رقم المنفذ المحلي الذي تنوي التواصل من خلاله. |

## انظر أيضًا

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [UdpClient](../)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)