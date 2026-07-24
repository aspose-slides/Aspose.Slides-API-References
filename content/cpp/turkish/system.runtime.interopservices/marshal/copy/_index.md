---
title: Copy()
second_title: Aspose.Slides for C++ API Referansı
description: Public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) işlevselliğini uygular.
type: docs
weight: 1
url: /tr/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) yöntemi

Public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) işlevselliğini uygular.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| container | Destination container type. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const IntPtr | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const void *, container\&&, int, int) yöntemi

Public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) işlevselliğini uygular.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| container | Destination container type. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const void * | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, void *, int) yöntemi

Public static void Copy(char[] source, int startIndex, IntPtr destination, int length) işlevselliğini uygular.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| container | Source container type. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | void * | Destination data pointer. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, IntPtr, int) yöntemi

Public static void Copy(char[] source, int startIndex, IntPtr destination, int length) işlevselliğini uygular.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| container | Source container type. |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | IntPtr | Destination data pointer. |
| length | int | Number of elements to copy. |

## İlgili

* Sınıf [Marshal](../)
* Ad alanı [System::Runtime::InteropServices](../../)
* Kütüphane [Aspose.Slides](../../../)