---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터 해시의 서명을 검증합니다.
type: docs
weight: 40
url: /ko/system.security.cryptography/rsapkcs1signaturedeformatter/verifysignature/
---
## RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드


데이터 해시의 서명을 검증합니다.

```cpp
virtual bool System::Security::Cryptography::RSAPKCS1SignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature) override
```


### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터에 대해 계산된 해시. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터에 대해 받은 서명. |

### 반환 값

서명이 유효하면 true, 그렇지 않으면 false.

## 참고

* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [RSAPKCS1SignatureDeformatter](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)