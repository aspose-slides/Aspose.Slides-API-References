---
title: GetSocketOption()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回與指定選項名稱相對應的值。
type: docs
weight: 729
url: /zh-hant/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) 方法

返回與指定選項名稱對應的值。

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字選項層級。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 選項名稱。 |

### 回傳值

返回與指定選項名稱對應的值。

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) 方法

取得與指定選項名稱對應的值。

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字選項層級。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 選項名稱。 |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 輸出參數，將在此指派對應的值。 |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) 方法

返回與指定選項名稱對應的值。

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 套接字選項層級。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 選項名稱。 |
| optionLength | **int32_t** | 選項長度。 |

### 回傳值

返回與指定選項名稱對應的值。

## 另見

* 列舉 [SocketOptionLevel](../../socketoptionlevel/)
* 列舉 [SocketOptionName](../../socketoptionname/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [Object](../../../system/object/)
* 類別 [Socket](../)
* 命名空間 [System::Net::Sockets](../../)
* 函式庫 [Aspose.Slides](../../../)