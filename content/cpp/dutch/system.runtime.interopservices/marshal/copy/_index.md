---
title: Copy()
second_title: Aspose.Slides voor C++ API-referentie
description: Implementeert public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiek.
type: docs
weight: 1
url: /nl/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) methode

Implementeert public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiek.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| container | Destination container type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| source | const IntPtr | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const void *, container\&&, int, int) methode

Implementeert public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantiek.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| container | Destination container type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| source | const void * | Source data pointer. |
| destination | container\&& | Container to copy data into. |
| startIndex | int | Source start index. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, void *, int) methode

Implementeert public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| container | Source container type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | void * | Destination data pointer. |
| length | int | Number of elements to copy. |

## Marshal::Copy(const container\&, int, IntPtr, int) methode

Implementeert public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| container | Source container type. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| source | const container\& | Source data pointer. |
| startIndex | int | Source start index. |
| destination | IntPtr | Destination data pointer. |
| length | int | Number of elements to copy. |

## Zie ook

* Klasse [Marshal](../)
* Naamruimte [System::Runtime::InteropServices](../../)
* Bibliotheek [Aspose.Slides](../../../)