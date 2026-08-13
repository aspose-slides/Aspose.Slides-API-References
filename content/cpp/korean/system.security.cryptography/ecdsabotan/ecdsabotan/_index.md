---
title: ECDsaBotan()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 생성자. 기본 매개변수를 사용합니다.
type: docs
weight: 1
url: /ko/system.security.cryptography/ecdsabotan/ecdsabotan/
---
## ECDsaBotan::ECDsaBotan() 생성자

생성자. 기본 매개변수를 사용합니다.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan()
```

## ECDsaBotan::ECDsaBotan(const ECParameters\&) 생성자

생성자.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECParameters &parameters)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| parameters | const [ECParameters](../../ecparameters/)\& | 알고리즘 매개변수. |

## ECDsaBotan::ECDsaBotan(const ECCurve\&) 생성자

생성자.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const ECCurve &curve)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| curve | const [ECCurve](../../eccurve/)\& | 공개/비공개 키 쌍을 만들 때 사용되는 곡선. |

## ECDsaBotan::ECDsaBotan(int32_t) 생성자

생성자.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(int32_t key_size)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| key_size | **int32_t** | 키 크기(비트 단위). |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey\&) 생성자

생성자.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PublicKey &key)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| key | const Botan::ECDSA_PublicKey\& | Botan 공개 키. |

## ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey\&) 생성자

생성자.

```cpp
System::Security::Cryptography::ECDsaBotan::ECDsaBotan(const Botan::ECDSA_PrivateKey &key)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| key | const Botan::ECDSA_PrivateKey\& | Botan 비공개 키. |

## 참조

* 클래스 [ECDsaBotan](../)
* 구조체 [ECParameters](../../ecparameters/)
* 구조체 [ECCurve](../../eccurve/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)