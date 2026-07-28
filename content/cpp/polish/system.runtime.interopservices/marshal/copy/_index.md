---
title: Copy()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Implementuje semantykę public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /pl/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) metoda

Implementuje semantykę public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| container | Typ docelowego kontenera. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const IntPtr | Wskaźnik danych źródłowych. |
| destination | container\&& | Kontener, do którego kopiowane są dane. |
| startIndex | int | Indeks początkowy źródła. |
| length | int | Liczba elementów do skopiowania. |

## Marshal::Copy(const void *, container\&&, int, int) metoda

Implementuje semantykę public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| container | Typ docelowego kontenera. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const void * | Wskaźnik danych źródłowych. |
| destination | container\&& | Kontener, do którego kopiowane są dane. |
| startIndex | int | Indeks początkowy źródła. |
| length | int | Liczba elementów do skopiowania. |

## Marshal::Copy(const container\&, int, void *, int) metoda

Implementuje semantykę public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| container | Typ źródłowego kontenera. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const container\& | Wskaźnik danych źródłowych. |
| startIndex | int | Indeks początkowy źródła. |
| destination | void * | Wskaźnik danych docelowych. |
| length | int | Liczba elementów do skopiowania. |

## Marshal::Copy(const container\&, int, IntPtr, int) metoda

Implementuje semantykę public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Parametry szablonu

| Parametr | Opis |
| --- | --- |
| container | Typ źródłowego kontenera. |

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| source | const container\& | Wskaźnik danych źródłowych. |
| startIndex | int | Indeks początkowy źródła. |
| destination | IntPtr | Wskaźnik danych docelowych. |
| length | int | Liczba elementów do skopiowania. |

## Zobacz także

* Klasa [Marshal](../)
* Przestrzeń nazw [System::Runtime::InteropServices](../../)
* Biblioteka [Aspose.Slides](../../../)