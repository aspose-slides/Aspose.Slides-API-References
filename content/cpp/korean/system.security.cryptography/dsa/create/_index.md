---
title: Create()
second_title: Aspose.Slides for C++ API 참조
description: 기본 DSA 알고리즘 구현을 생성합니다.
type: docs
weight: 105
url: /ko/system.security.cryptography/dsa/create/
---
## DSA::Create() 메서드


기본 [DSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create()
```


### 반환 값

[DSA](../) algorithm object.

## DSA::Create(const String\&) 메서드


기본 [DSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const String &alg_name)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| alg_name | const [String](../../../system/string/)\& | 값은 \"System.Security.Cryptography.DSACryptoServiceProvider\"이어야 합니다. |

### 반환 값

[DSA](../) algorithm object.

## DSA::Create(int32_t) 메서드


지정된 키 크기로 기본 [DSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(int32_t key_size_in_bits)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| key_size_in_bits | **int32_t** | 키 크기(비트). |

## DSA::Create(const DSAParameters\&) 메서드


지정된 매개변수로 기본 [DSA](../) 알고리즘 구현을 생성합니다.

```cpp
static SharedPtr<DSA> System::Security::Cryptography::DSA::Create(const DSAParameters &parameters)
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | [DSA](../) 알고리즘의 매개변수입니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSA](../)
* Class [String](../../../system/string/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)