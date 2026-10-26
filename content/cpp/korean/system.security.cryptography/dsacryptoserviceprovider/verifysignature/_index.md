---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 데이터에 대한 DSA 서명을 검증합니다.
type: docs
weight: 118
url: /ko/system.security.cryptography/dsacryptoserviceprovider/verifysignature/
---
## DSACryptoServiceProvider::VerifySignature(ByteArrayPtr, ByteArrayPtr) 메서드

지정된 데이터에 대한 [DSA](../../dsa/) 서명을 검증합니다.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature) override
```

### 매개변수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) **rgb_signature** 로 서명되었습니다. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../../dsa/) 서명. |

### 반환값

true - **rgb_signature** 가 **rgb_hash** 로 계산된 [DSA](../../dsa/) 서명과 일치하면 true, 그렇지 않으면 false.

## 참조

* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [DSACryptoServiceProvider](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)