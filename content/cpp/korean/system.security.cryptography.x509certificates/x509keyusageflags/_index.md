---
title: X509KeyUsageFlags
second_title: Aspose.Slides for C++ API 레퍼런스
description: 인증서 키를 어떻게 사용할 수 있는지 정의합니다.
type: docs
weight: 274
url: /ko/system.security.cryptography.x509certificates/x509keyusageflags/
---
## X509KeyUsageFlags 열거형


인증서 키를 어떻게 사용할 수 있는지 정의합니다.

```cpp
enum class X509KeyUsageFlags : int32_t
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| None | 0 | 키 사용 매개변수가 없습니다. |
| EncipherOnly | 1 | 키는 암호화에만 사용할 수 있습니다. |
| CrlSign | 2 | 키는 인증서 폐기 목록을 서명하는 데 사용할 수 있습니다. |
| KeyCertSign | 4 | 키는 인증서를 서명하는 데 사용할 수 있습니다. |
| KeyAgreement | 8 | 키는 키 합의를 결정하는 데 사용할 수 있습니다. |
| DataEncipherment | 16 | 키는 데이터 암호화에 사용할 수 있습니다. |
| KeyEncipherment | 32 | 키는 키 암호화에 사용할 수 있습니다. |
| NonRepudiation | 64 | 키는 인증에 사용할 수 있습니다. |
| DigitalSignature | 128 | 키는 디지털 서명으로 사용할 수 있습니다. |
| DecipherOnly | 32768 | 키는 복호화에만 사용할 수 있습니다. |

## 참고

* 네임스페이스 [System::Security::Cryptography::X509Certificates](../)
* 라이브러리 [Aspose.Slides](../../)