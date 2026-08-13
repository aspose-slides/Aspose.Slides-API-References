---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 데이터에 대한 DSA 서명을 검증합니다.
type: docs
weight: 14
url: /ko/system.security.cryptography/dsa/verifysignature/
---
## DSA::VerifySignature(ByteArrayPtr, ByteArrayPtr) method


[DSA](../) 서명을 지정된 데이터에 대해 검증합니다.

```cpp
virtual bool System::Security::Cryptography::DSA::VerifySignature(ByteArrayPtr rgb_hash, ByteArrayPtr rgb_signature)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgb_hash | [ByteArrayPtr](../../../system/bytearrayptr/) | [Data](../../../system.data/) **rgb_signature** 로 서명된. |
| rgb_signature | [ByteArrayPtr](../../../system/bytearrayptr/) | [DSA](../) 서명. |

### 반환 값

true - **rgb_signature** 가 **rgb_hash** 로부터 계산된 [DSA](../) 서명과 일치하면 true, 그렇지 않으면 false.

## 참조

* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [DSA](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)