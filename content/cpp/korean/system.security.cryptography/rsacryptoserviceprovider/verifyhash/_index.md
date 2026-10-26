---
title: VerifyHash()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터 서명을 확인합니다.
type: docs
weight: 222
url: /ko/system.security.cryptography/rsacryptoserviceprovider/verifyhash/
---
## RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr\&, const String\&, const ByteArrayPtr\&) 메서드

데이터 서명을 확인합니다.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(const ByteArrayPtr &rgb_hash, const String &str, const ByteArrayPtr &rgb_signature)
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 수신된 데이터에 대해 계산된 해시. |
| str | const [String](../../../system/string/)\& | 사용된 해시 알고리즘의 이름. |
| rgb_signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 수신된 서명. |

### 반환 값

서명이 유효하면 true, 그렇지 않으면 false.

## RSACryptoServiceProvider::VerifyHash(ByteArrayPtr, ByteArrayPtr, const HashAlgorithmName\&, SharedPtr\<RSASignaturePadding\>) 메서드

지정된 해시의 서명이 유효함을 검증합니다.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyHash(ByteArrayPtr hash, ByteArrayPtr signature, const HashAlgorithmName &hash_algorithm, SharedPtr<RSASignaturePadding> padding) override
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hash | [ByteArrayPtr](../../../system/bytearrayptr/) | 서명된 데이터의 해시 값. |
| signature | [ByteArrayPtr](../../../system/bytearrayptr/) | 서명 데이터. |
| hash_algorithm | const [HashAlgorithmName](../../hashalgorithmname/)\& | 해시 알고리즘. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSASignaturePadding](../../rsasignaturepadding/)\> | 패딩 모드. 서명이 유효하면 true를 반환하고, 그렇지 않으면 false를 반환합니다. |

## 참조

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [RSACryptoServiceProvider](../)
* 클래스 [RSASignaturePadding](../../rsasignaturepadding/)
* 구조체 [HashAlgorithmName](../../hashalgorithmname/)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)