---
title: Add()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 네트워크 자격 증명을 캐시에 추가합니다.
type: docs
weight: 40
url: /ko/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) 메서드


지정된 네트워크 자격 증명을 캐시에 추가합니다.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 자격 증명이 연결된 리소스의 URI 접두사. |
| authenticationType | [String](../../../system/string/) | 인증 방식. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 추가할 자격 증명. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) 메서드


지정된 네트워크 자격 증명을 캐시에 추가합니다.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| host | [String](../../../system/string/) | 자격 증명이 연결된 호스트 이름. |
| port | **int32_t** | 포트 번호. |
| authenticationType | [String](../../../system/string/) | 인증 방식. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | 추가할 자격 증명. |

## 기타 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)