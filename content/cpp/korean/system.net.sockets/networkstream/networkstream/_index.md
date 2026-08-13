---
title: NetworkStream()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 인스턴스를 생성합니다.
type: docs
weight: 170
url: /ko/system.net.sockets/networkstream/networkstream/
---
## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 데이터 전송 및 수신에 사용되는 소켓입니다. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, System::IO::FileAccess, bool) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, System::IO::FileAccess access, bool ownsSocket)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 데이터 전송 및 수신에 사용되는 소켓입니다. |
| access | [System::IO::FileAccess](../../../system.io/fileaccess/) | 지정된 소켓에 대해 인스턴스에 부여된 액세스 유형을 지정합니다. |
| ownsSocket | **bool** | 값이 true이면 현재 인스턴스가 지정된 소켓의 소유권을 가져가는지를 나타냅니다. |

## NetworkStream::NetworkStream(System::SharedPtr\<System::Net::Sockets::Socket\>, bool) 생성자

새 인스턴스를 생성합니다.

```cpp
System::Net::Sockets::NetworkStream::NetworkStream(System::SharedPtr<System::Net::Sockets::Socket> socket, bool ownsSocket)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| socket | [System::SharedPtr](../../../system/sharedptr/)\<[System::Net::Sockets::Socket](../../socket/)\> | 데이터 전송 및 수신에 사용되는 소켓입니다. |
| ownsSocket | **bool** | 값이 true이면 현재 인스턴스가 지정된 소켓의 소유권을 가져가는지를 나타냅니다. |

## 참조

* 열거형 [FileAccess](../../../system.io/fileaccess/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Socket](../../socket/)
* 클래스 [NetworkStream](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)