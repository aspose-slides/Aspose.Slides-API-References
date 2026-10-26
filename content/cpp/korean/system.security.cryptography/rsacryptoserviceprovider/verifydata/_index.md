---
title: VerifyData()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터 서명을 확인합니다.
type: docs
weight: 209
url: /ko/system.security.cryptography/rsacryptoserviceprovider/verifydata/
---
## RSACryptoServiceProvider::VerifyData(const ByteArrayPtr\&, const SharedPtr\<Object\>\&, const ByteArrayPtr\&) 메서드

데이터 서명을 확인합니다.

```cpp
bool System::Security::Cryptography::RSACryptoServiceProvider::VerifyData(const ByteArrayPtr &buffer, const SharedPtr<Object> &halg, const ByteArrayPtr &signature)
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | [Data](../../../system.data/) 의 서명을 확인하기 위해. |
| halg | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | 사용할 해시 알고리즘. |
| signature | const [ByteArrayPtr](../../../system/bytearrayptr/)\& | 받은 서명. |

### 반환값

서명이 유효하면 true, 그렇지 않으면 false.

## 또보기

* 타입정의 [ByteArrayPtr](../../../system/bytearrayptr/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [Object](../../../system/object/)
* 클래스 [RSACryptoServiceProvider](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)