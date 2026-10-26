---
title: SecurityPermissionFlag
second_title: Aspose.Slides for C++ API 레퍼런스
description: 보안 권한 플래그.
type: docs
weight: 27
url: /ko/system.security.permissions/securitypermissionflag/
---
## SecurityPermissionFlag 열거형

보안 권한 플래그.

```cpp
enum class SecurityPermissionFlag
```

### 값

| Name | Value | Description |
| --- | --- | --- |
| NoFlags | 0 | 액세스 없음. |
| Assertion | 1 | 권한이 부여되었음을 주장합니다. |
| UnmanagedCode | 2 | 관리되지 않는 코드를 호출합니다. |
| SkipVerification | 4 | 코드 검증을 건너뜁니다. |
| Execution | 8 | 코드를 실행합니다. |
| ControlThread | 16 | 스레드에서 작업을 수행합니다. |
| ControlEvidence | 32 | CLR 증거를 제어하거나 변경합니다. |
| ControlPolicy | 64 | 정책을 보고 변경합니다. |
| SerializationFormatter | 128 | 직렬화합니다. |
| ControlDomainPolicy | 256 | 도메인 정책을 설정합니다. |
| ControlPrincipal | 512 | 주체 객체를 제어합니다. |
| ControlAppDomain | 1024 | 응용 프로그램 도메인을 제어합니다. |
| RemotingConfiguration | 2048 | 리모팅을 구성합니다. |
| Infrastructure | 4096 | CLR 인프라에 연결합니다. |
| BindingRedirects | 8192 | 명시적 바인딩 리디렉션을 수행합니다. |
| AllFlags | 16383 | 제한 없음. |

## 참고

* 네임스페이스 [System::Security::Permissions](../)
* 라이브러리 [Aspose.Slides](../../)