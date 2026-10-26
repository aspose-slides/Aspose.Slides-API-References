---
title: SocketOptionName
second_title: Aspose.Slides for C++ API 참조
description: Socket 클래스에 대한 소켓 옵션 이름을 정의합니다.
type: docs
weight: 248
url: /ko/system.net.sockets/socketoptionname/
---
## SocketOptionName 열거형

[Socket](../socket/) 클래스에 대한 소켓 옵션 이름을 정의합니다.

```cpp
enum class SocketOptionName
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| Debug | 1 | 디버깅 정보를 기록합니다. |
| AcceptConnection | 2 | 소켓이 들어오는 연결을 듣고 있는지 여부를 나타냅니다. |
| ReuseAddress | 4 | 이미 사용 중인 주소에 소켓을 바인딩할 수 있는지 여부를 나타냅니다. |
| KeepAlive | 8 | 소켓 연결에 대해 'Keep-Alive' 패킷을 활성화합니다. |
| DontRoute | 16 | 패킷이 인터페이스 주소로 직접 전송되는지 여부를 나타냅니다. |
| Broadcast | 32 | 소켓이 브로드캐스트 메시지를 보낼 수 있는지 여부를 나타냅니다. |
| UseLoopback | 64 | 가능한 경우 하드웨어를 우회합니다. |
| Linger | 128 | 시스템은 데이터를 전송할 수 있을 때까지 닫기 시도 시 프로세스를 차단합니다. |
| OutOfBandInline | 256 | 정상 데이터 스트림에서 밴드 외 데이터를 수신합니다. |
| DontLinger | n/a | 소켓이 linger 없이 닫히는지 여부를 나타냅니다. |
| ExclusiveAddressUse | n/a | 소켓이 바인드된 주소를 독점적으로 사용합니다. |
| SendBuffer | 4097 | 전송 버퍼 크기를 지정합니다. |
| ReceiveBuffer | 4098 | 수신 버퍼 크기를 지정합니다. |
| SendLowWater | 4099 | 전송 작업에 필요한 최소 데이터 양을 지정합니다. |
| ReceiveLowWater | 4100 | 수신 작업에 필요한 최소 데이터 양을 지정합니다. |
| SendTimeout | 4101 | 동기 전송 작업의 타임아웃을 지정합니다. |
| ReceiveTimeout | 4102 | 동기 수신 작업의 타임아웃을 지정합니다. |
| Error | 4103 | 오류 상태를 반환하고 초기화합니다. |
| Type | 4104 | 소켓 종류를 반환합니다. |
| ReuseUnicastPort | 12295 | 시스템이 외부 연결을 위해 임시 포트 할당을 연기해야 하는지 여부를 나타냅니다. |
| MaxConnections | 2147483647 | 이 옵션은 지원되지 않습니다. 청취 대기열의 최대 길이를 지정하는 데 사용되었습니다. |
| IPOptions | 1 | 출력 데이터그램에 삽입해야 하는 IP 옵션을 지정합니다. |
| HeaderIncluded | 2 | 헤더가 출력 데이터그램에 포함됩니다. |
| TypeOfService | 3 | IP 헤더 서비스 필드 유형을 변경합니다. |
| IpTimeToLive | 4 | IP 생존 시간(TTL)입니다. |
| MulticastInterface | 9 | 출력 멀티캐스트 패킷의 인터페이스를 설정합니다. |
| MulticastTimeToLive | 10 | IP 멀티캐스트의 생존 시간(TTL)입니다. |
| MulticastLoopback | 11 | IP 멀티캐스트 루프백입니다. |
| AddMembership | 12 | IP 그룹 멤버십을 추가합니다. |
| DropMembership | 13 | IP 그룹 멤버십을 삭제합니다. |
| DontFragment | 14 | IP 데이터그램을 조각화하지 않습니다. |
| AddSourceMembership | 15 | IP 그룹/소스를 가입합니다. |
| DropSourceMembership | 16 | IP 그룹/소스를 탈퇴합니다. |
| BlockSource | 17 | IP 그룹/소스를 차단합니다. |
| UnblockSource | 18 | IP 그룹/소스 차단을 해제합니다. |
| PacketInformation | 19 | IPv4 패킷 정보를 수신합니다. |
| HopLimit | 21 | 패킷의 홉 수를 포함하는 정수를 전달합니다. |
| IPProtectionLevel | 23 | IPv6 소켓을 지정된 범위로 제한합니다. |
| IPv6Only | 27 | 소켓이 IPv6 패킷만 송수신하도록 제한됩니다. |
| NoDelay | 1 | 전송 패킷을 병합하는 Nagle 알고리즘을 비활성화합니다. |
| BsdUrgent | 2 | RFC-1222에 정의된 긴급 데이터를 사용합니다. |
| Expedited | 2 | RFC-1222에 정의된 급송 데이터를 사용합니다. |
| NoChecksum | 1 | 체크섬을 0으로 설정하여 UDP 데이터그램을 전송합니다. |
| ChecksumCoverage | 20 | UDP 체크섬 적용 범위를 설정하거나 가져옵니다. |
| UpdateAcceptContext | 28683 | 청취 소켓과 동일한 속성을 가진 클라이언트 소켓을 업데이트합니다. |
| UpdateConnectContext | 28688 | 청취 소켓과 동일한 속성을 가진 클라이언트 소켓을 업데이트합니다. |

## 참고

* 네임스페이스 [System::Net::Sockets](../)
* 라이브러리 [Aspose.Slides](../../)