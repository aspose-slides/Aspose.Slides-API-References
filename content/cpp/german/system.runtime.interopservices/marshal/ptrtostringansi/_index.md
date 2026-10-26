---
title: PtrToStringAnsi()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt einen verwalteten String aus einem nicht verwalteten nullterminierten UTF8-String.
type: docs
weight: 274
url: /de/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) Methode

Erstellt ein verwaltetes [String](../../../system/string/) aus einem nicht verwalteten nullterminierten UTF8-String.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | IntPtr | Zeiger auf den nicht verwalteten String. |

### Rückgabewert

Ein verwalteter String.

## Marshal::PtrToStringAnsi(IntPtr, int) Methode

Erstellt ein verwaltetes [String](../../../system/string/) aus einem nicht verwalteten UTF8-String.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ptr | IntPtr | Zeiger auf den nicht verwalteten String. |
| length | int | Länge des nicht verwalteten Strings. |

### Rückgabewert

Ein verwalteter String.

## Siehe auch

* Klasse [String](../../../system/string/)
* Klasse [Marshal](../)
* Namensraum [System::Runtime::InteropServices](../../)
* Library [Aspose.Slides](../../../)