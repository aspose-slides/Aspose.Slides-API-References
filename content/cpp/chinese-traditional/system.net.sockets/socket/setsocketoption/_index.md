---
title: SetSocketOption()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的套接字選項設定為指定的值。
type: docs
weight: 716
url: /zh-hant/system.net.sockets/socket/setsocketoption/
---
## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) 方法

將指定的套接字選項設定為指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字選項層級。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必須更新的選項名稱。 |
| optionValue | **int32_t** | 必須設定給指定選項的值。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) 方法

將指定的套接字選項設定為指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字選項層級。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必須更新的選項名稱。 |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 必須設定給指定選項的值。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, bool) 方法

將指定的套接字選項設定為指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, bool optionValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字選項層級。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必須更新的選項名稱。 |
| optionValue | **bool** | 必須設定給指定選項的值。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) 方法

將指定的套接字選項設定為指定的值。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::SharedPtr<Object> optionValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字選項層級。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 必須更新的選項名稱。 |
| optionValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 必須設定給指定選項的值。 |

## 另見

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [Object](../../../system/object/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)