---
title: DSACryptoServiceProvider()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자. 기본 매개변수를 사용합니다.
type: docs
weight: 1
url: /ko/system.security.cryptography/dsacryptoserviceprovider/dsacryptoserviceprovider/
---
## DSACryptoServiceProvider::DSACryptoServiceProvider() 생성자

Constructor. Uses default parameters.

```cpp
System::Security::Cryptography::DSACryptoServiceProvider::DSACryptoServiceProvider()
```

## DSACryptoServiceProvider::DSACryptoServiceProvider(const DSAParameters\&) 생성자

Constructor.

```cpp
System::Security::Cryptography::DSACryptoServiceProvider::DSACryptoServiceProvider(const DSAParameters &parameters)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parameters | const [DSAParameters](../../dsaparameters/)\& | Algorithm parameters. |

## DSACryptoServiceProvider::DSACryptoServiceProvider(const SharedPtr\<CspParameters\>\&) 생성자

Constructor. Not implemented.

```cpp
System::Security::Cryptography::DSACryptoServiceProvider::DSACryptoServiceProvider(const SharedPtr<CspParameters> &parameters)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| parameters | const [SharedPtr](../../../system/sharedptr/)\<[CspParameters](../../cspparameters/)\>\& | Algorithm parameters. |

## DSACryptoServiceProvider::DSACryptoServiceProvider(int32_t) 생성자

Constructor.

```cpp
System::Security::Cryptography::DSACryptoServiceProvider::DSACryptoServiceProvider(int32_t key_size)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key_size | **int32_t** | Key size in bits. |

## DSACryptoServiceProvider::DSACryptoServiceProvider(int32_t, const SharedPtr\<CspParameters\>\&) 생성자

Constructor. Not implemented.

```cpp
System::Security::Cryptography::DSACryptoServiceProvider::DSACryptoServiceProvider(int32_t key_size, const SharedPtr<CspParameters> &parameters)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| key_size | **int32_t** | Key size in bits. |
| parameters | const [SharedPtr](../../../system/sharedptr/)\<[CspParameters](../../cspparameters/)\>\& | Algorithm parameters. |

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [DSACryptoServiceProvider](../)
* Class [CspParameters](../../cspparameters/)
* Struct [DSAParameters](../../dsaparameters/)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)