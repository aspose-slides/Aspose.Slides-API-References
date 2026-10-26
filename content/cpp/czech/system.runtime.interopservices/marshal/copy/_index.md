---
title: Copy()
second_title: Aspose.Slides pro C++ referenční dokumentace API
description: Implementuje public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiku.
type: docs
weight: 1
url: /cs/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) metoda

Implementuje public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiku.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| container | Destination container type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const IntPtr | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const void *, container\&&, int, int) metoda

Implementuje public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiku.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| container | Destination container type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const void * | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, void *, int) metoda

Implementuje public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| container | Source container type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | void * | Destination data pointer. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, IntPtr, int) metoda

Implementuje public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| container | Source container type. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | IntPtr | Destination data pointer. |
| length | int | Number of elements to copy. |

## Viz také

* Třída [Marshal](../)
* Jmenný prostor [System::Runtime::InteropServices](../../)
* Knihovna [Aspose.Slides](../../../)