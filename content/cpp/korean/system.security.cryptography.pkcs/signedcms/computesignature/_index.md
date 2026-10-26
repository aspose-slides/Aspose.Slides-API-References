---
title: ComputeSignature()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 서명을 생성합니다.
type: docs
weight: 14
url: /ko/system.security.cryptography.pkcs/signedcms/computesignature/
---
## SignedCms::ComputeSignature(const SharedPtr\<CmsSigner\>\&, bool) 메서드

서명을 생성합니다.

```cpp
void System::Security::Cryptography::Pkcs::SignedCms::ComputeSignature(const SharedPtr<CmsSigner> &signer, bool silent)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| signer | const [SharedPtr](../../../system/sharedptr/)\<[CmsSigner](../../cmssigner/)\>\& | 사용할 서명자. |
| silent | **bool** | 인증서가 유효하지 않을 경우 **signer**와 연결된 유효한 인증서를 사용자에게 요청하는 것을 억제할지 여부. |

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [CmsSigner](../../cmssigner/)
* 클래스 [SignedCms](../)
* 네임스페이스 [System::Security::Cryptography::Pkcs](../../)
* 라이브러리 [Aspose.Slides](../../../)