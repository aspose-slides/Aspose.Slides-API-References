---
title: SignHash()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 입력 값의 서명을 계산합니다.
type: docs
weight: 92
url: /ko/system.security.cryptography/ecdsa/signhash/
---
## ECDsa::SignHash(const ByteArrayPtr\&) 메서드


지정된 입력 값의 서명을 계산합니다.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::ECDsa::SignHash(const ByteArrayPtr &hash)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명될 데이터의 해시 값. |

### 반환 값

지정된 해시의 ECDSA 서명.

## 참고

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [ECDsa](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)