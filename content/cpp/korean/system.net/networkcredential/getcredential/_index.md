---
title: GetCredential()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI와 인증 유형에 대한 자격 증명을 반환합니다.
type: docs
weight: 92
url: /ko/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) method


지정된 URI와 인증 유형에 대한 자격 증명을 반환합니다.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| authenticationType | [String](../../../system/string/) | 인증 유형. |

## NetworkCredential::GetCredential(String, int32_t, String) method


지정된 호스트 이름, 포트 및 인증 유형에 대한 자격 증명을 반환합니다.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | 호스트 이름. |
| port | **int32_t** | 포트 번호. |
| authenticationType | [String](../../../system/string/) | 인증 유형. |

## 또 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [NetworkCredential](../)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)