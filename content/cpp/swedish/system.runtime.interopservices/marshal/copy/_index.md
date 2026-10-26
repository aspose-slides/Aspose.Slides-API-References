---
title: Copy()
second_title: Aspose.Slides för C++ API-referens
description: Implementerar public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantik.
type: docs
weight: 1
url: /sv/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) metod

Implementerar public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantik.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| container | Typ av destinationscontainer. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const IntPtr | Pekare till källdata. |
| destination | container\&& | Container att kopiera data till. |
| startIndex | int | Startindex för källan. |
| length | int | Antal element att kopiera. |

## Marshal::Copy(const void *, container\&&, int, int) metod

Implementerar public static void Copy(IntPtr source, byte[] destination, int startIndex, int length) semantik.

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| container | Typ av destinationscontainer. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const void * | Pekare till källdata. |
| destination | container\&& | Container att kopiera data till. |
| startIndex | int | Startindex för källan. |
| length | int | Antal element att kopiera. |

## Marshal::Copy(const container\&, int, void *, int) metod

Implementerar public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| container | Typ av källcontainer. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const container\& | Pekare till källdata. |
| startIndex | int | Startindex för källan. |
| destination | void * | Pekare till destinationsdata. |
| length | int | Antal element att kopiera. |

## Marshal::Copy(const container\&, int, IntPtr, int) metod

Implementerar public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| container | Typ av källcontainer. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| source | const container\& | Pekare till källdata. |
| startIndex | int | Startindex för källan. |
| destination | IntPtr | Pekare till destinationsdata. |
| length | int | Antal element att kopiera. |

## Se även

* Klass [Marshal](../)
* Namnrymd [System::Runtime::InteropServices](../../)
* Bibliotek [Aspose.Slides](../../../)