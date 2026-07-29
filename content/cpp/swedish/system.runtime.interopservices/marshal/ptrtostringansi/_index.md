---
title: PtrToStringAnsi()
second_title: Aspose.Slides för C++ API-referens
description: Skapar en hanterad String från en ohanterad nollterminerad UTF8-sträng.
type: docs
weight: 274
url: /sv/system.runtime.interopservices/marshal/ptrtostringansi/
---
## Marshal::PtrToStringAnsi(IntPtr) metod


Skapar ett hanterat [String](../../../system/string/) från en ohanterad nollterminerad UTF8-sträng.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | IntPtr | Pekare till den ohanterade strängen. |

### Returvärde

En hanterad sträng.

## Marshal::PtrToStringAnsi(IntPtr, int) metod


Skapar ett hanterat [String](../../../system/string/) från en ohanterad UTF8-sträng.

```cpp
static String System::Runtime::InteropServices::Marshal::PtrToStringAnsi(IntPtr ptr, int length)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ptr | IntPtr | Pekare till den ohanterade strängen. |
| length | int | Längd på den ohanterade strängen. |

### Returvärde

En hanterad sträng.

## Se också

* Klass [String](../../../system/string/)
* Klass [Marshal](../)
* Namnrymd [System::Runtime::InteropServices](../../)
* Bibliotek [Aspose.Slides](../../../)