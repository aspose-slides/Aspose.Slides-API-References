---
title: PtrToStringUTF8()
second_title: Aspose.Slides for C++ API 참조
description: 비관리형 zero-terminated UTF8 문자열에서 관리형 String을 생성합니다.
type: docs
weight: 313
url: /ko/system.runtime.interopservices/marshal/ptrtostringutf8/
---
## Marshal::PtrToStringUTF8(IntPtr) 메서드

비관리형 zero-terminated UTF8 문자열에서 관리형 [String](../../../system/string/)를 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 비관리형 문자열에 대한 포인터. |

### 반환값

관리형 문자열.

## Marshal::PtrToStringUTF8(IntPtr, int) 메서드

비관리형 UTF8 문자열에서 관리형 [String](../../../system/string/)를 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUTF8(IntPtr ptr, int length)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 비관리형 문자열에 대한 포인터. |
| length | int | 비관리형 문자열의 길이. |

### 반환값

관리형 문자열.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [Marshal](../)
* 네임스페이스 [System::Runtime::InteropServices](../../)
* 라이브러리 [Aspose.Slides](../../../)