---
title: ReceiveMessageFrom()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。
type: docs
weight: 677
url: /ja/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 受信するバイト数で、'offset' インデックスから指定されたバイト配列に割り当てられます。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモート エンドポイント。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | パケットに関する情報が割り当てられる出力パラメーター。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 受信するバイト数で、'offset' インデックスから指定されたバイト配列に割り当てられます。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモート エンドポイント。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | パケットに関する情報が割り当てられる出力パラメーター。 |

### 戻り値

受信したバイト数。

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

指定されたエンドポイントからデータを受信し、指定されたバイト配列に書き込みます。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 受信したデータが割り当てられるバイト配列。 |
| offset | **int32_t** | 指定された配列内のバイト単位のオフセット。 |
| size | **int32_t** | 受信するバイト数で、'offset' インデックスから指定されたバイト配列に割り当てられます。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 受信の動作。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | リモート エンドポイント。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | パケットに関する情報が割り当てられる出力パラメーター。 |

### 戻り値

受信したバイト数。

## 参照

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [EndPoint](../../../system.net/endpoint/)
* クラス [IPPacketInformation](../../ippacketinformation/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)