---
title: PtrToStringAuto()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 비관리형 널 종료 문자열에서 관리되는 String을 생성합니다.
type: docs
weight: 287
url: /ko/system.runtime.interopservices/marshal/ptrtostringauto/
---
## Marshal::PtrToStringAuto(IntPtr) 메서드

관리되는 [String](../../../system/string/)를 비관리형 널 종료 문자열에서 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 비관리형 문자열에 대한 포인터입니다. |

### 반환 값

관리되는 문자열.

## Marshal::PtrToStringAuto(IntPtr, int) 메서드

관리되는 [String](../../../system/string/)를 비관리형 문자열에서 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAuto(IntPtr ptr, int length)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 비관리형 문자열에 대한 포인터입니다. |
| length | int | 비관리형 문자열의 길이입니다. |

### 반환 값

관리되는 문자열.

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [Marshal](../)
* 네임스페이스 [System::Runtime::InteropServices](../../)
* 라이브러리 [Aspose.Slides](../../../)