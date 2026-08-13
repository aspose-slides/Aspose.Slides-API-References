---
title: VerifySignature()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터에 대한 서명을 검증합니다.
type: docs
weight: 27
url: /ko/system.security.cryptography/asymmetricsignaturedeformatter/verifysignature/
---
## AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드

데이터에 대한 서명을 검증합니다.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::ArrayPtr<uint8_t> rgbHash, System::ArrayPtr<uint8_t> rgbSignature)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Data](../../../system.data/) **rgbSignature** 로 서명되었습니다. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터에 대해 검증할 서명. |

### 반환 값

서명 검증이 성공하면 true, 그렇지 않으면 false.

## AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr\<HashAlgorithm\>, System::ArrayPtr\<uint8_t\>) 메서드

데이터에 대한 서명을 검증합니다. 구현되지 않았습니다.

```cpp
virtual bool System::Security::Cryptography::AsymmetricSignatureDeformatter::VerifySignature(System::SharedPtr<HashAlgorithm> hash, System::ArrayPtr<uint8_t> rgbSignature)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| hash | [System::SharedPtr](../../../system/sharedptr/)\<[HashAlgorithm](../../hashalgorithm/)\> | 해싱에 사용할 알고리즘. |
| rgbSignature | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 데이터에 대해 검증할 서명. |

### 반환 값

서명 검증이 성공하면 true, 그렇지 않으면 false.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [AsymmetricSignatureDeformatter](../)
* 클래스 [HashAlgorithm](../../hashalgorithm/)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)