---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이름을 기반으로 해시 알고리즘을 생성합니다.
type: docs
weight: 118
url: /ko/system.security.cryptography/hashalgorithm/create/
---
## HashAlgorithm::Create(const String\&) 메서드

이름을 기반으로 해시 알고리즘을 생성합니다.

```cpp
static SharedPtr<HashAlgorithm> System::Security::Cryptography::HashAlgorithm::Create(const String &hashName)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hashName | const [String](../../../system/string/)\& | 다음 값 중 하나: \"MD5\", \"SHA1\", \"SHA256\", \"SHA384\", \"SHA512\", \"RIPEMD160\" 또는 \"System.Security.Cryptography.\" 접두사가 붙은 경우 |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [HashAlgorithm](../)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)