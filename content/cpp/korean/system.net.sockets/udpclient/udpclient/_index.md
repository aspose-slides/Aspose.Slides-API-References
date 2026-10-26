---
title: UdpClient()
second_title: C++용 Aspose.Slides API 참조
description: UdpClient 클래스의 새 인스턴스를 초기화합니다.
type: docs
weight: 27
url: /ko/system.net.sockets/udpclient/udpclient/
---
## UdpClient::UdpClient() 생성자

[UdpClient](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Net::Sockets::UdpClient::UdpClient()
```

## UdpClient::UdpClient(AddressFamily) 생성자

[UdpClient](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Net::Sockets::UdpClient::UdpClient(AddressFamily family)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | 소켓의 주소 지정 체계를 지정하는 값. |

## UdpClient::UdpClient(int32_t) 생성자

[UdpClient](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | 통신하려는 로컬 포트 번호. |

## UdpClient::UdpClient(int32_t, AddressFamily) 생성자

[UdpClient](../) 클래스의 새 인스턴스를 초기화합니다.

```cpp
System::Net::Sockets::UdpClient::UdpClient(int32_t port, AddressFamily family)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| port | **int32_t** | 통신하려는 로컬 포트 번호. |
| family | [AddressFamily](../../addressfamily/) | 소켓의 주소 지정 체계를 지정하는 값. |

## UdpClient::UdpClient(System::SharedPtr\<IPEndPoint\>) 생성자

[UdpClient](../) 클래스의 새 인스턴스를 초기화합니다. param local EP UDP 연결을 바인딩할 로컬 엔드포인트.

```cpp
System::Net::Sockets::UdpClient::UdpClient(System::SharedPtr<IPEndPoint> localEP)
```

## UdpClient::UdpClient(String, int32_t) 생성자

[UdpClient](../) 클래스의 새 인스턴스를 생성하고 지정된 포트의 지정된 원격 호스트에 연결합니다.

```cpp
System::Net::Sockets::UdpClient::UdpClient(String hostname, int32_t port)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 연결하려는 원격 DNS 호스트의 이름. |
| port | **int32_t** | 통신하려는 로컬 포트 번호. |

## 참고

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [UdpClient](../)
* 클래스 [IPEndPoint](../../../system.net/ipendpoint/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)