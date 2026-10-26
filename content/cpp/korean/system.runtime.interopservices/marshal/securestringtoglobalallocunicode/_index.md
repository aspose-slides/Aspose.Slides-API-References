---
title: SecureStringToGlobalAllocUnicode()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 Secure string의 내용을 관리되지 않는 메모리로 복사합니다.
type: docs
weight: 170
url: /ko/system.runtime.interopservices/marshal/securestringtoglobalallocunicode/
---
## Marshal::SecureStringToGlobalAllocUnicode(const SharedPtr\<Security::SecureString\>\&) method


지정된 Secure string의 내용을 관리되지 않는 메모리로 복사합니다.

```cpp
static IntPtr System::Runtime::InteropServices::Marshal::SecureStringToGlobalAllocUnicode(const SharedPtr<Security::SecureString> &s)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [SharedPtr](../../../system/sharedptr/)\<[Security::SecureString](../../../system.security/securestring/)\>\& | Secure string. |

### Return Value

관리되지 않는 메모리의 주소입니다.

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [SecureString](../../../system.security/securestring/)
* 클래스 [Marshal](../)
* 네임스페이스 [System::Runtime::InteropServices](../../)
* 라이브러리 [Aspose.Slides](../../../)