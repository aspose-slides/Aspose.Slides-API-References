---
title: Copy()
second_title: Aspose.Slides for C++ API 참조
description: public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 메서드의 동작을 구현합니다.
type: docs
weight: 1
url: /ko/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) 메서드

public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 메서드의 동작을 구현합니다.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| container | Destination container type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const IntPtr | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const void *, container\&&, int, int) 메서드

public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) 메서드의 동작을 구현합니다.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| container | Destination container type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const void * | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, void *, int) 메서드

public static void Copy(char[] source, int startIndex, IntPtr destination, int length) 메서드의 동작을 구현합니다.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| container | Source container type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | void * | Destination data pointer. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, IntPtr, int) 메서드

public static void Copy(char[] source, int startIndex, IntPtr destination, int length) 메서드의 동작을 구현합니다.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### 템플릿 매개변수

| 매개변수 | 설명 |
| --- | --- |
| container | Source container type. |

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | IntPtr | Destination data pointer. |
| length | int | Number of elements to copy. |

## 참고

* 클래스 [Marshal](../)
* 네임스페이스 [System::Runtime::InteropServices](../../)
* 라이브러리 [Aspose.Slides](../../../)