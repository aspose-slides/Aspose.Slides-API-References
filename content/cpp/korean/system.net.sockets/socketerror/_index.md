---
title: SocketError
second_title: Aspose.Slides for C++ API 참조
description: 소켓 오류 유형을 나열합니다.
type: docs
weight: 209
url: /ko/system.net.sockets/socketerror/
---
## SocketError 열거형

소켓 오류 유형을 나열합니다.

```cpp
enum class SocketError
```

### Values

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Success | 0 | 소켓 작업이 성공적으로 완료되었습니다. |
| SocketError | -1 | 특정되지 않은 소켓 오류가 발생했습니다. |
| Interrupted | 10004 | 블로킹 소켓 호출이 취소되었습니다. |
| AccessDenied | 10013 | 소켓에 대한 접근이 거부되었습니다. |
| Fault | 10014 | 잘못된 포인터 주소가 감지되었습니다. |
| InvalidArgument | 10022 | 잘못된 인수가 제공되었습니다. |
| TooManyOpenSockets | 10024 | 기본 소켓 제공자에 열려 있는 소켓이 너무 많습니다. |
| WouldBlock | 10035 | 비블로킹 소켓에서 작업을 즉시 완료할 수 없습니다. |
| InProgress | 10036 | 블로킹 작업이 진행 중입니다. |
| AlreadyInProgress | 10037 | 비블로킹 소켓에 이미 실행 중인 작업이 있습니다. |
| NotSocket | 10038 | 소켓이 아닌 대상에 소켓 작업을 호출하려는 시도입니다. |
| DestinationAddressRequired | 10039 | 필요한 주소가 소켓 작업에서 누락되었습니다. |
| MessageSize | 10040 | 데이터그램이 너무 깁니다. |
| ProtocolType | 10041 | 이 소켓에서 지원되지 않는 프로토콜 유형입니다. |
| ProtocolOption | 10042 | 알 수 없거나 잘못되었거나 지원되지 않은 옵션 또는 레벨이 사용되었습니다. |
| ProtocolNotSupported | 10043 | 프로토콜이 구현되지 않았거나 구성되지 않았습니다. |
| SocketNotSupported | 10044 | 주소 패밀리가 지정된 소켓을 지원하지 않습니다. |
| OperationNotSupported | 10045 | 프로토콜 패밀리가 주소 패밀리를 지원하지 않습니다. |
| ProtocolFamilyNotSupported | 10046 | 프로토콜 패밀리가 구현되지 않았거나 구성되지 않았습니다. |
| AddressFamilyNotSupported | 10047 | 지정된 주소 패밀리가 지원되지 않습니다. |
| AddressAlreadyInUse | 10048 | 주소는 한 번만 사용할 수 있습니다. |
| AddressNotAvailable | 10049 | 선택된 IP 주소가 이 컨텍스트에서 유효하지 않습니다. |
| NetworkDown | 10050 | 네트워크를 사용할 수 없습니다. |
| NetworkUnreachable | 10051 | 원격 호스트로 가는 경로가 없습니다. |
| NetworkReset | 10052 | 애플리케이션이 이미 시간 초과된 연결에 'Keep-Alive'를 설정하려고 시도했습니다. |
| ConnectionAborted | 10053 | 연결이 중단되었습니다. |
| ConnectionReset | 10054 | 연결이 원격 피어에 의해 재설정되었습니다. |
| NoBufferSpaceAvailable | 10055 | 소켓 작업에 사용할 수 있는 빈 버퍼 공간이 없습니다. |
| IsConnected | 10056 | 소켓이 이미 연결되어 있습니다. |
| NotConnected | 10057 | 애플리케이션이 데이터를 보내거나 받으려고 시도했지만 소켓이 연결되어 있지 않습니다. |
| Shutdown | 10058 | 소켓이 이미 닫혔으므로 데이터 전송 또는 수신 요청이 금지되었습니다. |
| TimedOut | 10060 | 연결 시도가 시간 초과되었거나 연결된 호스트가 응답하지 않았습니다. |
| ConnectionRefused | 10061 | 원격 호스트가 연결을 적극적으로 거부하고 있습니다. |
| HostDown | 10064 | 원격 호스트가 다운되어 있어 작업이 실패했습니다. |
| HostUnreachable | 10065 | 지정된 호스트로 가는 네트워크 경로가 존재하지 않습니다. |
| ProcessLimit | 10067 | 기본 소켓 제공자를 사용 중인 프로세스가 너무 많습니다. |
| SystemNotReady | 10091 | 네트워크 서브시스템을 사용할 수 없습니다. |
| VersionNotSupported | 10092 | 기본 소켓 제공자의 버전이 범위를 벗어났습니다. |
| NotInitialized | 10093 | 기본 소켓 제공자가 초기화되지 않았습니다. |
| Disconnecting | 10101 | 우아한 종료가 진행 중입니다. |
| TypeNotFound | 10109 | 지정된 클래스를 찾을 수 없습니다. |
| HostNotFound | 11001 | 지정된 호스트를 알 수 없습니다. |
| TryAgain | 11002 | 호스트 이름을 확인할 수 없습니다. |
| NoRecovery | 11003 | 오류가 복구 불가능하거나 요청된 데이터베이스를 찾을 수 없습니다. |
| NoData | 11004 | 요청된 이름이나 IP 주소를 이름 서버에서 찾을 수 없습니다. |

## 참고

* 네임스페이스 [System::Net::Sockets](../)
* 라이브러리 [Aspose.Slides](../../)