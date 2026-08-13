---
title: CreateDecryptor()
second_title: Aspose.Slides for C++ API 참조
description: 명시적인 매개변수를 사용하여 복호화 객체를 생성합니다.
type: docs
weight: 14
url: /ko/system.security.cryptography/rijndaelmanaged/createdecryptor/
---
## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

명시적인 매개변수를 사용하여 복호화 객체를 생성합니다.

```cpp
SharedPtr<ICryptoTransform> System::Security::Cryptography::RijndaelManaged::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV) override
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| rgbKey | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 암호화 키입니다. |
| rgbIV | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 바이트 배열 형태의 초기값입니다. |

### Return Value

새로 생성된 복호화 객체입니다.

## RijndaelManaged::CreateDecryptor() method

알고리즘 객체에 정의된 매개변수를 사용하여 복호화 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor()
```

## RijndaelManaged::CreateDecryptor(System::ArrayPtr\<uint8_t\>, System::ArrayPtr\<uint8_t\>) method

알고리즘 객체에 정의된 매개변수를 사용하여 복호화 객체를 생성합니다.

```cpp
virtual SharedPtr<ICryptoTransform> System::Security::Cryptography::SymmetricAlgorithm::CreateDecryptor(System::ArrayPtr<uint8_t> rgbKey, System::ArrayPtr<uint8_t> rgbIV)=0
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICryptoTransform](../../icryptotransform/)
* Class [RijndaelManaged](../)
* Namespace [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)