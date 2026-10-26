---
title: PtrToStringAnsi()
second_title: Riferimento API Aspose.Slides per C++
description: Crea una String gestita da una stringa UTF8 non gestita terminata con zero.
type: docs
weight: 274
url: /it/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) metodo

Crea un [String](../../../system/string/) gestito a partire da una stringa UTF8 non gestita terminata con zero.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | IntPtr | Puntatore alla stringa non gestita. |

### Valore restituito

Una stringa gestita.

## Marshal::PtrToStringAnsi(IntPtr, int) metodo

Crea un [String](../../../system/string/) gestito a partire da una stringa UTF8 non gestita.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ptr | IntPtr | Puntatore alla stringa non gestita. |
| length | int | Lunghezza della stringa non gestita. |

### Valore restituito

Una stringa gestita.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [Marshal](../)
* Spazio dei nomi [System::Runtime::InteropServices](../../)
* Libreria [Aspose.Slides](../../../)