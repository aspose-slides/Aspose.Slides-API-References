---
title: CreateSignature()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 데이터에 대한 서명을 생성합니다.
type: docs
weight: 1
url: /ko/system.security.cryptography/asymmetricsignatureformatter/createsignature/
---
## AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) 메서드

지정된 데이터에 대한 시그니처를 생성합니다.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/)를 해시 계산에 사용합니다. |

### 반환값

바이트 배열 형태의 계산된 시그니처.

## AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr\<HashAlgorithm\>) 메서드

지정된 해시 값에 대한 시그니처를 생성합니다.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::AsymmetricSignatureFormatter::CreateSignature(System::SharedPtr<HashAlgorithm> hash)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | 시그니처를 만들 때 사용할 해시 알고리즘. |

### 반환값

바이트 배열 형태의 계산된 시그니처.

## 참조

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [AsymmetricSignatureFormatter](../)
* 클래스 [HashAlgorithm](../../hashalgorithm/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)