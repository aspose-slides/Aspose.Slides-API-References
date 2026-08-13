---
title: SecureStringToGlobalAllocAnsi()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 보안 문자열의 내용을 비관리 메모리로 복사하고 ANSI 형식으로 변환합니다.
type: docs
weight: 1
url: /ko/system.security/securestringmarshal/securestringtoglobalallocansi/
---
## SecureStringMarshal::SecurePtr\<Security::SecureString\>\&) 메서드


지정된 보안 문자열의 내용을 비관리 메모리로 복사하고 ANSI 형식으로 변환합니다.

```cpp
static IntPtr System::Security::SecureStringMarshal::SecureStringToGlobalAllocAnsi(const SharedPtr<Security::SecureString> &s)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| s | const [SharedPtr](../../../system/sharedptr/)\<[Security::SecureString](../../securestring/)\>\& | 보안 문자열. |

### 반환값

비관리 메모리의 주소.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [SecureString](../../securestring/)
* 클래스 [SecureStringMarshal](../)
* 네임스페이스 [System::Security](../../)
* 라이브러리 [Aspose.Slides](../../../)