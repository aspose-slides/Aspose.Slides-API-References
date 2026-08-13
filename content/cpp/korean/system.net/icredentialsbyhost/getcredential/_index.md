---
title: GetCredential()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 호스트와 인증 유형에 대한 자격 증명을 반환합니다.
type: docs
weight: 1
url: /ko/system.net/icredentialsbyhost/getcredential/
---
## ICredentialsByHost::GetCredential(String, int32_t, String) 메서드

지정된 호스트와 인증 유형에 대한 자격 증명을 반환합니다.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentialsByHost::GetCredential(String host, int32_t port, String authenticationType)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 클라이언트를 인증하는 호스트. |
| port | **int32_t** | 호스트 포트 번호. |
| authenticationType | [String](../../../system/string/) | 인증 유형. |

## 관련 항목

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [NetworkCredential](../../networkcredential/)
* 클래스 [String](../../../system/string/)
* 클래스 [ICredentialsByHost](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)