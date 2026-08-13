---
title: SignHash()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 지정된 해시 값에 대한 서명을 계산합니다.
type: docs
weight: 144
url: /ko/system.security.cryptography/rsa/signhash/
---
## RSA::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) method

지정된 해시 값에 대한 서명을 계산합니다.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 해시 값. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 해시 알고리즘. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 패딩 모드. 지정된 해시의 [RSA](../) 서명을 반환합니다. |

## 참고

* 타입 정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [RSASignaturePadding](../../rsasignaturepadding/)
* 클래스 [RSA](../)
* 구조체 [HashAlgorithmName](../../hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)