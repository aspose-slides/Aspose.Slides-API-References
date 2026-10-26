---
title: NetworkStream()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的實例。
type: docs
weight: 170
url: /zh-hant/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) 建構函式

建立新的實例。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 用於傳送和接收資料的 Socket。 |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) 建構函式

建立新的實例。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 用於傳送和接收資料的 Socket。 |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | 指定指派給實例的存取類型，針對指定的 Socket。 |
| ownsSocket | **bool** | 當值為 true 時，此值表示目前實例是否取得指定 Socket 的擁有權。 |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) 建構函式

建立新的實例。

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 用於傳送和接收資料的 Socket。 |
| ownsSocket | **bool** | 當值為 true 時，此值表示目前實例是否取得指定 Socket 的擁有權。 |

## 另請參閱

* 列舉 [FileAccess](../../../system.io/fileaccess/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Socket](../../socket/)
* 類別 [NetworkStream](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)