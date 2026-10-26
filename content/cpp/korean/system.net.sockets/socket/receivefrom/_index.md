---
title: ReceiveFrom()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.
type: docs
weight: 690
url: /ko/system.net.sockets/socket/receivefrom/
---
## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | ‘offset’ 인덱스에서 지정된 바이트 배열에 할당될 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | ‘offset’ 인덱스에서 지정된 바이트 배열에 할당될 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | ‘offset’ 인덱스에서 지정된 바이트 배열에 할당될 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| size | **int32_t** | ‘offset’ 인덱스에서 지정된 바이트 배열에 할당될 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| size | **int32_t** | ‘offset’ 인덱스에서 지정된 바이트 배열에 할당될 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |
| size | **int32_t** | ‘offset’ 인덱스에서 지정된 바이트 배열에 할당될 수신할 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| socketFlags | [SocketFlags](../../socketflags/) | 수신 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 수신된 데이터가 할당될 바이트 배열. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## Socket::ReceiveFrom(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>\&) 메서드

지정된 엔드포인트에서 데이터를 수신하고 지정된 바이트 배열에 기록합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::ReceiveFrom(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> &remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 수신된 데이터가 할당될 바이트 배열. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\>\& | 원격 엔드포인트. |

### 반환값

수신된 바이트 수.

## 또 보기

* Enum [SocketFlags](../../socketflags/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../../system.net/endpoint/)
* Class [Socket](../)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)