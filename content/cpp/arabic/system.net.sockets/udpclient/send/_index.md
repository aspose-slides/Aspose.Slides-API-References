---
title: Send()
second_title: مرجع API Aspose.Slides للـ C++
description: يُرسل حزمة UDP إلى المضيف عند نقطة النهاية البعيدة.
type: docs
weight: 79
url: /ar/system.net.sockets/udpclient/send/
---
## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, System::SharedPtr\<IPEndPoint\>) طريقة


يرسل حزمة UDP إلى المضيف عند نقطة النهاية البعيدة.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, System::SharedPtr<IPEndPoint> endPoint)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة من النوع [Byte](../../../system/byte/) لإرسالها |
| bytes | **int32_t** | عدد البايتات في الحزمة. |
| endPoint | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | [IPEndPoint](../../../system.net/ipendpoint/) تمثل المضيف والمنفذ الذي سيتم إرسال الحزمة إليه. |

### قيمة الإرجاع

عدد البايتات التي تم إرسالها.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t, String, int32_t) طريقة


يرسل حزمة UDP إلى المنفذ المحدد على المضيف البعيد المحدد.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes, String hostname, int32_t port)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة من النوع [Byte](../../../system/byte/) لإرسالها |
| bytes | **int32_t** | عدد البايتات في الحزمة. |
| hostname | [String](../../../system/string/) | اسم المضيف البعيد. |
| port | **int32_t** | رقم منفذ بعيد. |

### قيمة الإرجاع

عدد البايتات التي تم إرسالها.

## UdpClient::Send(System::ArrayPtr\<uint8_t\>, int32_t) طريقة


يرسل حزمة UDP إلى مضيف بعيد.

```cpp
int32_t System::Net::Sockets::UdpClient::Send(System::ArrayPtr<uint8_t> dgram, int32_t bytes)
```


### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| dgram | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة من النوع [Byte](../../../system/byte/) لإرسالها. |
| bytes | **int32_t** | عدد البايتات في الحزمة. |

### قيمة الإرجاع

عدد البايتات التي تم إرسالها.

## انظر أيضًا

* تعريف نوع [ArrayPtr](../../../system/arrayptr/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IPEndPoint](../../../system.net/ipendpoint/)
* فئة [UdpClient](../)
* فئة [String](../../../system/string/)
* مساحة الاسم [System::Net::Sockets](../../)
* المكتبة [Aspose.Slides](../../../)