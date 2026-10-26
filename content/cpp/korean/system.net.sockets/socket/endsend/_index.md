---
title: EndSend()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 비동기 전송 작업이 완료될 때까지 대기합니다.
type: docs
weight: 508
url: /ko/system.net.sockets/socket/endsend/
---
## Socket::EndSend(System::SharedPtr\<IAsyncResult\>) 메서드

지정된 비동기 전송 작업이 완료될 때까지 대기합니다.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 객체는 비동기 전송 작업을 나타냅니다. |

### 반환 값

전송된 바이트 수.

## Socket::EndSend(System::SharedPtr\<IAsyncResult\>, SocketError\&) 메서드

지정된 비동기 전송 작업이 완료될 때까지 대기합니다.

```cpp
int32_t System::Net::Sockets::Socket::EndSend(System::SharedPtr<IAsyncResult> asyncResult, SocketError &errorCode)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| asyncResult | [System::SharedPtr](../../../system/sharedptr/)\<[IAsyncResult](../../../system/iasyncresult/)\> | [IAsyncResult](../../../system/iasyncresult/) 객체는 비동기 전송 작업을 나타냅니다. |
| errorCode | [SocketError](../../socketerror/)\& | 전송 작업이 실패할 때 오류 코드를 할당받는 출력 매개변수. |

### 반환 값

전송된 바이트 수.

## 참고

* Enum [SocketError](../../socketerror/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAsyncResult](../../../system/iasyncresult/)
* 클래스 [Socket](../)
* 네임스페이스 [System::Net::Sockets](../../)
* Library [Aspose.Slides](../../../)