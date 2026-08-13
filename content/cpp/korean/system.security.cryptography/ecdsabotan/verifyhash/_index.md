---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터 서명을 확인합니다.
type: docs
weight: 183
url: /ko/system.security.cryptography/ecdsabotan/verifyhash/
---
## ECDsaBotan::VerifyHash(ByteArrayPtr, ByteArrayPtr) 메서드

데이터 서명을 확인합니다.

```cpp
bool System::Security::Cryptography::ECDsaBotan::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 수신된 데이터에 대해 계산된 해시. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 수신된 서명. |

### 반환 값

서명이 유효하면 true, 그렇지 않으면 false.

## 참고

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [ECDsaBotan](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)