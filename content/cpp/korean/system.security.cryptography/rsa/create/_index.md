---
title: Create()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 RSA 알고리즘 구현을 생성합니다.
type: docs
weight: 183
url: /ko/system.security.cryptography/rsa/create/
---
## RSA::Create() 메서드

기본 [RSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create()
```

## RSA::Create(const String\&) 메서드

기본 [RSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const String &alg_name)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | 반드시 "System.Security.Cryptography.RSACryptoServiceProvider"이어야 합니다. |

## RSA::Create(int32_t) 메서드

지정된 키 크기를 갖는 기본 [RSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(int32_t key_size_in_bits)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | 키 크기(비트 단위)입니다. |

## RSA::Create(const RSAParameters\&) 메서드

지정된 매개변수를 사용한 기본 [RSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<RSA> System::Security::Cryptography::RSA::Create(const RSAParameters &parameters)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parameters | const [RSAParameters](../../rsaparameters/)\& | [RSA](../) 알고리즘에 대한 매개변수입니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [RSA](../)
* Class [String](../../../system/string/)
* Struct [RSAParameters](../../rsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)