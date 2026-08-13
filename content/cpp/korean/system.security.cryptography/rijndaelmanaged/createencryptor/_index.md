---
title: CreateEncryptor()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 명시적인 매개변수로 encryptor 객체를 생성합니다.
type: docs
weight: 1
url: /ko/system.security.cryptography/rijndaelmanaged/createencryptor/
---
## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

encryptor 객체를 명시적인 매개변수로 생성합니다.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 암호화 키. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 초기값. |

### Return Value

새로 생성된 encryptor 객체.

## RijndaelManaged::CreateEncryptor() method

알고리즘 객체에 정의된 매개변수로 encryptor 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor()
```

## RijndaelManaged::CreateEncryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

알고리즘 객체에 정의된 매개변수로 encryptor 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateEncryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)