---
title: ReceiveMessageFrom()
second_title: Aspose.Slides للغة C++ مرجع API
description: يتلقى البيانات من نقطة النهاية المحددة ويكتبها في مصفوفة البايت المحددة.
type: docs
weight: 677
url: /ar/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتعيينها إلى مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | سلوك الاستلام. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | معامل الإخراج حيث سيتم تعيين معلومات الحزمة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتعيينها إلى مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | سلوك الاستلام. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | معامل الإخراج حيث سيتم تعيين معلومات الحزمة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) طريقة

يتلقى البيانات من نقطة النهاية المحددة ويكتبها إلى مصفوفة البايت المحددة.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | مصفوفة البايت التي سيتم تعيين البيانات المستلمة فيها. |
| offset | **int32_t** | الإزاحة بالبايت في المصفوفة المحددة. |
| size | **int32_t** | عدد البايتات التي سيتم استقبالها وتعيينها إلى مصفوفة البايت المحددة بدءًا من الفهرس 'offset'. |
| socketFlags | [SocketFlags](../../socketflags/)\& | سلوك الاستلام. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | نقطة النهاية البعيدة. |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | معامل الإخراج حيث سيتم تعيين معلومات الحزمة. |

### قيمة الإرجاع

عدد البايتات المستلمة.

## انظر أيضاً

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [IPPacketInformation](../../ippacketinformation/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)