---
title: Encrypt()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 패딩 모드를 사용하여 입력 데이터를 암호화합니다.
type: docs
weight: 53
url: /ko/system.security.cryptography/rsa/encrypt/
---
## RSA::Encrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 메서드


입력 데이터를 지정된 패딩 모드로 암호화합니다.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Encrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 암호화할 배열. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 패딩 모드. |

### 반환 값

바이트 배열 형식의 암호화된 데이터.

## 참고

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 클래스 [RSA](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)