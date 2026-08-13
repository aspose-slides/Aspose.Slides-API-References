---
title: Remove()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI 접두사와 인증 유형에 대한 네트워크 자격 증명을 제거합니다.
type: docs
weight: 53
url: /ko/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) 메서드


지정된 URI 접두사와 인증 유형에 대한 네트워크 자격 증명을 제거합니다.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI 접두사입니다. |
| authenticationType | [String](../../../system/string/) | 인증 유형입니다. |

## CredentialCache::Remove(String, int32_t, String) 메서드


지정된 호스트 이름, 포트 및 인증 유형에 대한 네트워크 자격 증명을 제거합니다.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 자격 증명이 연결된 호스트 이름입니다. |
| port | **int32_t** | 포트 번호입니다. |
| authenticationType | [String](../../../system/string/) | 인증 유형입니다. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [CredentialCache](../)
* 네임스페이스 [System::Net](../../)
* Library [Aspose.Slides](../../../)