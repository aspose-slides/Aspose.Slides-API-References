---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 참조
description: 데이터 서명을 확인합니다.
type: docs
weight: 118
url: /ko/system.security.cryptography/ecdsa/verifyhash/
---
## ECDsa::VerifyHash(ByteArrayPtr, ByteArrayPtr) 메서드

데이터 서명을 확인합니다.

```cpp
virtual bool System::Security::Cryptography::ECDsa::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature)=0
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 수신된 데이터에 대해 계산된 해시. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 수신된 서명. |

### 반환값

서명이 유효하면 true, 그렇지 않으면 false.

## 참조

* 타입정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [ECDsa](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)