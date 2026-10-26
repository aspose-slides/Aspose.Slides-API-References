---
title: GetSocketOption()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたオプション名に対応する値を返します。
type: docs
weight: 729
url: /ja/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) method


指定されたオプション名に対応する値を返します。

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ソケットオプションレベルです。 |
| optionName | [SocketOptionName](../../socketoptionname/) | オプション名です。 |

### 戻り値

指定されたオプション名に対応する値です。

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) method


指定されたオプション名に対応する値を取得します。

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ソケットオプションレベルです。 |
| optionName | [SocketOptionName](../../socketoptionname/) | オプション名です。 |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 対応する値が代入される出力パラメーターです。 |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) method


指定されたオプション名に対応する値を返します。

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ソケットオプションレベルです。 |
| optionName | [SocketOptionName](../../socketoptionname/) | オプション名です。 |
| optionLength | **int32_t** | オプションの長さです。 |

### 戻り値

指定されたオプション名に対応する値です。

## 参照

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [Object](../../../system/object/)
* クラス [Socket](../)
* 名前空間 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)