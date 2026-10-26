---
title: SignHash()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 입력 값의 서명을 계산합니다.
type: docs
weight: 196
url: /ko/system.security.cryptography/dsacryptoserviceprovider/signhash/
---
## DSACryptoServiceProvider::SignHash(const ByteArrayPtr\&, const String\&) 메서드


지정된 입력 값의 서명을 계산합니다.

```cpp
ByteArrayPtr System::Security::Cryptography::DSACryptoServiceProvider::SignHash(const ByteArrayPtr &rgb_hash, const String &str)
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgb_hash | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 서명될 데이터의 해시 값. |
| str | const [String](../../../system/string/)\& | 해시를 생성하는 데 사용된 해시 알고리즘 식별자. |

### Return Value

[DSA](../../dsa/) 지정된 데이터에 대한 서명.

## See Also

* 타입정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 클래스 [String](../../../system/string/)
* 클래스 [DSACryptoServiceProvider](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)