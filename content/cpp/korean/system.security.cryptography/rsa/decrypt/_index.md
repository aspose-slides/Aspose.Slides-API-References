---
title: Decrypt()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 패딩 모드를 사용하여 입력 데이터를 복호화합니다.
type: docs
weight: 27
url: /ko/system.security.cryptography/rsa/decrypt/
---
## RSA::Decrypt(ByteArrayPtr, SharedPtr\<RSAEncryptionPadding\>) 메서드


지정된 패딩 모드를 사용하여 입력 데이터를 복호화합니다.

```cpp
virtual ByteArrayPtr System::Security::Cryptography::RSA::Decrypt(ByteArrayPtr data, SharedPtr<RSAEncryptionPadding> padding)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| data | [ByteArrayPtr](../../../system/bytearrayptr/) | [Byte](../../../system/byte/) 복호화할 배열. |
| padding | [SharedPtr](../../../system/sharedptr/)\<[RSAEncryptionPadding](../../rsaencryptionpadding/)\> | 패딩 모드. |

### 반환값

바이트 배열 형식의 복호화된 데이터.

## 참조

* Typedef [ByteArrayPtr](../../../system/bytearrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [RSAEncryptionPadding](../../rsaencryptionpadding/)
* 클래스 [RSA](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* Library [Aspose.Slides](../../../)