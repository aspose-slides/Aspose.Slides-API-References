---
title: GetCredential()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 URI 및 인증 유형에 대한 자격 증명을 반환합니다.
type: docs
weight: 1
url: /ko/system.net/icredentials/getcredential/
---
## ICredentials::GetCredential(System::SharedPtr\<Uri\>, String) 메서드


지정된 URI 및 인증 유형에 대한 자격 증명을 반환합니다.

```cpp
virtual System::SharedPtr<NetworkCredential> System::Net::ICredentials::GetCredential(System::SharedPtr<Uri> uri, String authType)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | 클라이언트가 인증 유형을 제공하는 URI. |
| authType | [String](../../../system/string/) | 인증 유형. |

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [NetworkCredential](../../networkcredential/)
* 클래스 [Uri](../../../system/uri/)
* 클래스 [String](../../../system/string/)
* 클래스 [ICredentials](../)
* 네임스페이스 [System::Net](../../)
* 라이브러리 [Aspose.Slides](../../../)