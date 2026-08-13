---
title: EndAcceptTcpClient()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비동기 수락 작업이 완료될 때까지 대기합니다.
type: docs
weight: 183
url: /ko/system.net.sockets/tcplistener/endaccepttcpclient/
---
## TcpListener::EndAcceptTcpClient(System::SharedPtr\<IAsyncResult\>) 메서드

지정된 비동기 수락 작업이 완료될 때까지 대기합니다.

```cpp
System::SharedPtr<TcpClient> System::Net::Sockets::TcpListener::EndAcceptTcpClient(System::SharedPtr<IAsyncResult> asyncResult)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | 비동기 수락 작업을 나타내는 [IAsyncResult](../../../system/iasyncresult/) 객체. |

## 참조

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [TcpClient](../../tcpclient/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [TcpListener](../)
* 네임스페이스 [System::Net::Sockets](../../)
* 라이브러리 [Aspose.Slides](../../../)