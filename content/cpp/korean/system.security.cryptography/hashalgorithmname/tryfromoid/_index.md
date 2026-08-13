---
title: TryFromOid()
second_title: Aspose.Slides for C++ API 참조
description: OID 값으로부터 HashAlgorithmName을 생성하려고 시도합니다.
type: docs
weight: 66
url: /ko/system.security.cryptography/hashalgorithmname/tryfromoid/
---
## HashAlgorithmName::TryFromOid(const String\&, HashAlgorithmName\&) 메서드


OID 값으로부터 [HashAlgorithmName](../)을(를) 생성하려고 시도합니다.

```cpp
static bool System::Security::Cryptography::HashAlgorithmName::TryFromOid(const String &oid_value, HashAlgorithmName &value)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| oid_value | const [String](../../../system/string/)\& | OID 값. |
| value | [HashAlgorithmName](../)\& | 출력 [HashAlgorithmName](../). |

### 반환 값

지정된 OID가 유효한 해시 알고리즘인 경우 true, 그렇지 않으면 false.

## 참조

* 클래스 [String](../../../system/string/)
* 구조체 [HashAlgorithmName](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)