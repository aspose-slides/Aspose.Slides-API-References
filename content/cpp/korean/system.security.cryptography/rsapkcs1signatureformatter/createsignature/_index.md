---
title: CreateSignature()
second_title: C++용 Aspose.Slides API 참조
description: 데이터에 서명합니다.
type: docs
weight: 27
url: /ko/system.security.cryptography/rsapkcs1signatureformatter/createsignature/
---
## RSAPKCS1SignatureFormatter::CreateSignature(System::ArrayPtr\<uint8_t\>) 메서드

데이터에 서명합니다.

```cpp
virtual System::ArrayPtr<uint8_t> System::Security::Cryptography::RSAPKCS1SignatureFormatter::CreateSignature(System::ArrayPtr<uint8_t> rgbHash) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| rgbHash | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | 서명할 데이터의 해시. |

### 반환 값

계산된 서명.

## 참고

* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [RSAPKCS1SignatureFormatter](../)
* 네임스페이스 [System::Security::Cryptography](../../)
* 라이브러리 [Aspose.Slides](../../../)