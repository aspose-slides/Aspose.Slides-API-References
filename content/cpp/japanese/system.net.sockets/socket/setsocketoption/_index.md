---
title: SetSocketOption()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたソケットオプションを指定された値に設定します。
type: docs
weight: 716
url: /ja/system.net.sockets/socket/setsocketoption/
---
## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) メソッド

指定されたソケットオプションを指定された値に設定します。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ソケットオプションのレベルです。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 更新する必要があるオプションの名前です。 |
| optionValue | **int32_t** | 指定されたオプションに設定する必要がある値です。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) メソッド

指定されたソケットオプションを指定された値に設定します。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ソケットオプションのレベルです。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 更新する必要があるオプションの名前です。 |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 指定されたオプションに設定する必要がある値です。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, bool) メソッド

指定されたソケットオプションを指定された値に設定します。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, bool optionValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ソケットオプションのレベルです。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 更新する必要があるオプションの名前です。 |
| optionValue | **bool** | 指定されたオプションに設定する必要がある値です。 |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) メソッド

指定されたソケットオプションを指定された値に設定します。

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::SharedPtr<Object> optionValue)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | ソケットオプションのレベルです。 |
| optionName | [SocketOptionName](../../socketoptionname/) | 更新する必要があるオプションの名前です。 |
| optionValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 指定されたオプションに設定する必要がある値です。 |

## 参照

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [Object](../../../system/object/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)