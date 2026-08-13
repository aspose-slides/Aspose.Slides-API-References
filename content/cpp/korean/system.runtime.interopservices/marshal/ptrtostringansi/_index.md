---
title: PtrToStringAnsi()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비관리 zero-terminated UTF8 문자열에서 관리되는 String을 생성합니다.
type: docs
weight: 274
url: /ko/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) 메서드

관리되지 않은 zero-terminated UTF8 문자열에서 관리된 [String](../../../system/string/)를 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 비관리 문자열에 대한 포인터. |

### 반환값

관리된 string.

## Marshal::PtrToStringAnsi(IntPtr, int) 메서드

관리되지 않은 UTF8 문자열에서 관리된 [String](../../../system/string/)를 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 비관리 문자열에 대한 포인터. |
| length | int | 비관리 문자열의 길이. |

### 반환값

관리된 string.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [Marshal](../)
* 네임스페이스 [System::Runtime::InteropServices](../../)
* 라이브러리 [Aspose.Slides](../../../)