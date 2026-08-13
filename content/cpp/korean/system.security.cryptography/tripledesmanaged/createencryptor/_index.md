---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 명시적인 매개변수로 암호화기 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system.security.cryptography/tripledesmanaged/createencryptor/
---
## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드

명시적인 매개변수로 암호화기 객체를 생성합니다.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::TripleDESManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 암호화 키입니다. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 초기값입니다. |

### 반환 값

새로 생성된 암호화기 객체입니다.

## TripleDESManaged::CreateEncryptor() 메서드

알고리즘 객체에 정의된 매개변수로 암호화기 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## TripleDESManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드

알고리즘 객체에 정의된 매개변수로 암호화기 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICryptoTransform](../../icryptotransform/)
* 클래스 [TripleDESManaged](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)