---
title: SignHash()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 입력 값의 서명을 계산합니다.
type: docs
weight: 144
url: /ko/system.security.cryptography/ecdsabotan/signhash/
---
## ECDsaBotan::SignHash(const ByteArrayPtr\&) 메서드

지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::ECDsaBotan::SignHash(const ByteArrayPtr &hash) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명할 데이터의 해시 값. |

### 반환 값

지정된 해시의 ECDSA 서명.

## 참고

* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [ECDsaBotan](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)