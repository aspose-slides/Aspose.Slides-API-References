---
title: Create()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 소켓 주소를 사용하여 EndPoint 클래스의 새 인스턴스를 생성합니다.
type: docs
weight: 92
url: /ko/system.net/ipendpoint/create/
---
## IPEndPoint::Create(System::SharedPtr\<SocketAddress\>) method

새 지정된 소켓 주소를 사용하여 [EndPoint](../../endpoint/) 클래스의 새 인스턴스를 생성합니다.

```cpp
System::SharedPtr<EndPoint> System::Net::IPEndPoint::Create(System::SharedPtr<SocketAddress> socketAddress) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| socketAddress | [System::SharedPtr](../../../system/sharedptr/)\<[SocketAddress](../../socketaddress/)\> | 새 인스턴스를 초기화하는 데 사용될 소켓 주소입니다. |

### 반환 값

새로 생성된 EndPoint-class 인스턴스.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [EndPoint](../../endpoint/)
* Class [SocketAddress](../../socketaddress/)
* Class [IPEndPoint](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)