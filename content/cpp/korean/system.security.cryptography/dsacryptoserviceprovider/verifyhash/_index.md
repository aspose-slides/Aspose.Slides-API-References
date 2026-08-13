---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 참조
description: 데이터 서명을 확인합니다.
type: docs
weight: 222
url: /ko/system.security.cryptography/dsacryptoserviceprovider/verifyhash/
---
## DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) 메서드

데이터 서명을 확인합니다.

```cpp
bool System::Security::Cryptography::DSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 수신된 데이터에 대해 계산된 해시. |
| str | const [String](../../../system/string/)\& | 사용된 해시 알고리즘의 이름. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 수신된 서명. |

### 반환 값

서명이 유효하면 true, 그렇지 않으면 false.

## 참조

* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [DSACryptoServiceProvider](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)