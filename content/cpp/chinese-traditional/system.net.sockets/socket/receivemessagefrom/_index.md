---
title: ReceiveMessageFrom()
second_title: Aspose.Slides for C++ API 參考
description: 從指定的端點接收資料，並寫入指定的位元組陣列。
type: docs
weight: 677
url: /zh-hant/system.net.sockets/socket/receivemessagefrom/
---
## Socket::ReceiveMessageFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 接收的資料將指派至的位元組陣列。 |
| offset | **int32_t** | 指定陣列中的位元組偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | 將指派封包資訊的輸出參數。 |

### 傳回值

接收的位元組數。

## Socket::ReceiveMessageFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 接收的資料將指派至的位元組陣列。 |
| offset | **int32_t** | 指定陣列中的位元組偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | 將指派封包資訊的輸出參數。 |

### 傳回值

接收的位元組數。

## Socket::ReceiveMessageFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags\&, System::SharedPtr\<EndPoint\>\&, IPPacketInformation\&) method

從指定的端點接收資料，並寫入指定的位元組陣列。

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveMessageFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags &socketFlags, System::SharedPtr<EndPoint> &remoteEP, IPPacketInformation &ipPacketInformation)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 接收的資料將指派至的位元組陣列。 |
| offset | **int32_t** | 指定陣列中的位元組偏移量。 |
| size | **int32_t** | 要接收的位元組數，將從「offset」索引指派至指定的位元組陣列。 |
| socketFlags | [SocketFlags](../../socketflags/)\& | 接收行為。 |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 遠端端點。 |
| ipPacketInformation | [IPPacketInformation](../../ippacketinformation/)\& | 將指派封包資訊的輸出參數。 |

### 傳回值

接收的位元組數。

## 另請參閱

* 列舉 [SocketFlags](../../socketflags/)
* 型別定義 [ArrayPtr](../../../system/arrayptr/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [EndPoint](../../../system.net/endpoint/)
* 類別 [IPPacketInformation](../../ippacketinformation/)
* 類別 [Socket](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)