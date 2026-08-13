---
title: Receive()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.
type: docs
weight: 664
url: /ko/system.net.sockets/socket/receive/
---
## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| size | **int32_t** | 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| size | **int32_t** | 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |
| size | **int32_t** | 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::ArrayPtr\<uint8_t\>) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 인덱스부터 지정된 바이트 배열에 할당될 수신 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 인덱스부터 지정된 바이트 배열에 할당될 수신 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 인덱스부터 지정된 바이트 배열에 할당될 수신 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 인덱스부터 지정된 바이트 배열에 할당될 수신 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 수신 작업이 실패했을 때 오류 코드가 할당되는 출력 매개변수. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, SocketError\&) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 인덱스부터 지정된 바이트 배열에 할당될 수신 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 수신 작업이 실패했을 때 오류 코드가 할당되는 출력 매개변수. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, SocketError\&) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::Receive(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 인덱스부터 지정된 바이트 배열에 할당될 수신 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 수신 작업이 실패했을 때 오류 코드가 할당되는 출력 매개변수. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 수신된 데이터가 할당될 바이트 배열들. |

### 반환값

수신된 바이트 수.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 수신된 데이터가 할당될 바이트 배열들. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |

### 반환값

받은 바이트 수.

## Socket::Receive(System::SharedPtr\<Collections::Generic::IList\<ArraySegment\<uint8_t\>\>\>, SocketFlags, SocketError\&) 메서드


소켓에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::Receive(System::SharedPtr<Collections::Generic::IList<ArraySegment<uint8_t>>> buffers, SocketFlags socketFlags, SocketError &errorCode)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffers | [System::SharedPtr](../../../system/sharedptr/)\<[Collections::Generic::IList](../../../system.collections.generic/ilist/)\<[ArraySegment](../../../system/arraysegment/)\<**uint8_t**\>\>\> | 수신된 데이터가 할당될 바이트 배열들. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| errorCode | [SocketError](../../socketerror/)\& | 수신 작업이 실패했을 때 오류 코드가 할당되는 출력 매개변수. |

### 반환값

받은 바이트 수.

## 보기

* 열거형 [SocketFlags](../../socketflags/)
* 열거형 [SocketError](../../socketerror/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Socket](../)
* 클래스 [IList](../../../system.collections.generic/ilist/)
* 클래스 [ArraySegment](../../../system/arraysegment/)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)