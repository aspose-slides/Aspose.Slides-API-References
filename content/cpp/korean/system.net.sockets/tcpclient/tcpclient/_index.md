---
title: TcpClient()
second_title: Aspose.Slides for C++ API 참조
description: 새 인스턴스를 생성합니다.
type: docs
weight: 235
url: /ko/system.net.sockets/tcpclient/tcpclient/
---
## TcpClient::TcpClient(System::SharedPtr\<IPEndPoint\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::TcpClient::TcpClient(System::SharedPtr<IPEndPoint> localEP)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| localEP | [System::SharedPtr](../../../system/sharedptr/)\<[IPEndPoint](../../../system.net/ipendpoint/)\> | 소켓이 바인드되는 엔드포인트. |

## TcpClient::TcpClient() 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::TcpClient::TcpClient()
```

## TcpClient::TcpClient(AddressFamily) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::TcpClient::TcpClient(AddressFamily family)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| family | [AddressFamily](../../addressfamily/) | 주소 패밀리. |

## TcpClient::TcpClient(String, int32_t) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::TcpClient::TcpClient(String hostname, int32_t port)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hostname | [String](../../../system/string/) | 연결할 원격 호스트 이름. |
| port | **int32_t** | 연결할 원격 호스트의 포트. |

## 참고

* Enum [AddressFamily](../../addressfamily/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPEndPoint](../../../system.net/ipendpoint/)
* Class [TcpClient](../)
* Class [String](../../../system/string/)
* Namespace [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)