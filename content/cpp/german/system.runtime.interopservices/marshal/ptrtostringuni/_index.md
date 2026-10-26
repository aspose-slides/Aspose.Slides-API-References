---
title: PtrToStringUni()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen verwalteten String aus einem unverwalteten nullterminierten Unicode-String.
type: docs
weight: 300
url: /de/system.runtime.interopservices/marshal/ptrtostringuni/
---
## Marshal::PtrToStringUni(IntPtr) Methode

Erstellt einen verwalteten [String](../../../system/string/) aus einem unverwalteten nullterminierten Unicode-String.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | IntPtr | Zeiger auf den unverwalteten String. |

### Rückgabewert

Ein verwalteter String.

## Marshal::PtrToStringUni(IntPtr, int) Methode

Erstellt einen verwalteten [String](../../../system/string/) aus einem unverwalteten Unicode-String.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringUni(IntPtr ptr, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | IntPtr | Zeiger auf den unverwalteten String. |
| length | int | Länge des unverwalteten Strings. |

### Rückgabewert

Ein verwalteter String.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [Marshal](../)
* Namensraum [System::Runtime::InteropServices](../../)
* Bibliothek [Aspose.Slides](../../../)