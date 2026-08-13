---
title: CreateDecryptor()
second_title: C++용 Aspose.Slides API 참조
description: 명시적 매개변수를 사용하여 복호화기 객체를 생성합니다.
type: docs
weight: 14
url: /ko/system.security.cryptography/rc2managed/createdecryptor/
---
## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드

명시적 매개변수를 사용하여 복호화기 객체를 생성합니다.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RC2Managed::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 암호화 키. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 초기값. |

### 반환값

새로 생성된 복호화기 객체.

## RC2Managed::CreateDecryptor() 메서드

알고리즘 객체에 의해 정의된 매개변수로 복호화기 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RC2Managed::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) 메서드

알고리즘 객체에 의해 정의된 매개변수로 복호화기 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ICryptoTransform](../../icryptotransform/)
* 클래스 [RC2Managed](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)