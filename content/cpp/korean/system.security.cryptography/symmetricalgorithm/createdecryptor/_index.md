---
title: CreateDecryptor()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 알고리즘 객체와 연관된 매개변수를 사용하여 복호화기를 생성합니다.
type: docs
weight: 196
url: /ko/system.security.cryptography/symmetricalgorithm/createdecryptor/
---
## SymmetricAlgorithm::CreateDecryptor() 메서드


알고리즘 개체와 연관된 매개변수를 사용하여 복호화기를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```


### 반환값

새로 생성된 복호화기 객체.

## SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드


명시적인 매개변수를 사용하여 복호화기를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 사용할 키. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 사용할 초기값. |

### 반환값

새로 생성된 복호화기 객체.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICryptoTransform](../../icryptotransform/)
* 클래스 [SymmetricAlgorithm](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)