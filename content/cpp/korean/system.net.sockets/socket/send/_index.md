---
title: Send()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 데이터를 소켓으로 전송합니다.
type: docs
weight: 638
url: /ko/system.net.sockets/socket/send/
---
## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| size | **int32_t** | 지정된 데이터에서 전송해야 하는 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| size | **int32_t** | 지정된 데이터에서 전송해야 하는 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| size | **int32_t** | 지정된 데이터에서 전송해야 하는 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::ArrayPtr\<uint8_t\>, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::ArrayPtr\<uint8_t\>) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::ArrayView\<uint8_t\>) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 데이터를 전송해야 하는 바이트 배열들의 컬렉션. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 데이터를 전송해야 하는 바이트 배열들의 컬렉션. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 데이터를 전송해야 하는 바이트 배열들의 컬렉션. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 전송 작업이 실패할 때 오류 코드를 할당하는 출력 매개변수. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 전송 작업이 실패할 때 오류 코드를 할당하는 출력 매개변수. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::Send(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 전송 작업이 실패할 때 오류 코드를 할당하는 출력 매개변수. |

### 반환값

전송된 바이트 수.

## Socket::Send(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) 메서드

지정된 데이터를 소켓으로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Send(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 전송 작업이 실패할 때 오류 코드를 할당하는 출력 매개변수. |

### 반환값

전송된 바이트 수.

## 참고

* Enum [SocketFlags](../../socketflags/)
* Enum [SocketError](../../socketerror/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Socket](../)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [ArraySegment](../../../system/arraysegment/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)