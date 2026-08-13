---
title: SecureStringToGlobalAllocAnsi()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 보안 문자열의 내용을 복사하여 관리되지 않는 메모리로 옮기고, ANSI 형식으로 변환합니다.
type: docs
weight: 157
url: /ko/system.runtime.interopservices/marshal/securestringtoglobalallocansi/
---
## Marshal::SecureStringToGlobalAllocAnsi(const SharedPtr\<Security::SecureString\>\&) 메서드

지정된 보안 문자열의 내용을 복사하여 관리되지 않는 메모리로 옮기며, ANSI 형식으로 변환합니다.

```cpp
static IntPtr System::Runtime::InteropServices::Marshal::SecureStringToGlobalAllocAnsi(const SharedPtr<Security::SecureString> &s)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [SharedPtr](../../../system/sharedptr/)\<[Security::SecureString](../../../system.security/securestring/)\>\& | 보안 문자열. |

### 반환 값

관리되지 않는 메모리의 주소.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [SecureString](../../../system.security/securestring/)
* 클래스 [Marshal](../)
* 네임스페이스 [System::Runtime::InteropServices](../../)
* 라이브러리 [Aspose.Slides](../../../)