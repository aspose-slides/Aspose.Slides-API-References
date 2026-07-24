---
title: Copy()
second_title: Aspose.Slides für C++ API-Referenz
description: Implementiert die Semantik von public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /de/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) method

Implementiert die Semantik von public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| container | Zielcontainertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const IntPtr | Quell-Datenzeiger. |
| destination | container\&& | Container, in den die Daten kopiert werden. |
| startIndex | int | Startindex der Quelle. |
| length | int | Anzahl der zu kopierenden Elemente. |

## Marshal::Copy(const void *, container\&&, int, int) method

Implementiert die Semantik von public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| container | Zielcontainertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const void * | Quell-Datenzeiger. |
| destination | container\&& | Container, in den die Daten kopiert werden. |
| startIndex | int | Startindex der Quelle. |
| length | int | Anzahl der zu kopierenden Elemente. |

## Marshal::Copy(const container\&, int, void *, int) method

Implementiert public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| container | Quellcontainertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const container\& | Quell-Datenzeiger. |
| startIndex | int | Startindex der Quelle. |
| destination | void * | Ziel-Datenzeiger. |
| length | int | Anzahl der zu kopierenden Elemente. |

## Marshal::Copy(const container\&, int, IntPtr, int) method

Implementiert public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| container | Quellcontainertyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| source | const container\& | Quell-Datenzeiger. |
| startIndex | int | Startindex der Quelle. |
| destination | IntPtr | Ziel-Datenzeiger. |
| length | int | Anzahl der zu kopierenden Elemente. |

## Siehe auch

* Klasse [Marshal](../)
* Namensraum [System::Runtime::InteropServices](../../)
* Bibliothek [Aspose.Slides](../../../)