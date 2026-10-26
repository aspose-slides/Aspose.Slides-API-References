---
title: Encrypt()
second_title: Aspose.Slides for C++ API 참조
description: 메시지를 암호화합니다. 구현되지 않았습니다.
type: docs
weight: 118
url: /ko/system.security.cryptography/rsacryptoserviceprovider/encrypt/
---
## RSACryptoServiceProvider::Encrypt(const ByteArrayPtr\&, bool) 메서드

메시지를 암호화합니다. 구현되지 않았습니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(const ByteArrayPtr &rgb, bool use_oaep)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 암호화할 [Data](../../../system.data/). |
| use_oaep | **bool** | OAEP 패딩을 사용하려면 true, PKCS#1 v1.5 패딩을 사용하려면 false. |

### 반환값

암호화된 데이터 배열.

## RSACryptoServiceProvider::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 메서드

지정된 패딩 모드를 사용하여 입력 데이터를 암호화합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | 암호화할 [Byte](../../../system/byte/) 배열. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 패딩 모드. |

### 반환값

바이트 배열 형식의 암호화된 데이터.

## 참조

* typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* typedef [SharedPtr](../../../system/sharedptr/)
* class [RSACryptoServiceProvider](../)
* class [RSAEncryptionPadding](../../rsaencryptionpadding/)
* namespace [System::Security::Cryptography](../../)
* library [Aspose.Slides](../../../)