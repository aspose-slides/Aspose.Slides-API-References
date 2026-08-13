---
title: Decrypt()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 메시지를 복호화합니다. 구현되지 않았습니다.
type: docs
weight: 105
url: /ko/system.security.cryptography/rsacryptoserviceprovider/decrypt/
---
## RSACryptoServiceProvider::Decrypt(const ByteArrayPtr\&, bool) 메서드

메시지를 복호화합니다. 구현되지 않았습니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(const ByteArrayPtr &rgb, bool use_oaep)
```


### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| rgb | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) 복호화용. |
| use_oaep | **bool** | True OAEP 패딩을 사용하려면, false PKCS#1 v1.5 패딩을 사용하려면. |

### 반환값

복호화된 데이터 배열.

## RSACryptoServiceProvider::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 메서드

지정된 패딩 모드를 사용하여 입력 데이터를 복호화합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::RSACryptoServiceProvider::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 복호화할 배열. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 패딩 모드. |

### 반환값

바이트 배열 형식의 복호화된 데이터.

## 참고

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [RSACryptoServiceProvider](../)
* 클래스 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)