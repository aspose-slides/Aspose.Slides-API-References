---
title: X509KeyStorageFlags
second_title: Aspose.Slides for C++ API 참조
description: 키를 저장하는 방법을 정의합니다.
type: docs
weight: 261
url: /ko/system.security.cryptography.x509certificates/x509keystorageflags/
---
## X509KeyStorageFlags enum


키를 저장하는 방법을 정의합니다.

```cpp
enum class X509KeyStorageFlags : int32_t
```

### 값

| 이름 | 값 | 설명 |
| --- | --- | --- |
| DefaultKeySet | 0 | 기본 키 세트를 사용합니다. |
| UserKeySet | 1 | 머신 로컬 저장소 대신 사용자 연관 저장소를 사용합니다. |
| MachineKeySet | 2 | 사용자 저장소 대신 로컬 머신 저장소를 사용합니다. |
| Exportable | 4 | 가져온 키를 내보낼 수 있도록 표시합니다. |
| UserProtected | 8 | 키가 사용 중임을 사용자에게 알립니다. |
| PersistKeySet | 16 | 인증서를 가져올 때 키가 지속됩니다. |

## 참조

* 네임스페이스 [System::Security::Cryptography::X509Certificates](../)
* 라이브러리 [Aspose.Slides](../../)