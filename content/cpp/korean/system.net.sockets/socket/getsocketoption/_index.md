---
title: GetSocketOption()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 옵션 이름에 해당하는 값을 반환합니다.
type: docs
weight: 729
url: /ko/system.net.sockets/socket/getsocketoption/
---
## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName) 메서드


지정된 옵션 이름에 해당하는 값을 반환합니다.

```cpp
System::SharedPtr<Object> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The option name. |

### 반환값

지정된 옵션 이름에 해당하는 값입니다.

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) 메서드


지정된 옵션 이름에 해당하는 값을 가져옵니다.

```cpp
void System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The option name. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | The output parameter where the corresponding value will be assigned. |

## Socket::GetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) 메서드


지정된 옵션 이름에 해당하는 값을 반환합니다.

```cpp
System::ArrayPtr<uint8_t> System::Net::Sockets::Socket::GetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionLength)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | The socket option level. |
| optionName | [SocketOptionName](../../socketoptionname/) | The option name. |
| optionLength | **int32_t** | The option length. |

### 반환값

지정된 옵션 이름에 해당하는 값입니다.

## 참조

* Enum [SocketOptionLevel](../../socketoptionlevel/)
* Enum [SocketOptionName](../../socketoptionname/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [Socket](../)
* 네임스페이스 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)