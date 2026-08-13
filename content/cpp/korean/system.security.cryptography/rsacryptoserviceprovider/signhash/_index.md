---
title: SignHash()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 해시 값에 대한 서명을 계산합니다.
type: docs
weight: 196
url: /ko/system.security.cryptography/rsacryptoserviceprovider/signhash/
---
## RSACryptoServiceProvider::SignHash(ByteArrayPtr, HashAlgorithmName, SharedPtr\<RSASignaturePadding\>) 메서드

지정된 해시 값에 대한 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(ByteArrayPtr hash, HashAlgorithmName hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 해시 값. |
| hash_algorithm | [HashAlgorithmName](../../hashalgorithmname/) | 해시 알고리즘. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 패딩 모드. 지정된 해시의 [RSA](../../rsa/) 서명을 반환합니다. |

## RSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) 메서드

지정된 입력 값의 서명을 계산합니다. 구현되지 않음.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명할 데이터의 해시 값. |
| str | const [String](../../../system/string/)\& | 해시를 생성하는 데 사용된 해시 알고리즘 식별자. |

### 반환값

[RSA](../../rsa/) 지정된 데이터의 서명.

## 참조

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSASignaturePadding](../../rsasignaturepadding/)
* Class [RSACryptoServiceProvider](../)
* Class [String](../../../system/string/)
* Struct [HashAlgorithmName](../../hashalgorithmname/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)