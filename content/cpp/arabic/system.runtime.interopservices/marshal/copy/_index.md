---
title: Copy()
second_title: مرجع API Aspose.Slides للغة C++
description: ينفّذ دلالات الدالة العامة الثابتة public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /ar/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) طريقة

ينفّذ دلالات الدالة العامة الثابتة public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| container | نوع الحاوية الوجهة. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| source | const IntPtr | مؤشر بيانات المصدر. |
| destination | container\&& | الحاوية التي يُنسخ إليها البيانات. |
| startIndex | int | فهرس البدء للمصدر. |
| length | int | عدد العناصر التي تُنسخ. |

## Marshal::Copy(const void *, container\&&, int, int) طريقة

ينفّذ دلالات الدالة العامة الثابتة public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| container | نوع الحاوية الوجهة. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| source | const void * | مؤشر بيانات المصدر. |
| destination | container\&& | الحاوية التي يُنسخ إليها البيانات. |
| startIndex | int | فهرس البدء للمصدر. |
| length | int | عدد العناصر التي تُنسخ. |

## Marshal::Copy(const container\&, int, void *, int) طريقة

ينفّذ الدالة العامة الثابتة public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| container | نوع الحاوية المصدر. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| source | const container\& | مؤشر بيانات المصدر. |
| startIndex | int | فهرس البدء للمصدر. |
| destination | void * | مؤشر بيانات الوجهة. |
| length | int | عدد العناصر التي تُنسخ. |

## Marshal::Copy(const container\&, int, IntPtr, int) طريقة

ينفّذ الدالة العامة الثابتة public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| container | نوع الحاوية المصدر. |

### المعاملات

| Parameter | Type | Description |
| --- | --- | --- |
| source | const container\& | مؤشر بيانات المصدر. |
| startIndex | int | فهرس البدء للمصدر. |
| destination | IntPtr | مؤشر بيانات الوجهة. |
| length | int | عدد العناصر التي تُنسخ. |

## انظر أيضًا

* فئة [Marshal](../)
* نطاق الاسم [System::Runtime::InteropServices](../../)
* المكتبة [Aspose.Slides](../../../)