---
title: PtrToStringUni()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 관리되지 않은 널 종료 유니코드 문자열에서 관리되는 String을 생성합니다.
type: docs
weight: 300
url: /ko/system.runtime.interopservices/marshal/ptrtostringuni/
---
## Marshal::PtrToStringUni(IntPtr) 메서드

관리되는 [String](../../../system/string/)를 관리되지 않은 널 종료 유니코드 문자열에서 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 관리되지 않은 문자열에 대한 포인터. |

### 반환 값

관리되는 문자열.

## Marshal::PtrToStringUni(IntPtr, int) 메서드

관리되는 [String](../../../system/string/)를 관리되지 않은 유니코드 문자열에서 생성합니다.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr, int length)
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| ptr | IntPtr | 관리되지 않은 문자열에 대한 포인터. |
| length | int | 관리되지 않은 문자열의 길이. |

### 반환 값

관리되는 문자열.

## 추가 참고

* 클래스 [String](../../../system/string/)
* 클래스 [Marshal](../)
* 네임스페이스 [System::Runtime::InteropServices](../../)
* 라이브러리 [Aspose.Slides](../../../)