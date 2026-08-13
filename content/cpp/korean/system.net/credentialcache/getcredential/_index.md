---
title: GetCredential()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 지정된 URI 접두사 및 인증 유형에 대한 자격 증명을 반환합니다.
type: docs
weight: 66
url: /ko/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) 메서드

지정된 URI 접두사 및 인증 유형에 대한 자격 증명을 반환합니다.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI 접두사입니다. |
| authenticationType | [String](../../../system/string/) | 인증 유형입니다. |

## CredentialCache::GetCredential(String, int32_t, String) 메서드

지정된 호스트 이름, 포트 및 인증 유형에 대한 자격 증명을 반환합니다.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 자격 증명이 연결된 호스트 이름입니다. |
| port | **int32_t** | 포트 번호입니다. |
| authenticationType | [String](../../../system/string/) | 인증 유형입니다. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [NetworkCredential](../../networkcredential/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [CredentialCache](../)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)