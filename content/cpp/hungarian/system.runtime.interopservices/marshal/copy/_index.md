---
title: Copy()
second_title: Aspose.Slides C++ API referencia
description: Megvalósítja a public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) szintaxisát.
type: docs
weight: 1
url: /hu/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) metódus


Megvalósítja a public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) szintaxisát.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| container | Destination container type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const IntPtr | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const void *, container\&&, int, int) metódus


Megvalósítja a public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) szintaxisát.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| container | Destination container type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const void * | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, void *, int) metódus


Megvalósítja a public static void Copy(char[] source, int startIndex, IntPtr destination, int length) szintaxisát.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| container | Source container type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | void * | Destination data pointer. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, IntPtr, int) metódus


Megvalósítja a public static void Copy(char[] source, int startIndex, IntPtr destination, int length) szintaxisát.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| container | Source container type. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | IntPtr | Destination data pointer. |
| length | int | Number of elements to copy. |

## Lásd még

* Osztály [Marshal](../)
* Névtere [System::Runtime::InteropServices](../../)
* Könyvtár [Aspose.Slides](../../../)