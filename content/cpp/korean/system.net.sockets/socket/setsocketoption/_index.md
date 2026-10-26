---
title: SetSocketOption()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 소켓 옵션을 지정된 값으로 설정합니다.
type: docs
weight: 716
url: /ko/system.net.sockets/socket/setsocketoption/
---
## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, int32_t) 메서드


지정된 소켓 옵션을 지정된 값으로 설정합니다.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, int32_t optionValue)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 소켓 옵션 레벨입니다. |
| optionName | [SocketOptionName](../../socketoptionname/) | 업데이트해야 하는 옵션의 이름입니다. |
| optionValue | **int32_t** | 지정된 옵션에 설정해야 하는 값입니다. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::ArrayPtr\<uint8_t\>) 메서드


지정된 소켓 옵션을 지정된 값으로 설정합니다.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::ArrayPtr<uint8_t> optionValue)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 소켓 옵션 레벨입니다. |
| optionName | [SocketOptionName](../../socketoptionname/) | 업데이트해야 하는 옵션의 이름입니다. |
| optionValue | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 지정된 옵션에 설정해야 하는 값입니다. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, bool) 메서드


지정된 소켓 옵션을 지정된 값으로 설정합니다.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, bool optionValue)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 소켓 옵션 레벨입니다. |
| optionName | [SocketOptionName](../../socketoptionname/) | 업데이트해야 하는 옵션의 이름입니다. |
| optionValue | **bool** | 지정된 옵션에 설정해야 하는 값입니다. |

## Socket::SetSocketOption(SocketOptionLevel, SocketOptionName, System::SharedPtr\<Object\>) 메서드


지정된 소켓 옵션을 지정된 값으로 설정합니다.

```cpp
void System::Net::Sockets::Socket::SetSocketOption(SocketOptionLevel optionLevel, SocketOptionName optionName, System::SharedPtr<Object> optionValue)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| optionLevel | [SocketOptionLevel](../../socketoptionlevel/) | 소켓 옵션 레벨입니다. |
| optionName | [SocketOptionName](../../socketoptionname/) | 업데이트해야 하는 옵션의 이름입니다. |
| optionValue | [System::SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\> | 지정된 옵션에 설정해야 하는 값입니다. |

## 참조

* 열거형 [SocketOptionLevel](../../socketoptionlevel/)
* 열거형 [SocketOptionName](../../socketoptionname/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Socket](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)