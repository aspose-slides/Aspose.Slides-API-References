---
title: SendTo()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 데이터를 지정된 엔드포인트로 전송합니다.
type: docs
weight: 651
url: /ko/system.net.sockets/socket/sendto/
---
## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t offset, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| offset | **int32_t** | 지정된 배열에서 바이트 단위의 오프셋. |
| size | **int32_t** | 'offset' 매개변수부터 시작하는 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| size | **int32_t** | 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| size | **int32_t** | 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, int32_t, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, int32_t size, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| size | **int32_t** | 지정된 배열의 바이트 수. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, SocketFlags, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, SocketFlags socketFlags, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| socketFlags | [SocketFlags](../../socketflags/) | 전송 동작. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::ArrayPtr<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 전송할 데이터. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::ArrayView\<uint8_t\>, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
int32_t System::Net::Sockets::Socket::SendTo(System::Details::ArrayView<uint8_t> buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::ArrayView\<**uint8_t**\> | 전송할 데이터. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## Socket::SendTo(System::Details::StackArray\<uint8_t, N\>\&, System::SharedPtr\<EndPoint\>) 메서드

지정된 데이터를 지정된 엔드포인트로 전송합니다.

```cpp
template<std::size_t> int32_t System::Net::Sockets::Socket::SendTo(System::Details::StackArray<uint8_t, N> &buffer, System::SharedPtr<EndPoint> remoteEP)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| buffer | System::Details::StackArray\<**uint8_t**, N\>\& | 전송할 데이터. |
| remoteEP | [System::SharedPtr](../../../system/sharedptr/)\<[EndPoint](../../../system.net/endpoint/)\> | 원격 엔드포인트. |

### 반환 값

전송된 바이트 수.

## 참고

* 열거형 [SocketFlags](../../socketflags/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [EndPoint](../../../system.net/endpoint/)
* 클래스 [Socket](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)